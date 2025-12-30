<html>
<head>
    <meta charset="UTF-8">
    <title>Danh sách học sinh lớp 12A1</title>
    <style>
        body { font-family: Arial, sans-serif; } 

        table { border-collapse: collapse; width: 80%; margin-top: 20px; }

         th, td { border: 1px solid black; padding: 8px; text-align: center; }

          th { background-color: #f2f2f2; }

         input { margin: 5px; }

          .khung{
            text-align: bold;
            width: auto;
            height: auto;
      background:#fff;
      padding:10px;
      border-radius:6px;
      box-shadow:0 1px 3px rgba(0,0,0,0.06);
        border: 4px solid transparent;
      background: 
        linear-gradient(white, white) padding-box,
        linear-gradient(90deg, #ff7a18, #af002d, #319197) border-box;
    }
    .dam
    {font-weight: bold}
    </style>
</head>
<body>

    <h2 style="text-align: center;">Danh sách học sinh lớp 12A1</h2>
    <label class="dam">Họ và tên:</label>
    <input type="text" id="hoten" class="khung">

    <label class="dam">Ngày sinh:</label>
    <input type="date" id="ngaysinh" class="khung">


    <label class="dam">Điểm toán:</label>
    <input type="number" id="diemtoan" class="khung">

    <label class="dam">Điểm lý:</label>
    <input type="number" id="diemly" class="khung">

    <label class="dam">Điểm sinh:</label>
    <input type="number" id="diemsinh" class="khung">



    <button onclick="themHocSinh()">Thêm</button>

    <div id="khungBang">
    <table>
        <thead>
            <tr>
                <th>STT</th>
                <th>Họ và tên</th>
                <th>Ngày sinh</th>
                <th>điểm toán</th>
                <th>điểm lý</th>
                <th>điểm sinh</th>
            </tr>
        </thead>
        <tbody id="bangdulieu">
        </tbody>
    </table>
    </div>
    <br>
        <button onclick="veTruoc()"class="khung">⬅️ Về trước</button>
        <button onclick="veSau()"class="khung">➡️ Về sau</button>
        <button onclick="xuatExcel()" class="khung">📥 Xuất ra Excel</button>
<script>
let trangHienTai = 1;
let soDongMoiTrang = 3;

function hienThiTrang() {
    let bang = document.getElementById("bangdulieu");
    let cacDong = bang.getElementsByTagName("tr");
    let tongDong = cacDong.length;
    let tongTrang = Math.ceil(tongDong / soDongMoiTrang);

    for (let i = 0; i < tongDong; i++) {
        cacDong[i].style.display = "none";
    }

    let batDau = (trangHienTai - 1) * soDongMoiTrang;
    let ketThuc = batDau + soDongMoiTrang;

    for (let i = batDau; i < ketThuc && i < tongDong; i++) {
        cacDong[i].style.display = "";
    }
}

function veSau() {
    let tongDong = document.getElementById("bangdulieu").rows.length;
    let tongTrang = Math.ceil(tongDong / soDongMoiTrang);

    if (trangHienTai < tongTrang) {
        trangHienTai++;
        hienThiTrang();
    }
}

function veTruoc() {
    if (trangHienTai > 1) {
        trangHienTai--;
        hienThiTrang();
    }
}
function xuatExcel() {
    let table = document.querySelector("table");
    let html = `
        <html>
        <head>
            <meta charset="UTF-8">
            <style>
                table { border-collapse: collapse; }
                th, td {
                    border: 1px solid black;
                    padding: 5px;
                    text-align: center;
                }
                th {
                    font-weight: bold;
                    background-color: #f2f2f2;
                }
            </style>
        </head>
        <body>
            ${table.outerHTML}
        </body>
        </html>
    `;
    let blob = new Blob(
        ["\ufeff", html],
        { type: "application/vnd.ms-excel;charset=utf-8;" }
    );

    let url = URL.createObjectURL(blob);

    let a = document.createElement("a");
    a.href = url;
    a.download = "danhsach_hocsinh_12A1.xls";
    document.body.appendChild(a);
    a.click();
    document.body.removeChild(a);
}
         let stt = 1;

        function themHocSinh() {
            let hoten = document.getElementById("hoten").value;
            let ngaysinh = document.getElementById("ngaysinh").value;
            let diemtoan = document.getElementById("diemtoan").value;
            let diemly = document.getElementById("diemly").value;
            let diemsinh = document.getElementById("diemsinh").value;

            if (hoten === "" || diemtoan === "" || ngaysinh === "" || diemly ==="" || diemsinh ==="") {
                alert("Vui lòng nhập đầy đủ thông tin!");
                return;
            }

            let bang = document.getElementById("bangdulieu");
            let dong = bang.insertRow();

            dong.insertCell(0).innerHTML = stt++;
            dong.insertCell(1).innerHTML = hoten;
            dong.insertCell(2).innerHTML = ngaysinh;
            dong.insertCell(3).innerHTML = diemtoan;
            dong.insertCell(4).innerHTML = diemly;
            dong.insertCell(5).innerHTML = diemsinh;

            document.getElementById("hoten").value = "";
            document.getElementById("ngaysinh").value = "";
            document.getElementById("diemtoan").value = "";
            document.getElementById("diemly").value = "";
            document.getElementById("diemsinh").value = "";
            hienThiTrang();
        }
    document.addEventListener("DOMContentLoaded", function () {
    document.getElementById("btnTruoc").addEventListener("click", veTruoc);
    document.getElementById("btnSau").addEventListener("click", veSau);
});
    </script>
<footer style="text-align: center;">Thiết kế Website: <b>Phong – Khôi</b></footer>
</body>
</html>
