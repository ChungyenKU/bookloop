<html>

<head>
    <meta charset="big5"></meta>
    <title>新書資訊網</title>
    <style type="text/css">
    .head {
        background-color: #003344;
        color: white;
        font-weight: bold;
        font-size: 30px;
        text-align: center;
        padding: 10px;
        position: fixed;
        left: 0;
        right: 0;
        z-index: 999;
    }
    
    .content {
        width: 1200px;
        margin-left: auto;
        margin-right: auto;
    }
    
    .tagcontent {
        width: 150px;
        margin-left: 0cm;
        margin-right: auto;
        text-align: left;
        font-size: 24px;
        font-family: 微軟正黑體;
    }
    
    .tagcontent-menu {
        width: 200px;
        margin-left: 0cm;
        margin-right: auto;
        text-align: left;
        font-size: 24px;
        font-family: 微軟正黑體;
        left: 0;
        top: 56.4;
        position: fixed;
        z-index: 10;
    }
    
    .box {
        width: 650px;
        padding: 10px;
        margin: 10px;
        background-color: #eeeeee;
        display: inline-block;
        vertical-align: top;
        text-align: center;
        height: 650px;
        line-height: 30px;
        position: relative;
        top: 60;
        right: -70;
    }
    .bookbox {
        font-family: 微軟正黑體;
    }
    
    .rightbox {
        width: 400px;
        padding: 10px;
        margin: 10px;
        background-color: #eeeeee;
        display: inline-block;
        vertical-align: top;
        text-align: center;
        height: 400px;
        line-height: 30px;
        position: relative;
        top: 60;
    }
    .searchbox {
        width: 300px;
        padding: 10px;
        margin: 10px;
        background-color: #eeeeee;
        font-family: 微軟正黑體;
        display: inline-block;
        vertical-align: top;
        text-align: center;
        height: 120px;
        line-height: 30px;
        position: relative;
        top: 30;
    }
    .inforbox {
        width: 300px;
        padding: 10px;
        margin: 10px;
        background-color: #eeeeee;
        font-family: 微軟正黑體;
        display: inline-block;
        vertical-align: top;
        text-align: center;
        height: 400px;
        line-height: 30px;
        position: relative;
        top: 40;
    }
    
    .widebox {
        width: 400px;
        padding: 10px;
        margin: 10px;
        background-color: #eeeeee;
        display: inline-block;
        vertical-align: top;
        text-align: center;
        height: 400px;
        line-height: 30px;
        position: relative;
    }
    .middlebox {
        width: 400px;
        padding: 10px;
        margin: 10px;
        background-color: #eeeeee;
        display: inline-block;
        vertical-align: top;
        text-align: center;
        height: 510px;
        line-height: 30px;
        position: relative;
        top: 60;
    }
    .doyouknowbox {
        width: 400px;
        padding: 10px;
        margin: 10px;
        background-color: #eeeeee;
        font-family: 微軟正黑體;
        display: inline-block;
        vertical-align: top;
        text-align: left;
        height: 400px;
        line-height: 30px;
        position: relative;
        top: -50;
        right:-40;
    }
    
    .tagbox {
        width: 250px;
        padding: 10px;
        margin: 10px;
        background-color: #eeeeee;
        display: inline-block;
        vertical-align: top;
        text-align: center;
        height: 400px;
        line-height: 30px;
        position: relative;
        top: 60;
    }
    
    .newsbox {
        width: 400px;
        padding: 0px;
        background-color: #eeeeee;
        display: inline-block;
        vertical-align: top;
        margin-top: 5px;
        margin-bottom: 5px;
        text-align: center;
        height: 50px;
        line-height: 30px;
        top: 60;
    }
    
    .news_smallbox {
        width: 80px;
        padding: 10px;
        background-color: #003344;
        font-family: 微軟正黑體;
        display: inline-block;
        vertical-align: top;
        margin-top: 5px;
        margin-right: 5px;
        margin-bottom: 0px;
        text-align: center;
        height: 30px;
        line-height: 17px;
        top: 60;
    }
    
    .news_widebox {
        width: 250px;
        padding: 10px;
        background-color: #eeeeee;
        font-family: 微軟正黑體;
        display: inline-block;
        vertical-align: top;
        margin-top: 0px;
        margin-right: 10px;
        margin-bottom: 0px;
        text-align: left;
        height: 30px;
        line-height: 20px;
        top: 60;
    }
    
    title {
        display: block;
        font-size: 20;
        background-image: url(http://i.imgur.com/oFjsxQK.png);
	height: 50px;
	width: 272px;
    }
    
    <!--標籤CSS--> .vertical-menu {
        width: 400px;
        /* Set a width if you like */
    }
    
    .vertical-menu a {
        background-color: #eee;
        /* Grey background color */
        color: black;
        /* Black text color */
        display: block;
        /* Make the links appear below each other */
        padding: 12px;
        /* Add some padding */
        text-decoration: none;
        /* Remove underline from links */
    }
    
    .vertical-menu a:hover {
        background-color: #ccc;
        /* Dark grey background on mouse-over */
    }
    
    .vertical-menu a.active {
        background-color: #4CAF50;
        /* Add a green color to the "active/current" link */
        color: white;
    }
    
    <!--uptnCSS--> .dropbtn {
        background-color: #4CAF50;
        color: white;
        padding: 16px;
        font-size: 16px;
        border: none;
        cursor: pointer;
    }
    
    .dropdown {
        position: relative;
        display: inline-block;
    }
    
    .dropdown-content {
        display: none;
        position: absolute;
        background-color: #f9f9f9;
        min-width: 160px;
        box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0.2);
        z-index: 1;
    }
    
    .dropdown-content a {
        color: black;
        padding: 12px 16px;
        text-decoration: none;
        display: block;
    }
    
    .dropdown-content a:hover {
        background-color: #f1f1f1
    }
    
    .dropdown:hover .dropdown-content {
        display: block;
    }
    
    .dropdown:hover .dropbtn {
        background-color: #3e8e41;
    }
    
    <!--SLIDESHOW CSS--> * {
        box-sizing: border-box
    }
    /* Slideshow container */
    
    .slideshow-container {
        max-width: 1000px;
        position: relative;
        margin: auto;
    }
    
    .mySlides {
        display: none;
    }
    /* Next & previous buttons */
    
    .prev {
        cursor: pointer;
        position: relative;
        top: 50%;
        right: 20%;
        width: auto;
        margin: 0px auto;
        margin-left: -22px;
        padding: 16px;
        color: white;
        font-weight: bold;
        font-size: 18px;
        transition: 0.6s ease;
        border-radius: 0 3px 3px 0;
    }
    
    .next {
        cursor: pointer;
        position: relative;
        top: 50%;
        left: 20%;
        width: auto;
        margin: 0px auto;
        margin-right: -22px;
        padding: 16px;
        color: white;
        font-weight: bold;
        font-size: 18px;
        transition: 0.6s ease;
        border-radius: 0 3px 3px 0;
    }
    /* Position the "next button" to the right */
    
    .next {
        right: 0;
        border-radius: 3px 0 0 3px;
    }
    /* On hover, add a black background color with a little bit see-through */
    
    .prev:hover,
    .next:hover {
        background-color: rgba(0, 0, 0, 0.8);
    }
    /* Caption text */
    
    .text {
        color: #f2f2f2;
        font-size: 15px;
        padding: 8px 12px;
        position: absolute;
        bottom: 8px;
        width: 100%;
        text-align: center;
    }
    /* Number text (1/3 etc) */
    
    .numbertext {
        color: #f2f2f2;
        font-size: 12px;
        padding: 8px 12px;
        position: absolute;
        top: 0;
    }
    /* The dots/bullets/indicators */
    
    .dot {
        cursor: pointer;
        height: 13px;
        width: 13px;
        margin: 0 2px;
        background-color: #bbb;
        border-radius: 50%;
        display: inline-block;
        transition: background-color 0.6s ease;
    }
    
    .active,
    .dot:hover {
        background-color: #717171;
    }
    /* Fading animation */
    
    .fade {
        -webkit-animation-name: fade;
        -webkit-animation-duration: 1.5s;
        animation-name: fade;
        animation-duration: 1.5s;
    }
    
    @-webkit-keyframes fade {
        from {
            opacity: .4
        }
        to {
            opacity: 1
        }
    }
    
    @keyframes fade {
        from {
            opacity: .4
        }
        to {
            opacity: 1
        }
    }
    </style>
</head>
<script>
var slideIndex = 1;
showSlides(slideIndex);

function plusSlides(n) {
    showSlides(slideIndex += n);
}

function currentSlide(n) {
    showSlides(slideIndex = n);
}

function showSlides(n) {
    var i;
    var slides = document.getElementsByClassName("mySlides");
    var dots = document.getElementsByClassName("dot");
    if (n > slides.length) {
        slideIndex = 1
    }
    if (n < 1) {
        slideIndex = slides.length
    }
    for (i = 0; i < slides.length; i++) {
        slides[i].style.display = "none";
    }
    for (i = 0; i < dots.length; i++) {
        dots[i].className = dots[i].className.replace(" active", "");
    }
    slides[slideIndex - 1].style.display = "block";
    dots[slideIndex - 1].className += " active";
}
/*Keep changing img*/
function changeImg() {
    showSlides(slideIndex += 1);
    setTimeout('changeImg()', 5000);
}
</script>

<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
<script>


$(document).ready(function() {
    $("#a1").hide();
    	$("#q1").click(function(){
      	$("#a1").fadeIn("fast");;
    	});
     $("#a2").hide();
    	$("#q2").click(function(){
      	$("#a2").fadeIn("fast");;
    	});
     $("#a3").hide();
    	$("#q3").click(function(){
      	$("#a3").fadeIn("fast");;
    });
     $("#a4").hide();
    	$("#q4").click(function(){
      	$("#a4").fadeIn("fast");;
    });
     $("#a5").hide();
    	$("#q5").click(function(){
      	$("#a5").fadeIn("fast");;
    });
    });
</script>


<body style="margin:0px;background-color:#eeeeee;" onload="currentSlide(1),setTimeout('changeImg()', 5000)">
    <div class="head">新書資訊網</div>
    <!--旁標籤-->
    <div class="content">
        <div class="tagbox">
            <div class="tagcontent-menu">
                <div class="vertical-menu">
                    <a href="#" class="active">網路書店</a>
                    <a href="http://www.books.com.tw/">博客來</a>
                    <a href="https://www.kadokawa.com.tw/">台灣角川</a>
                    <a href="http://www.kingstone.com.tw/about/about_102.asp">金石堂</a>
                    <a href="https://www.tenlong.com.tw/?gclid=CNiY8qPXitQCFRIEKgodtnsBsQ">天瓏</a>
                </div>
            </div>
        </div>
        <div class="middlebox">
         <div class="bookbox">
			<img src="https://www.kadokawa.com.tw/Upload/product_201704271639341.jpg" width="80px" height="100px" style="margin-top: 5px;margin-left: 10px;"align="left"></img>
			<div align="right" style="margin-top: 5px;font-family:微軟正黑體;font-size:5px;color:red;">台灣角川</div>
			<div align="left"  style="margin-top: 15px";><a href="https://www.kadokawa.com.tw/p1-products_detail.php?id=8ab9LkRLpIQXTPQaPX5JCCzDeWXAAdIMRcBn0UqBN9Tb" style="color:#348F33; text-decoration:none;">Taipei Walker 241期</a></div>
			<div align="right" style="margin-top: 5px;font-family:微軟正黑體;font-size:5px;color:blue;">Taipei Walker編輯部</div>
			
		</div>
		<div class="bookbox">
			<img src="https://www.kadokawa.com.tw/Upload/product_201705251645151.jpg" width="80px" height="100px" style="margin-top: 5px;margin-left: 10px;"align="left"></img>
			<div align="right" style="margin-top: 5px;font-family:微軟正黑體;font-size:5px;color:red;">台灣角川</div>

			<div align="left"  style="margin-top: 15px";><a href="https://www.kadokawa.com.tw/p1-products_detail.php?id=54dfROcNQ5DmFrBS9i6YUVtJQI6uWv6uW-QQeYQnozgw" style="color:#348F33; text-decoration:none;">Taipei Walker 242期</a></div>
			<div align="right" style="margin-top: 5px;font-family:微軟正黑體;font-size:5px;color:blue;">Taipei Walker編輯部</div>
			
		</div>
		<div class="bookbox">
			
			<img src="http://im1.book.com.tw/image/getImage?i=http://www.books.com.tw/img/CN1/142/75/CN11427514.jpg&v=590181da&w=348&h=348" width="80px" height="100px" style="margin-top: 5px;margin-left:10px;"align="left"></img>
			<div align="right" style="margin-top: 5px;font-family:微軟正黑體;font-size:5px;color:red;">博客來</div>
			<div align="left" style="margin-top: 15px";><a href="http://www.books.com.tw/products/CN11427514" style="color:#348F33; text-decoration:none;">生物與非生物之間</a></div>
			<div align="right" style="margin-top: 5px;font-family:微軟正黑體;font-size:5px;color:blue;">福岡伸一</div>
		
		</div>
		<div class="bookbox">

			<img src="http://im2.book.com.tw/image/getImage?i=http://www.books.com.tw/img/CN1/136/82/CN11368211.jpg&v=57d38c4b&w=348&h=348
		" width="80px" height="100px" style="margin-top: 5px;margin-left: 10px;"align="left"></img>
			<div align="right" style="margin-top: 5px;font-family:微軟正黑體;font-size:5px;color:red;">博客來</div>
			<div align="left" style="margin-top: 15px";><a href="http://www.books.com.tw/products/CN11368211?loc=P_asb_001" style="color:#348F33; text-decoration:none;">星空帝國：中國古代星宿揭秘</a></div>
			<div align="right" style="margin-top: 5px;font-family:微軟正黑體;font-size:5px;color:blue;">徐剛等</div>
		</div>
		<div class="bookbox">

			<img src="http://im1.book.com.tw/image/getImage?i=http://www.books.com.tw/img/F01/390/60/F013906030.jpg&v=5913a2bd&w=348&h=348" width="80px" height="100px" style="margin-top: 5px;margin-left: 10px;"align="left"></img>
			<div align="right" style="margin-top: 5px;font-family:微軟正黑體;font-size:5px;color:red;">博客來</div>
			<div align="left" style="margin-top: 15px";><a href="http://www.books.com.tw/products/F013906030?loc=P_005_011" style="color:#348F33; text-decoration:none;">The Fog</a></div>
			<div align="right" style="margin-top: 5px;font-family:微軟正黑體;font-size:5px;color:blue;">MacLear, Kyo/ Pak, Kenard (ILT)</div>
		</div>
        </div>
        <div class="rightbox">
          <div class="searchbox">
            <title style="color:#003344;">書籍搜尋</title>
            <form action="test.php" method="post">
                書名：
                <input type="text" name="BookName">
                <br>書商：
                <select name="BookStore">
                
                    <option value="books">博客來</option>
                
                    <option value="kadokawa">台灣角川</option>
                
                    <option value="kingstone">金石堂</option>
                
                    <option value="tenlong">天瓏</option>
                </select>
                <br>
                <input type="submit" value="查詢">
            </form>
          </div>
            <div class="inforbox">
            <title style="color:#003344;">書展資訊</title>
            <div class="newsbox">
                <div class="news_smallbox">
                    <div style="font-size:20px;color:white;">2017</div>
                    <div style="font-size:20px;color:white;">Jul, 6</div>
                </div>
                <div class="news_widebox">
                    <div style="font-size:20px;color:white;"><a href="http://www.ntl.edu.tw/ct.asp?xItem=61996&ctNode=1676&mp=1" style="color:#348F33; text-decoration:none;">「慕山手札」青少年主題書展</a></div>
                </div>
            </div>
            <div class="newsbox">
                <div class="news_smallbox">
                    <div style="font-size:20px;color:white;">2017</div>
                    <div style="font-size:20px;color:white;">Jul, 6</div>
                </div>
                <div class="news_widebox">
                    <div style="font-size:20px;color:white;"><a href="http://www.ntl.edu.tw/ct.asp?xItem=61995&ctNode=1676&mp=1" style="color:#348F33; text-decoration:none;">「戀海日記」主題書展</a></div>
                </div>
            </div>
            <div class="newsbox">
                <div class="news_smallbox">
                    <div style="font-size:20px;color:white;">2017</div>
                    <div style="font-size:20px;color:white;">May, 2</div>
                </div>
                <div class="news_widebox">
                    <div style="font-size:20px;color:white;"><a href="http://www.ntl.edu.tw/ct.asp?xItem=61833&ctNode=1676&mp=1" style="color:#348F33; text-decoration:none;">「上古石板」青少年主題書展</a></div>
                </div>
            </div>
            <div class="newsbox">
                <div class="news_smallbox">
                    <div style="font-size:20px;color:white;">2017</div>
                    <div style="font-size:20px;color:white;">May, 2</div>
                </div>
                <div class="news_widebox">
                    <div style="font-size:20px;color:white;"><a href="http://www.ntl.edu.tw/ct.asp?xItem=61609&ctNode=1676&mp=1" style="color:#348F33; text-decoration:none;">「摒住呼吸!驚賞臺灣國家公園之美」主題書展</a></div>
                </div>
            </div>
            </div>
	    <div class="doyouknowbox">
                <title style="text-align: center; color:#003344;">你知道嗎?</title>
	        <br>

	        <div style="cursor: pointer;" id="q1">你知道在日本文學之中擁有崇高地位的獎項--芥川獎，是為了紀念哪位文豪所設立的獎項嗎?</div>
	        <div style="color:red;" id="a1">芥川龍之介</div>
	        <br>

	        <div style="cursor: pointer;" id="q2">你知道中國史上第一篇長篇諷刺小說，是哪本書呢?</div>
	        <div style="color:red;" id="a2">儒林外史</div>
                <br>
            
	        <div style="cursor: pointer;" id="q3">你知道曾為公共電視台所翻改編，翻拍成連續劇的知名長篇小說--孽子，是出自哪位台灣作家之手呢?</div>
	        <div style="color:red;" id="a3">白先勇</div>

		<div style="cursor: pointer;" id="q4">你知道"小李杜"是指晚唐哪兩位詩人嗎?</div>
	    	<div style="color:red;" id="a4">李商隱、杜牧</div>
            	<br>

	    	<div style="cursor: pointer;" id="q5">你知道2016年的諾貝爾文學獎得主是誰嗎?</div>
	    	<div style="color:red;" id="a5">巴布·狄倫</div>
            	<br>     
	    
                <br>
        </div>
        </div>



        <!--<div class="box">
            <div class="tagcontent">
                <div class="dropdown">
                    <button class="dropbtn">網路書店</button>
                    <div class="dropdown-content">
                        <a href="http://www.books.com.tw/">博客來</a>
                        <a href="https://www.kadokawa.com.tw/">台灣角川</a>
                        <a href="http://www.kingstone.com.tw/about/about_102.asp">金石堂</a>
                        <a href="https://www.tenlong.com.tw/?gclid=CNiY8qPXitQCFRIEKgodtnsBsQ">天瓏</a>
                    </div>
                </div>
            </div>
        </div>-->
	<div class="box">
               

        </div>
    </div>
</body>

</html>
