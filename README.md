# Kako-je-propao-TikTok
<!DOCTYPE html>
<html>
    <head>
        <link rel="stylesheet" href="mystyle.css">
    </head>
    <body>
        <div id="header" class="cf">
            <div class="page-width">
                <h1 id="site-title">
                        <a href="http://html5backgroundvideos.com" target="_blank">
                            <span class="title">BG Stock</span>
                            <span class="subtitle">HTML5 Background Videos</span>
                        </a>
                </h1>
            </div>
        </div>

        <!-- Start video hero -->
        <div class="video-hero jquery-background-video-wrapper demo-video-wrapper">
        <video class="jquery-background-video" autoplay muted loop poster="https://d2ezlykacdqcnj.cloudfront.net/_assets/home-video/beach-waves-loop.jpg">
        <source src="https://d2ezlykacdqcnj.cloudfront.net/_assets/home-video/beach-waves-loop.mp4" type="video/mp4">
        <source src="https://d2ezlykacdqcnj.cloudfront.net/_assets/home-video/beach-waves-loop.webm" type="video/webm">
        <source src="https://d2ezlykacdqcnj.cloudfront.net/_assets/home-video/beach-waves-loop.ogv" type="video/ogg">
        </video>
            <div class="video-overlay"></div>
            <div class="page-width">
                <div class="video-hero--content">
                        <h2>Kako je propao TikTok</h2>
                        <p>Objasnjeno</p>
                </div>
            </div>
        </div>
        <!-- End video hero -->

        <div id="content">
            <div class="page-width">
                <h3>Easy Background Videos</h3>
                <p>Cijeli sadrzaj stranice napisala je Emina Abaza<a ></a>p

                <p>Molimo dajte joj 5, potrudila se :)<a 
                    div
 /* Settings - feel free to play with these */
$overlay_opacity: 0.3; // 0-1
$overlay_pattern: 'https://d3k5xyayaartr5.cloudfront.net/_assets/pattern-overlays/patterns/black-medium-checks.png'; // Grab the url of a png from here - http://html5backgroundvideos.com/pattern-overlays/

@import url(https://fonts.googleapis.com/css?family=Roboto:400,700);

/**
 * This part should be set separately for each video
 * if there are multiple videos in your site.
 * I.e. '.demo-video-wrapper' is the name of this particular video
 */
.demo-video-wrapper {
	background-image: url(https://d3k5xyayaartr5.cloudfront.net/_assets/home-video/beach-waves-loop.jpg);
}

/* Video overlay and content */
.video-overlay {
	position: absolute;
	top: 0;
	left: 0;
	bottom: 0;
	right: 0;
	pointer-events: none; /* Allows right click menu on the video */
	background: url($overlay_pattern) left top repeat;
  opacity: $overlay_opacity;
}
.video-hero--content {
	position: relative;
	text-align: center;
	color: #FFF;
  margin: 150px 0;
	text-shadow: 0 0 5px rgba(0,0,0,0.4);
}
.video-hero--content h2 {
	font-size: 34px;
	margin: 0 0 10px;
}
.video-hero--content p {
	font-size: 20px;
	margin: 0;
}

/* Other stuff */
body {
	font-family: 'Roboto', sans-serif;
	font-size: 16px;
	line-height: 1.4;
	color: #666;
}
a {
	text-decoration: none;
	color: #a46497;
}
.cf:before,
.cf:after {
    content: " ";
    display: table;
}
.cf:after {
    clear: both;
}
.page-width {
	width: 92%;
	max-width: 960px;
	margin: 0 auto;
}
#header {
	background: #2c2d33;
	padding: 2em 0;
}
#header a {
	color: #FFF;
}
.title {
	display: block;
	font-weight: bold;
	font-size: 18px;
}
.subtitle {
	display: block;
	font-weight: normal;
	font-size: 15px;
	color: #959699;
}
a:hover .subtitle {
	color: #FFF;
}
#site-title {
	float: left;
	margin: 0;
}
#content {
	padding: 40px 0;
}


/* CSS from jQuery Background Video plugin */
/**
 * Set default positioning as a fallback for if the plugin fails
 */
.jquery-background-video-wrapper {
	position: relative;
	overflow: hidden;
	background-position: center center;
	background-repeat: no-repeat;
	-webkit-background-size: cover;
	   -moz-background-size: cover;
	    	background-size: cover;
}
.jquery-background-video {
	position: absolute;
	min-width: 100%;
	min-height: 100%;
	width: auto;
	height: auto;
	top: 50%;
	left: 50%;
	-o-object-fit: contain;
	   object-fit: contain;
	-webkit-transform: translate(-50%,-50%);
	   -moz-transform: translate(-50%,-50%);
	    -ms-transform: translate(-50%,-50%);
	     -o-transform: translate(-50%,-50%);
	    	transform: translate(-50%,-50%);
}
/**
 * Fade in videos
 * Note the .js class - so non js users still
 * see the video
 */
.js .jquery-background-video {
	opacity: 0;
	-webkit-transition: opacity 300ms linear;
			transition: opacity 300ms linear;
}
.js .jquery-background-video.is-visible {
	opacity: 1;
}

/**
 * Pause/play button
 */ 
.jquery-background-video-pauseplay {
	position: absolute;
	background: transparent;
	border: none;
	box-shadow: none;
	width: 20px;
	height: 20px;
	top: 15px;
	right: 15px;
	padding: 0;
	cursor: pointer;
	outline: none !important;
}
.jquery-background-video-pauseplay span {
	display: none;
}
.jquery-background-video-pauseplay:after,
.jquery-background-video-pauseplay:before {
	content: "";
	position: absolute;
	left: 0;
	top: 0;
	-webkit-transition: all .3s ease;
			transition: all .3s ease;
}
.jquery-background-video-pauseplay.play:before {
	border-top: 10px solid transparent;
	border-bottom: 10px solid transparent;
	border-left: 15px solid #FFF;
}
.jquery-background-video-pauseplay.pause:before,
.jquery-background-video-pauseplay.pause:after {
	border-top: 10px solid #FFF;
	border-bottom: 10px solid #FFF;
	border-left: 5px solid #FFF;
}
.jquery-background-video-pauseplay.pause:after {
	left: 10px;
}
                                                         
