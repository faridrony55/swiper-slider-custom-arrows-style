# swiper-slider-custom-arrows-style

<style><br>
  .swiper-button-prev.swiper-button-prev_mySwiper3:empty, .swiper-button-next.swiper-button-next_mySwiper3:empty{\
  display:block;\
}\
.swiper-button-prev.swiper-button-prev_mySwiper3, .swiper-button-next.swiper-button-next_mySwiper3 {\
    width: 50px;\
    height: 50px;\
    border-radius: 50%;\
    background-color: #fff;\
}\
\
\


.swiper-button-prev.swiper-button-prev_mySwiper3::after,\
.swiper-button-prev.swiper-button-prev_mySwiper3::before,\
.swiper-button-next.swiper-button-next_mySwiper3::after,\
.swiper-button-next.swiper-button-next_mySwiper3::before{\
  height: 2px;\
    width: 25px;\
    background: var(--blue); \
    position: absolute;\ 
  content:""; \
}\
 
.swiper-button-prev.swiper-button-prev_mySwiper3::after,\
.swiper-button-prev.swiper-button-prev_mySwiper3::before{ \
    left: 10px;\
     
}\
.swiper-button-next.swiper-button-next_mySwiper3::after,\
.swiper-button-next.swiper-button-next_mySwiper3::before{ \
    right: 10px;\
}\
 
.swiper-button-prev.swiper-button-prev_mySwiper3::before,\
.swiper-button-next.swiper-button-next_mySwiper3::before {\
    
    transform: rotate(-40deg); \
}\

.swiper-button-prev.swiper-button-prev_mySwiper3::after,\
.swiper-button-next.swiper-button-next_mySwiper3::after{\
  transform: rotate(40deg); \
}\

\
.swiper-button-prev.swiper-button-prev_mySwiper3::before,\
.swiper-button-next.swiper-button-next_mySwiper3::after {  \
    top: 16px; \
} \

.swiper-button-prev.swiper-button-prev_mySwiper3::after,\
.swiper-button-next.swiper-button-next_mySwiper3::before { \
    bottom: 17px;\     
}\
/***** Slider Custom CSSS ***/\

</style>\
