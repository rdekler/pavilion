---
layout: default
title: Home
permalink: /home/
---

<div class="slider">
  <div class="slide">
    <video class="slide-video" autoplay>
	    		<source src="https://pavilion.chass.ncsu.edu/demos/Pavilion/wordpress/wp-content/uploads/2015/11/1B.mp4" type="video/mp4">
		<source src="https://pavilion.chass.ncsu.edu/demos/Pavilion/wordpress/wp-content/uploads/2015/12/1B_OGG.ogg" type="video/ogg">
	    </video>
  </div>
  <div class="slide">
	<video class="slide-video" autoplay>
		<source src="https://pavilion.chass.ncsu.edu/demos/Pavilion/wordpress/wp-content/uploads/2015/11/2.mp4" type="video/mp4">
		<source src="https://pavilion.chass.ncsu.edu/demos/Pavilion/wordpress/wp-content/uploads/2015/12/2_OGG.ogg" type="video/ogg">
	</video>
</div>
  <div class="slide">
	<video class="slide-video" autoplay>
		<source src="https://pavilion.chass.ncsu.edu/demos/Pavilion/wordpress/wp-content/uploads/2015/11/3.mp4" type="video/mp4">
		<source src="https://pavilion.chass.ncsu.edu/demos/Pavilion/wordpress/wp-content/uploads/2015/12/3_OGG.ogg" type="video/ogg">
	</video>
</div>
  <div class="slide">
        <video class="slide-video" autoplay>

        	<source src="https://pavilion.chass.ncsu.edu/demos/Pavilion/wordpress/wp-content/uploads/2015/11/4.mp4" type="video/mp4">

                <source src="https://pavilion.chass.ncsu.edu/demos/Pavilion/wordpress/wp-content/uploads/2015/12/4_OGG.ogg" type="video/ogg">  

    </video>
  </div>
  <div class="slide">
<video class="slide-video" autoplay>
	<source src="https://pavilion.chass.ncsu.edu/demos/Pavilion/wordpress/wp-content/uploads/2015/11/5b.mp4" type="video/mp4" />
	<source src="https://pavilion.chass.ncsu.edu/demos/Pavilion/wordpress/wp-content/uploads/2015/12/5b_OGG.ogg" type="video/ogg" />
	</video>
</div>
</div>

<script>
  $(document).ready(function(){
    $(".slider").slick({
      dots : true ,
      pauseOnDotsHover : true ,
      autoplay : true ,
      autoplaySpeed : 20000 ,
      arrows : false
    }) ;
  }) ;
</script>

<style>
	.content-wrapper {
		padding : 0 ;
		max-width : 100% ;
	}
	
	.slider {
		width : 100% ;
	}
</style>
