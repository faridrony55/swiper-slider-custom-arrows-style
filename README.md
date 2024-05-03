# swiper-slider-custom-arrows-style

<style><br>
  .swiper-button-prev.swiper-button-prev_mySwiper3:empty, <br>
  .swiper-button-next.swiper-button-next_mySwiper3:empty{<br>
  display:block;<br>
}<br>
.swiper-button-prev.swiper-button-prev_mySwiper3, <br>
.swiper-button-next.swiper-button-next_mySwiper3 {<br>
    width: 50px;<br>
    height: 50px;<br>
    border-radius: 50%;<br>
    background-color: #fff;<br>
}<br>
<br>
<br>


.swiper-button-prev.swiper-button-prev_mySwiper3::after,<br>
.swiper-button-prev.swiper-button-prev_mySwiper3::before,<br>
.swiper-button-next.swiper-button-next_mySwiper3::after,<br>
.swiper-button-next.swiper-button-next_mySwiper3::before{<br>
  height: 2px;<br>
    width: 25px;<br>
    background: var(--blue); <br>
    position: absolute;<br>
  content:""; <br>
}<br>
 
.swiper-button-prev.swiper-button-prev_mySwiper3::after,<br>
.swiper-button-prev.swiper-button-prev_mySwiper3::before{ <br>
    left: 10px;<br>
     
}<br>
.swiper-button-next.swiper-button-next_mySwiper3::after,<br>
.swiper-button-next.swiper-button-next_mySwiper3::before{ <br>
    right: 10px;<br>
}<br>
 
.swiper-button-prev.swiper-button-prev_mySwiper3::before,<br>
.swiper-button-next.swiper-button-next_mySwiper3::before {<br>
    
    transform: rotate(-40deg); <br>
}<br>

.swiper-button-prev.swiper-button-prev_mySwiper3::after,<br>
.swiper-button-next.swiper-button-next_mySwiper3::after{<br>
  transform: rotate(40deg); <br>
}<br>

<br>
.swiper-button-prev.swiper-button-prev_mySwiper3::before,<br>
.swiper-button-next.swiper-button-next_mySwiper3::after {  <br>
    top: 16px; <br>
} <br>

.swiper-button-prev.swiper-button-prev_mySwiper3::after,<br>
.swiper-button-next.swiper-button-next_mySwiper3::before { <br>
    bottom: 17px;<br>     
}<br>
/***** Slider Custom CSSS ***/<br>

</style><br>
