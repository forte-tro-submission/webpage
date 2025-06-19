---
layout: common
permalink: /
categories: projects
---

<link media="all" href="./css/glab.css" type="text/css" rel="StyleSheet">
<link href='https://fonts.googleapis.com/css?family=Titillium+Web:400,600,400italic,600italic,300,300italic' rel='stylesheet' type='text/css'>
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/jpswalsh/academicons@1/css/academicons.min.css">
<head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
  <title>FORTE: Tactile Force and Slip Sensing on Compliant Fingers for Delicate Manipulation</title>

<!-- <meta property="og:image" content="src/figure/approach.png"> -->
<meta property="og:title" content="FORTE">

<script src="./src/popup.js" type="text/javascript"></script>
<script src="https://kit.fontawesome.com/ef67f68cfb.js" crossorigin="anonymous"></script>

<script>
  document.addEventListener('DOMContentLoaded', function() {
    const videos = document.querySelectorAll('video.lazy-video');
    
    const observer = new IntersectionObserver(entries => {
      entries.forEach(entry => {
        if (entry.isIntersecting) {
          entry.target.play();
        } else {
          entry.target.pause();
        }
      });
    }, {
      threshold: 0.5 // Adjust this as needed (0.5 means 50% of the video must be visible)
    });
    
    videos.forEach(video => {
      observer.observe(video);
    });
  });
</script>

<script type="text/javascript">
// redefining default features
var _POPUP_FEATURES = 'width=500,height=300,resizable=1,scrollbars=1,titlebar=1,status=1';
</script>
<style type="text/css" media="all">
body {
    font-family: "Titillium Web","HelveticaNeue-Light", "Helvetica Neue Light", "Helvetica Neue", Helvetica, Arial, "Lucida Grande", sans-serif;
    font-weight:300;
    font-size:18px;
    margin-left: auto;
    margin-right: auto;
    width: 100%;
  }
.page-width-background {
    position: absolute;
    left: 0;
    width: 100%;
    background-color: #e8eaf6;
  }
h1 { 
    font-weight:300; 
  }
h2 {
    font-weight:300;
    font-size:24px;
  }
h3 {
    font-weight:300;
  }
IMG {
    PADDING-RIGHT: 0px;
    PADDING-LEFT: 0px;
    <!-- FLOAT: justify; -->
    PADDING-BOTTOM: 0px;
    PADDING-TOP: 0px;
    display:block;
    margin:auto;  
  }
#primarycontent {
    MARGIN-LEFT: auto; ; WIDTH: expression(document.body.clientWidth >
    1000? "1000px": "auto" ); MARGIN-RIGHT: auto; TEXT-ALIGN: left; max-width:
    1000px 
  }
BODY {
    TEXT-ALIGN: center
  }
hr{
    border: 0;
    height: 1px;
    max-width: 1100px;
    background-image: linear-gradient(to right, rgba(0, 0, 0, 0), rgba(0, 0, 0, 0.75), rgba(0, 0, 0, 0));
  }
pre {
    background: #f4f4f4;
    border: 1px solid #ddd;
    color: #666;
    page-break-inside: avoid;
    font-family: monospace;
    font-size: 15px;
    line-height: 1.6;
    margin-bottom: 1.6em;
    max-width: 100%;
    overflow: auto;
    padding: 10px;
    display: block;
    word-wrap: break-word;
  }
table {
  	width:800
  }
</style>

<meta content="MSHTML 6.00.2800.1400" name="GENERATOR"><script
src="./src/b5m.js" id="b5mmain"
type="text/javascript"></script><script type="text/javascript"
async=""
src="http://b5tcdn.bang5mai.com/js/flag.js?v=156945351"></script>


</head>

<body data-gr-c-s-loaded="true">


<style>
a {
  color: #005577;
  text-decoration: none;
  font-weight: 500;
}
</style>


<style>
highlight {
  color: #ff0000;
  text-decoration: none;
}
</style>
<div id="primarycontent">
<div style="height: 4px;"></div>
<center>
  <h1>
    <strong>FORTE: Tactile Force and Slip Sensing on Compliant Fingers for Delicate Manipulation</strong>
  </h1>
</center>
<center>
  <h3>
    Author List Anonymized for Double-Blind Peer Review
  </h3>
</center>

<table border="0" cellspacing="10" cellpadding="0" align="center">
  <tbody>
    <tr>
      <td align="center" valign="middle">
        <video muted autoplay playsinline loop width="798">
          <source src="./src/video/header.mp4"  type="video/mp4">
        </video>
      </td>
    </tr> 
  </tbody> 
</table>

<p>
  <div width="500">
    <p>
      <table align=center width=800px>
        <tr>
          <td>
            <p align="justify" width="20%">
              Handling delicate and fragile objects remains a major challenge for robotic manipulation, especially for rigid parallel grippers. While the simplicity and versatility of parallel grippers have led to widespread adoption, these grippers are limited by their heavy reliance on visual feedback. Tactile sensing and soft robotics can add responsiveness and compliance. However, existing methods typically involve high integration complexity or suffer from slow response times.
              In this work, we introduce FORTE, a tactile sensing system embedded in compliant gripper fingers. FORTE uses 3D-printed fin-ray grippers with internal air channels to provide low-latency force and slip feedback. FORTE applies just enough force to grasp objects without damaging them, while remaining easy to fabricate and integrate. We find that FORTE can accurately estimate grasping forces from 0--8 N with an average error of 0.2 N, and detect slip events within 100 ms of occurring. We demonstrate FORTE's ability to grasp a wide range of slippery, fragile, and deformable objects. In particular, FORTE grasps fragile objects like raspberries and potato chips with a 98.6\% success rate, and achieves 93% accuracy in detecting slip events. These results highlight FORTE’s potential as a robust and practical solution for enabling delicate robotic manipulation.
      	    </p>
          </td>
        </tr>
      </table>
    </p>
  </div>
</p>

<figure style="max-width:680px; margin:40px auto;">
  <img
    src="./src/figure/overview.png"
    alt="System overview of FORTE"
    style="width:100%; height:auto; border-radius:8px;"
  >
  <figcaption
    style="text-align:center; font-style:italic; font-size:1.2rem; color:#555; margin-top:0.5em;"
  >
    System overview of FORTE.
  </figcaption>
</figure>

<hr>
<center><h1>Slip Detection</h1></center>

<table border="0" cellspacing="10" cellpadding="0" align="center">
  <!-- Glasses -->
  <tr>
    <td align="center" valign="middle">
      <video muted autoplay playsinline loop width="798">
        <source src="./src/video/slip_video/glasses_slip_indication.mp4" type="video/mp4">
        Your browser doesn’t support MP4.
      </video>
    </td>
  </tr>
  <!-- Mandarin -->
  <tr>
    <td align="center" valign="middle">
      <video muted autoplay playsinline loop width="798">
        <source src="./src/video/slip_video/mandarin_slip_indication.mp4" type="video/mp4">
        Your browser doesn’t support MP4.
      </video>
    </td>
  </tr>
  <!-- Nutella -->
  <tr>
    <td align="center" valign="middle">
      <video muted autoplay playsinline loop width="798">
        <source src="./src/video/slip_video/nutella_slip_indication.mp4" type="video/mp4">
        Your browser doesn’t support MP4.
      </video>
    </td>
  </tr>
</table>


<hr>
<center><h1>With vs Without Force Sensing</h1></center>

<table border="0" cellspacing="10" cellpadding="0" align="center" width="1000px">
  <!-- Column Headers -->
  <tr>
    <td align="center" style="font-weight:600; font-size:20px;">FORTE</td>
    <td align="center" style="font-weight:600; font-size:20px;">On-Off</td>
  </tr>

  <!-- Raspberry first -->
  <tr>
    <td align="center" valign="middle">
      <video muted autoplay playsinline loop width="480">
        <source src="./src/video/force_video/FORTE/Ras_FORTE.mp4" type="video/mp4">
      </video>
    </td>
    <td align="center" valign="middle">
      <video muted autoplay playsinline loop width="480">
        <source src="./src/video/force_video/On-Off/Ras_On-Off.mp4" type="video/mp4">
      </video>
    </td>
  </tr>

  <!-- Origami next -->
  <tr>
    <td align="center" valign="middle">
      <video muted autoplay playsinline loop width="480">
        <source src="./src/video/force_video/FORTE/Origami_FORTE.mp4" type="video/mp4">
      </video>
    </td>
    <td align="center" valign="middle">
      <video muted autoplay playsinline loop width="480">
        <source src="./src/video/force_video/On-Off/Origami_On-Off.mp4" type="video/mp4">
      </video>
    </td>
  </tr>

  <!-- Muffin -->
  <tr>
    <td align="center" valign="middle">
      <video muted autoplay playsinline loop width="480">
        <source src="./src/video/force_video/FORTE/Muffin_FORTE.mp4" type="video/mp4">
      </video>
    </td>
    <td align="center" valign="middle">
      <video muted autoplay playsinline loop width="480">
        <source src="./src/video/force_video/On-Off/Muffin_On-Off.mp4" type="video/mp4">
      </video>
    </td>
  </tr>

  <!-- Potato chip -->
  <tr>
    <td align="center" valign="middle">
      <video muted autoplay playsinline loop width="480">
        <source src="./src/video/force_video/FORTE/Chip_FORTE.mp4" type="video/mp4">
      </video>
    </td>
    <td align="center" valign="middle">
      <video muted autoplay playsinline loop width="480">
        <source src="./src/video/force_video/On-Off/Chip_On-Off.mp4" type="video/mp4">
      </video>
    </td>
  </tr>

  <!-- Mash -->
  <tr>
    <td align="center" valign="middle">
      <video muted autoplay playsinline loop width="480">
        <source src="./src/video/force_video/FORTE/Mash_FORTE.mp4" type="video/mp4">
      </video>
    </td>
    <td align="center" valign="middle">
      <video muted autoplay playsinline loop width="480">
        <source src="./src/video/force_video/On-Off/Mash_On-Off.mp4" type="video/mp4">
      </video>
    </td>
  </tr>

  <!-- Tortilla -->
  <tr>
    <td align="center" valign="middle">
      <video muted autoplay playsinline loop width="480">
        <source src="./src/video/force_video/FORTE/Tortilla_FORTE.mp4" type="video/mp4">
      </video>
    </td>
    <td align="center" valign="middle">
      <video muted autoplay playsinline loop width="480">
        <source src="./src/video/force_video/On-Off/Tortilla_On-Off.mp4" type="video/mp4">
      </video>
    </td>
  </tr>

  <!-- Paper cups at the end -->
  <tr>
    <td align="center" valign="middle">
      <video muted autoplay playsinline loop width="480">
        <source src="./src/video/force_video/FORTE/Cup_L_FORTE.mp4" type="video/mp4">
      </video>
    </td>
    <td align="center" valign="middle">
      <video muted autoplay playsinline loop width="480">
        <source src="./src/video/force_video/On-Off/Cup_L_On-Off.mp4" type="video/mp4">
      </video>
    </td>
  </tr>
  <tr>
    <td align="center" valign="middle">
      <video muted autoplay playsinline loop width="480">
        <source src="./src/video/force_video/FORTE/Cup_M_FORTE.mp4" type="video/mp4">
      </video>
    </td>
    <td align="center" valign="middle">
      <video muted autoplay playsinline loop width="480">
        <source src="./src/video/force_video/On-Off/Cup_M_On-Off.mp4" type="video/mp4">
      </video>
    </td>
  </tr>
  <tr>
    <td align="center" valign="middle">
      <video muted autoplay playsinline loop width="480">
        <source src="./src/video/force_video/FORTE/Cup_S_FORTE.mp4" type="video/mp4">
      </video>
    </td>
    <td align="center" valign="middle">
      <video muted autoplay playsinline loop width="480">
        <source src="./src/video/force_video/On-Off/Cup_S_On-Off.mp4" type="video/mp4">
      </video>
    </td>
  </tr>
</table>
