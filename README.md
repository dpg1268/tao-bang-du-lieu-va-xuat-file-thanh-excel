<html>
<head>
<meta charset="UTF-8">
<title>Kỷ niệm 26/3</title>
<style>
body{
    margin:0;
    background:#f6e27a;
    font-family: Arial;
}
/* layout mới */
.wrapper{
    display:flex;
    justify-content:center;
    align-items:flex-start;
    gap:20px;
    margin:30px;
}
/* box chung */
.sidebar{
    width:300px;
    border:3px solid red;
    border-radius:10px;
    background:#fff8c6;
    padding:15px;
    box-shadow:0 0 10px rgba(0,0,0,0.3);
}
.sidebar h3{
    text-align:center;
    color:red;
}
.sidebar p{
    margin:8px 0;
}
/* container */
.container{
    max-width:750px;
    width:100%;
    padding:30px;
    border:4px solid red;
    border-radius:10px;
    background:#fff8c6;
    box-shadow:0 0 15px rgba(0,0,0,0.2);
    flex:2;
}
/* banner */
.banner img{
    width:100%;
}
/* chữ chạy */
.marquee{
    overflow:hidden;
    background:#f6e27a;
}
.marquee p{
    white-space:nowrap;
    animation:chaychu 12s linear infinite;
    font-weight:bold;
    color:red;
}
@keyframes chaychu{
    from{transform:translateX(100%);}
    to{transform:translateX(-100%);}
}
/* header */
.header{
    display:flex;
    gap:15px;
}
.tv, .hd{
    flex:1;
    max-width:260px;
}
.left{
    width:40%;
}
.left img{
    width:100%;
    margin-bottom:10px;
}
.right{
    width:60%;
    text-align:center;
}
/* activity */
.activity{
    flex-direction:column; 
    display:flex;
    align-items:center;
    gap:10px;
    margin:10px 0;
}
.activity a{
    display:flex;
    align-items:center;
    gap:10px;
    text-decoration:none;
    color:black;
}
.activity img{
    width:200px;
    height:100px;
    object-fit:cover;
    border-radius:8px;
    transition:0.3s;
}
.activity a:hover img{
    transform:scale(1.1);
}

.activity a:hover{
    color:red;
}
/* text */
.title{
    color:red;
    font-size:26px;
    font-weight:bold;
}
.date{
    color:blue;
    font-weight:bold;
}
.text{
    margin-top:10px;
    line-height:1.25;
    color:#c0392b;
    font-weight:bold;
}
/* ảnh */
.im{
    display:flex;
    gap:10px;
    margin-top:15px;
}
.im a{
    width:50%;
}
.im img{
    width:100%;
    height:220px;
    object-fit:cover;
    border-radius:8px;
    transition:0.3s;
}
.im img:hover{
    transform:scale(1.05);
    box-shadow:0 0 10px red;
}
/* video */
.video{
    text-align:center;
    margin-top:20px;
}
/* footer */
.t{
    margin-top:20px;
    text-align:center;
    color:#c0392b;
    font-weight:bold;
    line-height: 0.75;
}
/* gạch chân h4 */
.sidebar h4{
    border-bottom:4px solid black;
    padding-bottom:3px;
    margin-top:10px;
    display:inline-block;
}
</style>
</head>
<body>
<!-- banner -->
<div class="banner">
<img src="https://i.postimg.cc/DyyxVD83/z7631297192152-0b39019d485261de1b29e7f27c2b86ef.jpg">
</div>
<!-- chữ chạy -->
<div class="marquee">
<p>CHÀO MỪNG NGÀY THÀNH LẬP ĐOÀN TNCS HỒ CHÍ MINH 26/03</p>
</div>
<div class="wrapper">
<!-- BOX TRÁI -->
<div class="sidebar tv">
<div class="text">
    <h3>THÀNH VIÊN NHÓM</h3>
    <h4>Người làm Web :</h4><br>
    - Phạm Đức Phong<br>
    <h4>Người Hỗ Trợ Làm Web :</h4><br>
    - Bùi Thị Duyên<br>
    - Hoàng Ngọc Anh Khôi<br>
    <h4>Người Làm Nội Dung :</h4><br>
    - Mặc văn Cương<br>
    - Phạm Thùy Liên<br>
    - Hoàng Khánh Ngân<br>
    - Nguyễn Thị Thảo Vi<br> 
</div>
</div>
<!-- NỘI DUNG -->
<div class="container">
    <div class="header">
        <div class="left">
            <img src="https://cdn.thuvienphapluat.vn/phap-luat/2022-2/QB/180324/DOAN-TNCS.jpg">
            <img src="https://images2.thanhnien.vn/thumb_w/640/528068263637045248/2025/4/27/anh-1-1745757317683461590713.jpg">
        </div>
        <div class="right">
            <div class="title">
                KỶ NIỆM 95 NĂM<br>
                ĐOÀN TNCS HỒ CHÍ MINH
            </div>
            <div class="date">(26/3/1931 - 26/3/2026)</div>
            <div class="text">
Ngày 26/3 hằng năm là dịp để tuổi trẻ Việt Nam cùng nhau ôn lại truyền thống vẻ vang của Đoàn Thanh niên Cộng sản Hồ Chí Minh – tổ chức được thành lập vào ngày 26/3/1931. Đây là nơi tập hợp, giáo dục và định hướng lý tưởng cho thế hệ thanh niên Việt Nam.
            </div>
            <div class="text">
                    Trong suốt chặng đường lịch sử của dân tộc, thanh niên luôn là lực lượng xung kích trong học tập, lao động và bảo vệ Tổ quốc. Biết bao thế hệ đoàn viên đã cống hiến sức trẻ, lòng nhiệt huyết để góp phần xây dựng và phát triển đất nước.

Ngày nay, thanh niên tiếp tục phát huy tinh thần năng động, sáng tạo thông qua nhiều phong trào ý nghĩa như học tập tốt, tham gia hoạt động tình nguyện và rèn luyện bản thân. Những hoạt 
động đó giúp tuổi trẻ trưởng thành và đóng góp tích cực cho xã hội.
            </div>
        </div>
    </div>
    <hr>
    <p style="text-align:center;color:red; font-weight: bold;">▶ Video tư liệu lịch sử</p>
    <div class="video">
        <iframe width="700" height="400"
        src="https://www.youtube.com/embed/Kui4Tt7lbE0"
        frameborder="0" allowfullscreen></iframe>
    </div>
    <div class="t" style="text-align: left;">
        <p>THPT Ea Súp</p>
        <p>Chi đoàn 12A1 - Nhóm 1</p>
        <p>Người làm: Đức Phong</p>
    </div>
</div>
<!-- BOX PHẢI -->
<div class="sidebar hd">
    <h3>HOẠT ĐỘNG</h3>
    <div class="activity">
        <p> ⚽thể thao</p>
        <a href="https://c3easup.daklak.edu.vn/truong-thpt-ea-sup-tung-bung-to-chuc-cac-hoat-dong-ky-niem-92-nam-ngay-thanh-lap-doan-tncshcm-26031931-26032023.html" target="_blank">
            <img src="http://c3easup.daklak.edu.vn/wp-content/uploads/z4213912239140_0b0ed7bf3d3c1834dcecdd1fc1f0db11.jpg">
        </a>
                <a href="https://c3easup.daklak.edu.vn/truong-thpt-ea-sup-tung-bung-to-chuc-cac-hoat-dong-ky-niem-92-nam-ngay-thanh-lap-doan-tncshcm-26031931-26032023.html" target="_blank">
            <img src="http://c3easup.daklak.edu.vn/wp-content/uploads/z4213912273750_a0c32f191f5fa6a26a00c24c1a01188b.jpg">
        </a>
    </div>
    <div class="activity">
        <p>🎤văn nghệ</p>
        <a href="https://c3easup.daklak.edu.vn/truong-thpt-ea-sup-tung-bung-to-chuc-cac-hoat-dong-ky-niem-92-nam-ngay-thanh-lap-doan-tncshcm-26031931-26032023.html" target="_blank">
            <img src="http://c3easup.daklak.edu.vn/wp-content/uploads/z4213912215904_465438fa0e71188596b003c2c2e11a8f.jpg">
        </a>
                <a href="https://c3easup.daklak.edu.vn/truong-thpt-ea-sup-tung-bung-to-chuc-cac-hoat-dong-ky-niem-92-nam-ngay-thanh-lap-doan-tncshcm-26031931-26032023.html" target="_blank">
            <img src="http://c3easup.daklak.edu.vn/wp-content/uploads/z4214025635279_ce787a7973838abfae831765eaf95c90.jpg">
        </a>
    </div>  
    <hr>
    <h3>KẾT QUẢ</h3>
    <p>✔ Gắn kết thanh niên</p>
    <p>✔ Phát triển kỹ năng</p>
    <p>✔ Lan tỏa tinh thần tích cực</p>
</div>
</div>
