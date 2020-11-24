<html>
<head>
<title>초대합니다</title>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0, user-scalable=yes" />

<meta property="og:site_name" content="babyparty" />
<meta property="og:title" content="임직 예식에 초대합니다." />
<meta property="og:description" content="2020년 11월 29일 오후 3시, 해오름교회에서 임직 예식을 시작합니다." />
<meta property="og:image" content="https://user-images.githubusercontent.com/74969995/100102219-a3a6d280-2ea6-11eb-9a7f-2fe7896c2c23.png" />
<meta property="og:image" content="https://user-images.githubusercontent.com/74969995/100105635-f1253e80-2eaa-11eb-877c-0c84fb8dddc5.png" />
<meta property="og:type" content="website" />
<meta property="og:url" content="haeorum.github.io" />

<link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/jquery.slick/1.5.9/slick.css"/>
<style>
* {
	margin: 0;
	padding: 0;
	-webkit-tap-highlight-color: rgba(0, 0, 0, 0);
	-moz-tap-highlight-color: rgba(0, 0, 0, 0);
	-webkit-text-size-adjust: 100%;
}

html,body {
	height: 100%;
}

body {
	background-color: #eee;
}

#wrap {
	max-width: 500px;
	margin: 0 auto;
	background-color: #fff;
	height: auto;
}

.img100 {
	max-width: 100%;
	width: auto !important;
	width: 100%;
}

#autoplay, .slide_wrap {
	position:relative;
	width:100%;
	overflow:hidden;
}

.content_wrap {
	font-size: 14px;
	text-align: center;
	padding-top: 15px;
	margin: 0 15px;
	color: #8d968c;
	line-height: 20px;
}

.content_wrap h1 {
	font-size: 15px;
	font-weight: bold;
	text-align: center;
	padding-bottom: 15px;
	color: #50a27f;
}

.content_wrap h1 img {
	height: 40px;
	vertical-align: middle;
}

.contact_wrap {
	text-align: center;
	padding-top: 15px;
}

.contact_wrap a {
	font-size: 15px;
	color: #2f302c;
	font-weight: bold;
	text-decoration: none;
	display: inline-block;
	padding: 10px;
	min-width: 40px;
	border-radius: 5px;
}

.contact_wrap a.bg1 {
	background-color: #bbedc8;
}

.contact_wrap a.bg2 {
	background-color: #9bddbe;
}

.contact_wrap a.bg3 {
	background-color: #ccf2cb;
}

.contact_wrap img {
	height: 15px;
	padding-right: 5px;
	vertical-align: middle;
	position: relative;
	top: -2px;
}

.date_wrap {
	margin: 0 15px;
	padding: 20px 0 0 0;
	text-align: left;
	font-size: 13px;
}

.date_wrap img {
	height: 15px;
	vertical-align: middle;
	position: relative;
	top: -2px;
	padding-right: 5px;
}

.addr_wrap {
	margin: 0 15px;
	padding: 10px 0;
	text-align: left;
	font-size: 13px;
}

.addr_wrap img {
	height: 15px;
	vertical-align: middle;
	position: relative;
	top: -2px;
	padding-right: 5px;
}

.map_wrap {
	margin: 0 15px;
	height: 200px;
	background-color: #ddd;
	text-align: center;
	font-size: 14px;
}

.tras_wrap {
	margin: 0 15px;
	font-size: 14px;
	padding-bottom: 20px;
}

.tras_wrap div {
	padding-top: 10px;
}

.tras_wrap div.what {
	color: #888;
}

.tras_wrap div.is {
	color: #8d968c;
	font-weight: bold;
	margin: 0 20px;
}

.tras_wrap img {
	height: 14px;
	vertical-align: middle;
	position: relative;
	top: -3px;
	padding-right: 5px;
}
.copy {
	font-size:12px;
	color:#888;
	text-align:center;
	padding-top:15px;
	padding-bottom:15px;
}
.slick-prev,.slick-next {
	display:none !important;
}
</style>
</head>
<body>
	<div id="wrap">
		<div class="slide_wrap">
			<div id="autoplay" style="display:none;">
				<!-- //이미지 추가 -->
				<img src="https://user-images.githubusercontent.com/74969995/100102219-a3a6d280-2ea6-11eb-9a7f-2fe7896c2c23.png" class="img100" />
			</div>
		</div>
		
		<div class="contact_wrap">
			<a href="tel:055-384-0691" class="bg1"><img src="https://cdn4.iconfinder.com/data/icons/miu/24/device-iPhone-smartphone-vertical-glyph-128.png" alt="tel">교회전화</a>
		</div>
		<div class="date_wrap">
			<span><img src="https://cdn2.iconfinder.com/data/icons/office-38/24/office-40-128.png" alt="time" />날짜 : <strong>2020년 11월 29일 오후 3시</strong></span>
		</div>
		<div class="addr_wrap">
			<span><img src="https://cdn4.iconfinder.com/data/icons/miu/24/house-home-real_estate-property-glyph-128.png" alt="place" />장소 : <strong>해오름교회</strong> | 경남 양산시 중앙로 206, 덕산빌딩 6층</span>
		</div>
		<div class="map_wrap" id="map"></div>
		
	</div>
	<div id="wrap">
		<div class="slide_wrap">
			<div id="autoplay" style="display:none;">
				<!-- //이미지 추가 -->
				<img src="https://user-images.githubusercontent.com/74969995/100105635-f1253e80-2eaa-11eb-877c-0c84fb8dddc5.png" class="img100" />
			</div>
		</div>
	</div>
	
	
	<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/1.12.0/jquery.min.js"></script>
	<script src="https://maps.googleapis.com/maps/api/js?signed_in=true"></script>
	<script src="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.5.9/slick.min.js"></script>
	<script>
	var latlng = "35.348894, 129.040507"; //구글맵에서 위치 검색 후, 맵을 클릭하면 나오는 하단의 좌표를 입력한다.

	function initMap() {
		if (latlng.length <= 0)
			return false;
		arr = latlng.split(",");
		if (arr.length <= 1)
			return false;

		var myLatLng = {
			lat : parseFloat($.trim(arr[0])),
			lng : parseFloat($.trim(arr[1]))
		};
		var map = new google.maps.Map(document.getElementById('map'), {
			zoom : 17,
			center : myLatLng
		});
		var arr = [];

		new google.maps.Marker({
			position : myLatLng,
			map : map
		});
	}
	$(function(e) {
		initMap();
		
		var targetEle = $("#autoplay");
		targetEle.find("img").css("cssText" , "width:" + targetEle.width() + "px !important;");
		targetEle.slick({
			slidesToShow : 1,
			slidesToScroll : 1,
			autoplay : true,
			autoplaySpeed : 2000,
			dots: false,
		  	infinite: true,
		  	variableWidth: true
		});
		targetEle.css({"display" : "block"});
		var tmpHeight = 0;
		targetEle.find("img").each(function(k, v) {
			var _this = $(this);
			if( tmpHeight == 0 || tmpHeight > _this.height() ) {
				tmpHeight = _this.height();
			}
		});
		$(".slide_wrap").height(tmpHeight);
	});
	
	</script>
</body>
</html>
