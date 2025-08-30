# vmf
venusmusicfestival
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>공연 소개 & 예매</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body { font-family: 'Noto Sans KR', sans-serif; }
        .navbar { background-color: #222; }
        .navbar a { color: white !important; }
        section { padding: 80px 20px; }
        h1, h2 { font-weight: 600; }
        .btn-book { background: #ff6b6b; color: white; border-radius: 20px; padding: 10px 20px; }
        .btn-book:hover { background: #ff4d4d; }
        footer { background: #222; color: #aaa; padding: 20px 0; text-align: center; }
    </style>
</head>
<body>

<!-- Navigation -->
<nav class="navbar navbar-expand-lg fixed-top">
    <div class="container">
        <a class="navbar-brand text-white" href="#">공연 홈페이지</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ms-auto">
                <li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
                <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
                <li class="nav-item"><a class="nav-link" href="#schedule">Schedule</a></li>
                <li class="nav-item"><a class="nav-link" href="#booking">Booking</a></li>
                <li class="nav-item"><a class="nav-link" href="#gallery">Gallery</a></li>
                <li class="nav-item"><a class="nav-link" href="#news">News</a></li>
            </ul>
        </div>
    </div>
</nav>

<!-- Home -->
<section id="home" class="text-center bg-light">
    <div class="container">
        <h1>2025 공연 안내</h1>
        <p class="lead">멋진 공연에 여러분을 초대합니다!</p>
    </div>
</section>

<!-- About -->
<section id="about" class="text-center">
    <div class="container">
        <h2>공연 소개</h2>
        <p>공연 스토리, 출연진, 기획 의도 등을 소개합니다.</p>
    </div>
</section>

<!-- Schedule -->
<section id="schedule" class="bg-light text-center">
    <div class="container">
        <h2>공연 일정</h2>
        <p>날짜별 공연 시간표를 여기에 표시합니다.</p>
    </div>
</section>

<!-- Booking -->
<section id="booking" class="text-center">
    <div class="container">
        <h2>예매하기</h2>
        <p>아래 버튼을 클릭해 예매 페이지로 이동하세요.</p>
        <a href="https://booking.naver.com/your-link" target="_blank" class="btn btn-book">예매하기</a>
    </div>
</section>

<!-- Gallery -->
<section id="gallery" class="bg-light text-center">
    <div class="container">
        <h2>갤러리</h2>
        <p>공연 사진과 영상을 모아보세요.</p>
    </div>
</section>

<!-- News -->
<section id="news" class="text-center">
    <div class="container">
        <h2>공지사항</h2>
        <p>공연 관련 소식을 업데이트합니다.</p>
    </div>
</section>

<!-- Footer -->
<footer>
    <p>© 2025 공연 홈페이지. All Rights Reserved.</p>
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
