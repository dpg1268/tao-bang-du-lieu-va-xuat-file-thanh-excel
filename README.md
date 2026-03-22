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
    max-width:1700px;
}
/* box chung */
.sidebar{
    width:450px;
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
    max-width:700px;
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
.tv{
    flex:0 0 260px;
}
    .hd{
    flex:0 0 320px;
}
.left{
      position: relative;
    width:40%;
     top:115px;
    left:5px;
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
<div class="text" style="width: 200px;">
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
            <img src="https://s.yimg.com/zb/imgv1/8b3c733b-4f67-3258-9d7b-1547f274efba/t_500x300">
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
            </div>
        </div>
    </div>
    <hr>
    <p style="text-align:center;color:red; font-weight: bold;">▶ Video tư liệu lịch sử</p>
    <div class="video">
        <iframe width="600" height="350"
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
<div class="sidebar hd" style="width :525px;">
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
      <div class="activity" style="display: block;">
            <p>📚 Hoạt Động Chào Mừng Ngày 26/3</p>
                   <iframe src="https://www.facebook.com/plugins/post.php?href=https%3A%2F%2Fwww.facebook.com%2Fpermalink.php%3Fstory_fbid%3Dpfbid02WamieWgfzjjeYUC8wEgQ7sggV9Q2n2W56RLxnpVPXZBCuNNXC6XWhn6xFakQEiEsl%26id%3D100068895586741&show_text=true&width=500" width="500" height="700" style="border:none;overflow:hidden" scrolling="yes" frameborder="0" allowfullscreen="true" allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share"></iframe>
    </div>
    <hr>
    <h3>KẾT QUẢ</h3>
    <p style="font-weight:bold;">- Ngày 26/03 hằng năm là dịp để thanh niên cả nước ôn lại truyền thống vẻ vang của Đoàn Thanh niên Cộng sản Hồ Chí Minh. Thông qua các hoạt động kỷ niệm, phong trào thanh niên ngày càng phát triển mạnh mẽ và thu hút nhiều đoàn viên tham gia.</p>
</div>
</div>
