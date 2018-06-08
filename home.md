---
layout: default
title: Home
permalink: /home/
---

<div class="slider">
  <div class="slide">
    <video class="slide-video">
      <source src="https://pavilion.chass.ncsu.edu/demos/Pavilion/wordpress/wp-content/uploads/2015/11/4.mp4" type="video/mp4">
		  <source src="https://pavilion.chass.ncsu.edu/demos/Pavilion/wordpress/wp-content/uploads/2015/12/4_OGG.ogg" type="video/ogg">  
    </video>
  </div>
  <div class="slide"></div>
  <div class="slide"></div>
  <div class="slide"></div>
  <div class="slide"></div>
</div>

<script>
  $(document).ready(function(){
    $(".slider").slick({
      dots : true ,
      pauseOnDotsHover : true
    }) ;
  }) ;
</script>
