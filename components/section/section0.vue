<template>
    <div>
      <div class="w-[80%] m-auto">
        <Swiper
          :modules="modules"
          @swiper="(s) => (mySwiper = s)"
          :slides-per-view="5"
          :breakpoints="{
            300: {
              slidesPerView: 1.175,
            },
            400: {
              slidesPerView: 1.515,
            },
            768: {
              slidesPerView: 3,
              spaceBetween: 20,
            },
            1024: {
              slidesPerView: 4,
            },
          }"
          :space-between="28"
          loop
          :autoplay="{
            delay: 3000,
            disableOnInteraction: false,
            pauseOnMouseEnter: true,
          }"
          :speed="3000"
          class="!z-0 rounded-lg"
          @slideChange="onSlideChange"
        >
          <SwiperSlide v-for="(item, index) of 1" :key="index">
            <div class="">
              <div class="">
                <div class=" ">
                  <div class=" ">
                    <img class="" src="https://cdn.hoanghamobile.com/i/home/Uploads/2024/05/11/galaxy-s24-ultra-web.jpg" />
                  </div>
              </div>
            </div>
            </div>
          </SwiperSlide>
          <SwiperSlide v-for="(item, index) of 1" :key="index">
            <div class=" rounded-xl relative w-full">
              <div class="w-full">
                <div class="bg-white  flex flex-col justify-center items-center ">
                  <div class="">
                    <img class="w-full" src="https://cdn.hoanghamobile.com/i/home/Uploads/2024/05/06/note-13-web.png" />
                  </div>
                </div>
              </div>
            </div>
          </SwiperSlide>
          <SwiperSlide v-for="(item, index) of 1" :key="index">
  <div class="rounded-xl relative w-full">
    <div class="w-full">
      <div class="bg-white flex flex-col justify-center items-center">
        <div>
          <img class="w-full md:w-auto" src="https://cdn.hoanghamobile.com/i/home/Uploads/2024/05/06/note-13-web.png" />
        </div>
      </div>
    </div>
  </div>
</SwiperSlide>

        </Swiper>
      </div>
    </div>
  </template>
  
  <script setup>
  import { Swiper, SwiperSlide } from "swiper/vue";
  import { Autoplay, Pagination } from "swiper/modules";
  import "swiper/css";
  import "swiper/element/css/pagination";
  
  const modules = [Autoplay, Pagination];
  </script>
  