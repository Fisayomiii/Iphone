<template>
  <div class="grid min-h-screen place-items-center">
    <div
      class="relative mx-auto h-[550px] w-[320px] bg-black rounded-[50px] border-[14px] border-black overflow-hidden shadow-xl">
      <img class="absolute inset-0 h-full w-full object-cover"
        src="../src/assets/Imgs/desktop-wallpaper-juice-wrld-fighting-demons-phone-r-juicewrld-thumbnail.jpg" />
      <div class="absolute top-0 inset-x-0 z-20">
        <div class="mx-auto bg-black h-6 w-40 rounded-b-3xl"></div>
      </div>

      <div class="relative" v-motion :initial="{ opacity: 0, y: 100 }" :enter="{ opacity: 1, y: 0, scale: 1 }"
        :delay="900">
        <div className="container ">
          <div className="control-center-grid">
            <div className="connections grid-item">
              <div className="airplane-mode">
                <i class='bx bxs-plane-alt bx-sm'></i>
              </div>
              <div className="cellular">
                <i class='bx bx-broadcast bx-sm'></i>
              </div>
              <div className="wifi">
                <i class='bx bx-wifi bx-sm'></i>
              </div>
              <div className="bluetooth">
                <i class='bx bx-bluetooth bx-sm'></i>
              </div>
            </div>
            <div className="music grid-item" >
              <span>Music</span>
              <span>Juice WRLD</span>

              <div>
                <i class='bx bx-rewind bx-md'></i>
              </div>
              <div>
                <i class='bx bx-play bx-md'></i>
              </div>
              <div>
                <i class='bx bx-rewind bx-rotate-180 bx-md'></i>
              </div>
            </div>
            <div className="orientation grid-item">
              <i class='bx bxs-landscape bx-sm'></i>
            </div>
            <div className="nightmode grid-item">
              <i class='bx bxs-moon bx-sm'></i>
            </div>
            <div className="brightness grid-item">
              <i class='bx bxs-brightness-half bx-sm bg-[#000]'></i>
            </div>
            <div className="volume grid-item">
              <i class='bx bxs-volume-full'></i>
            </div>
            <div className="screen grid-item">
              <i class='bx bx-cast bx-sm'></i>
              <span>
                Screen
              </span>
            </div>
            <div className="flashlight grid-item">
              <i class='bx bxs-bulb bx-sm'></i>
            </div>
            <div className="timer grid-item">
              <i class='bx bxs-timer bx-sm'></i>
            </div>
            <div className="calculator grid-item">
              <i class='bx bxs-calculator bx-sm'></i>
            </div>
            <div className="camera grid-item">
              <i class='bx bxs-camera bx-sm'></i>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
// import { motion } from "framer-motion";

</script>