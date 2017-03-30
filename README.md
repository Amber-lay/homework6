<html>
<head>
<meta charset="utf-8">
<title>网传小官网</title>
<link rel="stylesheet" type="text/css" href="style.css" />
<link rel="stylesheet" type="text/css" href="swiper-3.4.0.min.css" />
</head>
<body>
<div class="content">
   <div class="header">
     <img src="logo.png">
        <div class="quickLink">
            <a href="#">教师进入</a>
            <a href="#">教师进入</a>
            <a href="#">教师进入</a>
        </div>
   </div>
</div>
<div class="nav">
   <nav>
      <ul>
         <a href="#"><li>首页</li> </a>
         <a href="#"><li>首页</li> </a> 
         <a href="#"><li>首页</li> </a>
         <a href="#"><li>首页</li> </a>
         <a href="#"><li>首页</li> </a>
         <a href="#"><li>首页</li> </a>
         <a href="#"><li>首页</li> </a>
         <a href="#"><li>首页</li> </a>
      </ul>
   </nav>
</div>
<div class="swiper-container">
    <div class="swiper-wrapper">
        <div class=" banner swiper-slide"><img src="banner1.jpg"></div>
        <div class=" banner swiper-slide"><img src="banner2.jpg"></div>
        <div class="swiper-slide">Slide 3</div>
    </div>
       <div class="swiper-button-prev"></div>
       <div class="swiper-button-next"></div>
</div>
</body>

<script src="jquery-3.1.1.min.js"></script>
<script src="swiper.jquery.min.js"></script>
<script>
    var mySlide = new Swiper ('.swiper-container', {
    loop: true,
    nextButton: '.swiper-button-next',
    prevButton: '.swiper-button-prev',
  })        
    var width = $(document).width();
    var height = width *300/2000;
    $('.swiper-container').css('height',height+'px');
</script>
</html>
