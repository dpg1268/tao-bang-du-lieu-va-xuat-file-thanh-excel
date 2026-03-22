<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Kỷ niệm 26/3</title>

<style>
body{
    margin:0;
    background:#f6e27a;
}

/* layout 3 cột */
.main-layout{
    display:flex;
    justify-content:center;
    align-items:flex-start;
    gap:20px;
    margin:40px;
}

/* container giữa */
.container{
    max-width:900px;
    width:100%;
    padding:40px;
    border:4px solid red;
    border-radius:10px;
    background:#fff8c6;
    box-shadow:0 0 15px rgba(0,0,0,0.2);
}

/* sidebar trái phải */
.sidebar{
    width:220px;
    border:3px solid red;
    border-radius:10px;
    background:#fff8c6;
    padding:15px;
    box-shadow:0 0 10px rgba(0,0,0,0.3);
    height:fit-content;
}

.sidebar h3{
    text-align:center;
    color:red;
}

.sidebar p{
    font-size:16px;
    margin:8px 0;
}

/* banner */
.banner img{
    width:100%;
}

/* chữ chạy */
.marquee{
    width:100%;
    overflow:hidden;
    background:#f6e27a;
}

.marquee p{
    display:inline-block;
    white-space:nowrap;
    animation:chaychu 12s linear infinite;
    font-size:18px;
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
    margin-top:20px;
}

.left{
    width:40%;
}

.left img{
    width:100%;
}

.right{
    width:60%;
    text-align:center;
}

/* tiêu đề */
.title{
    color:red;
    font-size:28px;
    font-weight:bold;
}

.date{
    color:blue;
    font-size:20px;
    margin-top:5px;
    font-weight:bold;
}

@import url('https://fonts.googleapis.com/css2?family=Dancing+Script:wght@700&display=swap');

.text, .l{
    margin-top:15px;
    font-size:18px;
    color:#c0392b;
    line-height:1.6;
    font-weight:bold;
    font-family: 'Dancing Script', cursive;
    text-align:center;
}

/* ảnh */
.im{
    display:flex;
    gap:10px;
    margin-top:20px;
}

.im img{
    width:50%;
}
.im img{
    width:400px;
    height:300px;
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
    text-align:center;
    margin-top:20px;
    font-size:18px;
    color:#c0392b;
    font-weight:bold;
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

<!-- layout chính -->
<div class="main-layout">
    <!-- BOX TRÁI -->
    <div class="sidebar">
        <h3>LỊCH SỬ</h3>
        <p>📅 26/03/1931</p>
        <p>📌 Thành lập Đoàn TNCS Hồ Chí Minh</p>
        <p>🔥 Thanh niên là lực lượng tiên phong</p>
    </div>
    <!-- NỘI DUNG GIỮA -->
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
                <div class="date">
                    (26/3/1931 - 26/3/2026)
                </div>
                <div class="text">
Ngày 26/3 hằng năm là dịp để tuổi trẻ Việt Nam cùng nhau ôn lại truyền thống vẻ vang của Đoàn Thanh niên Cộng sản Hồ Chí Minh – tổ chức được thành lập vào ngày 26/3/1931. Đây là nơi tập hợp, giáo dục và định hướng lý tưởng cho thế hệ thanh niên Việt Nam.
                </div>
                <div class="l">
    Trong suốt chặng đường lịch sử của dân tộc, thanh niên luôn là lực lượng xung kích trong học tập, lao động và bảo vệ Tổ quốc. Biết bao thế hệ đoàn viên đã cống hiến sức trẻ, lòng nhiệt huyết để góp phần xây dựng và phát triển đất nước.

Ngày nay, thanh niên tiếp tục phát huy tinh thần năng động, sáng tạo thông qua nhiều phong trào ý nghĩa như học tập tốt, tham gia hoạt động tình nguyện và rèn luyện bản thân. Những hoạt động đó giúp tuổi trẻ trưởng thành và đóng góp tích cực cho xã hội.
                </div>
            </div>
        </div>
        <hr>
        <h2 style="text-align:center; color:red;">HÌNH ẢNH TIÊU BIỂU</h2>
        <div class="im">
           <a href="https://c3easup.daklak.edu.vn/truong-thpt-ea-sup-tung-bung-to-chuc-cac-hoat-dong-ky-niem-92-nam-ngay-thanh-lap-doan-tncshcm-26031931-26032023.html" target="_blank">
            <img src="http://c3easup.daklak.edu.vn/wp-content/uploads/z4213912239140_0b0ed7bf3d3c1834dcecdd1fc1f0db11.jpg"></a>
           <a href="https://c3easup.daklak.edu.vn/truong-thpt-ea-sup-tung-bung-to-chuc-cac-hoat-dong-ky-niem-92-nam-ngay-thanh-lap-doan-tncshcm-26031931-26032023.html" target="_blank">
            <img src="http://c3easup.daklak.edu.vn/wp-content/uploads/z4213912215904_465438fa0e71188596b003c2c2e11a8f.jpg">
            </a>
        </div>
        <hr>
        <p style="text-align:center; color:red;">▶ Video kỷ niệm</p>
        <div class="video">
            <iframe width="700" height="400"
            src="https://www.youtube.com/embed/Kui4Tt7lbE0"
            frameborder="0"
            allowfullscreen>
            </iframe>
        </div>
        <div class="t">
            <p>THPT Ea Súp</p>
            <p>Chi đoàn 12A1</p>
            <p>Nhóm 1</p>
            <p>Người làm: Đức Phong</p>
        </div>
    </div>
    <!-- BOX PHẢI -->
    <div class="sidebar">
        <h3>HOẠT ĐỘNG</h3>
        <p>🎤 Văn nghệ</p>
        <p>⚽ Thể thao</p>
        <p>📚 Sinh hoạt đoàn</p>
        <p>💡 Tình nguyện</p>
        <p>🚀 Phát triển kỹ năng</p>
    </div>

<div class="t">
    <p>THPT Ea Súp</p>
    <p>Chi đoàn 12A1</p>
    <p>Nhóm 1</p>
    <p>Người làm: Đức Phong</p>
</div>

</body>
</html>
