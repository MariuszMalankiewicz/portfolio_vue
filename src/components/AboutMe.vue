<script setup>
import { ref } from 'vue'


</script>

<template>
  <section id="about" class="bg-black min-h-360 w-full min-h-screen flex flex-col justify-center items-center relative overflow-hidden">
    <img class="w-48 border-4 border-red-600 rotate-3 rounded-xl my-12" src="../../public/images/me.jpg" alt="author">
    <div class="text-slate-300 text-center">
      <p id="first" class="text-xs font-agbalumo inline-block text-white">Cześć<span class="text-red-600">!</span></p><br>
      <p id="secound" class="text-sm font-love_ya_like_a_sister mt-1 inline-block">Nazywam się</p><br>
      <h2 id="thirth" class="font-bold font-caveat text-2xl inline-block"><span class="text-red-600">M</span>ariusz <span class="text-red-600">M</span>alankiewicz</h2><br>
      <p id="fourth" class="text-sm my-2 font-love_ya_like_a_sister inline-block">Jestem <span class="font-space_mono text-red-500 font-bold">FullStack</span> developerem</p><br>
      <p id="fiveth" class="text-sm font-love_ya_like_a_sister inline-block">Pracuje z technologiami <span class="font-bold text-red-600">PHP</span> oraz <span class="font-bold text-red-600">JS</span></p><br>
      <a id="sixth" class="text-md font-agbalumo my-12 cursor-pointer ease-in-out duration-300 hover:text-red-500 inline-block">Zobacz moje Projekty</a>
      <div class="flex justify-center items-center mb-5">
        <svg id="codePhp" class="fill-white text-3xl" xmlns="http://www.w3.org/2000/svg" height="1em" viewBox="0 0 640 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. --><path d="M320 104.5c171.4 0 303.2 72.2 303.2 151.5S491.3 407.5 320 407.5c-171.4 0-303.2-72.2-303.2-151.5S148.7 104.5 320 104.5m0-16.8C143.3 87.7 0 163 0 256s143.3 168.3 320 168.3S640 349 640 256 496.7 87.7 320 87.7zM218.2 242.5c-7.9 40.5-35.8 36.3-70.1 36.3l13.7-70.6c38 0 63.8-4.1 56.4 34.3zM97.4 350.3h36.7l8.7-44.8c41.1 0 66.6 3 90.2-19.1 26.1-24 32.9-66.7 14.3-88.1-9.7-11.2-25.3-16.7-46.5-16.7h-70.7L97.4 350.3zm185.7-213.6h36.5l-8.7 44.8c31.5 0 60.7-2.3 74.8 10.7 14.8 13.6 7.7 31-8.3 113.1h-37c15.4-79.4 18.3-86 12.7-92-5.4-5.8-17.7-4.6-47.4-4.6l-18.8 96.6h-36.5l32.7-168.6zM505 242.5c-8 41.1-36.7 36.3-70.1 36.3l13.7-70.6c38.2 0 63.8-4.1 56.4 34.3zM384.2 350.3H421l8.7-44.8c43.2 0 67.1 2.5 90.2-19.1 26.1-24 32.9-66.7 14.3-88.1-9.7-11.2-25.3-16.7-46.5-16.7H417l-32.8 168.7z"/></svg>
        <svg id="code" class="fill-white text-3xl mx-5" xmlns="http://www.w3.org/2000/svg" height="1em" viewBox="0 0 640 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. --><path d="M392.8 1.2c-17-4.9-34.7 5-39.6 22l-128 448c-4.9 17 5 34.7 22 39.6s34.7-5 39.6-22l128-448c4.9-17-5-34.7-22-39.6zm80.6 120.1c-12.5 12.5-12.5 32.8 0 45.3L562.7 256l-89.4 89.4c-12.5 12.5-12.5 32.8 0 45.3s32.8 12.5 45.3 0l112-112c12.5-12.5 12.5-32.8 0-45.3l-112-112c-12.5-12.5-32.8-12.5-45.3 0zm-306.7 0c-12.5-12.5-32.8-12.5-45.3 0l-112 112c-12.5 12.5-12.5 32.8 0 45.3l112 112c12.5 12.5 32.8 12.5 45.3 0s12.5-32.8 0-45.3L77.3 256l89.4-89.4c12.5-12.5 12.5-32.8 0-45.3z"/></svg>
        <svg id="codeJs" class="fill-white text-3xl" xmlns="http://www.w3.org/2000/svg" height="1em" viewBox="0 0 448 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. --><path d="M0 32v448h448V32H0zm243.8 349.4c0 43.6-25.6 63.5-62.9 63.5-33.7 0-53.2-17.4-63.2-38.5l34.3-20.7c6.6 11.7 12.6 21.6 27.1 21.6 13.8 0 22.6-5.4 22.6-26.5V237.7h42.1v143.7zm99.6 63.5c-39.1 0-64.4-18.6-76.7-43l34.3-19.8c9 14.7 20.8 25.6 41.5 25.6 17.4 0 28.6-8.7 28.6-20.8 0-14.4-11.4-19.5-30.7-28l-10.5-4.5c-30.4-12.9-50.5-29.2-50.5-63.5 0-31.6 24.1-55.6 61.6-55.6 26.8 0 46 9.3 59.8 33.7L368 290c-7.2-12.9-15-18-27.1-18-12.3 0-20.1 7.8-20.1 18 0 12.6 7.8 17.7 25.9 25.6l10.5 4.5c35.8 15.3 55.9 31 55.9 66.2 0 37.8-29.8 58.6-69.7 58.6z"/></svg>
      </div>
    </div>
    <div id="square1"></div> 
    <div id="square2"></div> 
    <div id="square3"></div> 
    <div id="square4"></div> 
   </section>
</template>

<style scoped>

#square1{
  position: absolute;
  width: 50px;
  height: 50px;
  left: -10%;
  right: -10%;
  border: 3px solid red;
  border-radius: 10%;
  animation: squareFly 10s infinite alternate;
  animation-delay: 23.5s;
}

#square2{
  position: absolute;
  width: 50px;
  height: 50px;
  left: -10%;
  right: -10%;
  border: 3px solid red;
  border-radius: 10%;
  animation: squareFly 10s infinite reverse;
  animation-delay: 23.5s;
}


@keyframes squareFly {
  0%{
    opacity: 0.3;
    top: -10%;
    left: -10%;
  }
  25%{
    transform: scale(.6) rotateX(10deg) rotateY(180deg);
    opacity: .4;
    top: 40%;
    left: 30%;
  }
  40%{
    transform: scale(2) rotateX(20deg) rotateY(0deg);
    border-radius: 5%;
    opacity: 1;
    top: 70%;
    left: 10%;
  }
  42%{
    transform: scale(1) rotateX(20deg) rotateY(0deg);
    opacity: 0;
    top: 70%;
    left: 10%;
  }
  44%{
    transform: scale(2) rotateX(0deg) rotateY(0deg);
    opacity: 1;
    top: 70%;
    left: 10%;
  }
  46%{
    transform: scale(1) rotateX(20deg) rotateY(0deg);
    opacity: 0;
    top: 70%;
    left: 10%;
  }
  48%{
    transform: scale(2) rotateX(0deg) rotateY(0deg);
    outline: none;
    opacity: 1;
    top: 70%;
    left: 10%;
  }
  60%{
    transform: scale(.4) rotateX(0deg) rotateY(0deg) rotateZ(720deg);
    opacity: .6;
    top: 70%;
    left: 10%;
  }
  80%{
    transform: scale(1) rotateX(0deg) rotateY(0deg) rotateZ(0deg);
    opacity: .4;
    top: 70%;
    left: 10%;
  }
  100%{
    transform: scale(1) rotateX(0deg) rotateY(0deg) rotateZ(360deg);
    opacity: .2;
    top: -10%;
    left: -10%;
  }
}

#square3{
  position: absolute;
  width: 50px;
  height: 50px;
  left: 110%;
  right: 110%;
  border: 3px solid red;
  border-radius: 10%;
  animation: squareFlyRight 10s infinite alternate;
  animation-delay: 23.5s;
}

#square4{
  position: absolute;
  width: 50px;
  height: 50px;
  left: 110%;
  right: 110%;
  border: 3px solid red;
  border-radius: 10%;
  animation: squareFlyRight 10s infinite reverse;
  animation-delay: 23.5s;
}

@keyframes squareFlyRight {
  0%{
    opacity: 0.3;
    top: -10%;
    left: 110%;
  }
  25%{
    transform: scale(.6) rotateX(10deg) rotateY(180deg);
    opacity: .4;
    top: 40%;
    left: 70%;
  }
  40%{
    transform: scale(2) rotateX(20deg) rotateY(0deg);
    border-radius: 5%;
    opacity: 1;
    top: 70%;
    left: 90%;
  }
  42%{
    transform: scale(1) rotateX(20deg) rotateY(0deg);
    opacity: 0;
    top: 70%;
    left: 90%;
  }
  44%{
    transform: scale(2) rotateX(0deg) rotateY(0deg);
    opacity: 1;
    top: 70%;
    left: 90%;
  }
  46%{
    transform: scale(1) rotateX(20deg) rotateY(0deg);
    opacity: 0;
    top: 70%;
    left: 90%;
  }
  48%{
    transform: scale(2) rotateX(0deg) rotateY(0deg);
    outline: none;
    opacity: 1;
    top: 70%;
    left: 90%;
  }
  60%{
    transform: scale(.4) rotateX(0deg) rotateY(0deg) rotateZ(720deg);
    opacity: .6;
    top: 70%;
    left: 90%;
  }
  80%{
    transform: scale(1) rotateX(0deg) rotateY(0deg) rotateZ(0deg);
    opacity: .4;
    top: 70%;
    left: 90%;
  }
  100%{
    transform: scale(1) rotateX(0deg) rotateY(0deg) rotateZ(360deg);
    opacity: .2;
    top: -10%;
    left: 110%;
  }
}

#about img{
  animation: loadImage 4s 1;
}

@keyframes loadImage {
  0%{
    opacity: 0;
    transform: rotatex(0deg) rotateY(0deg) translateX(0vw) translateY(0vh)
  }
  0%, 40%{
    opacity: 0.2;
  }
  40%{
    opacity: 1;
    transform: rotatex(20deg) rotateY(180deg) scale(1.1) translateX(20vw) translateY(30vh)
  }
  41%, 70%{
    opacity: 0.2;
  }
  70%{
    opacity: 1;
    transform: rotatex(-20deg) rotateY(-180deg) scale(0.4) translateX(-10vw) translateY(-10vh)
  }
  71%, 100%{
  opacity: 0.2; 
  }
  100%{
    opacity: 1;
    transform: rotatex(0deg) rotateY(0deg) scale(1) translateX(0) translateY(0)
  }
}

#about #first
{
  position: relative;
  letter-spacing: 2px;
  animation: opacityFirst 4s 1
}

@keyframes opacityFirst {
  0%{
    opacity: 0;
  }
  100%{
    opacity: 0;
  }
}

#about #first::before{
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  animation: firstP 1s 1 steps(6, end);
  animation-delay: 4s;
}

@keyframes firstP {
  0%{
    background-color: black;
    width: 100%;
    left: 0;
  }
  100%{
    background-color: black;
    width: 0%;
    left: 100%;
  }
}

#about #secound{
  position: relative;
  letter-spacing: 4px;
  animation: opacitySecound 5s 1
}

@keyframes opacitySecound {
  0%{
    opacity: 0;
  }
  100%{
    opacity: 0;
  }
}

#about #secound::before{
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  animation: thirthh2 2s 1 steps(11, end);
  animation-delay: 5s;
}

@keyframes thirthh2 {
  0%{
    background-color: black;
    width: 100%;
    left: 0;
  }
  100%{
    background-color: black;
    width: 0%;
    left: 100%;
  }
}

#about #thirth{
  position: relative;
  letter-spacing: 5px;
  animation: opacityThirth 7s 1
}

@keyframes opacityThirth {
  0%{
    opacity: 0;
  }
  100%{
    opacity: 0;
  }
}

#about #thirth::before{
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  animation: thirthH2 3s 1 steps(19, end);
  animation-delay: 7s;
}

@keyframes thirthH2 {
  0%{
    background-color: black;
    width: 100%;
    left: 0;
  }
  100%{
    background-color: black;
    width: 0%;
    left: 100%;
  }
}

#about #fourth{
  position: relative;
  letter-spacing: 2px;
  animation: opacityFourth 10s 1
}

@keyframes opacityFourth {
  0%{
    opacity: 0;
  }
  100%{
    opacity: 0;
  }
}

#about #fourth::before{
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  animation: fourthP 4s 1 steps(28, end);
  animation-delay: 10s;
}

@keyframes fourthP {
  0%{
    background-color: black;
    width: 100%;
    left: 0;
  }
  100%{
    background-color: black;
    width: 0%;
    left: 100%;
  }
}

#about #fiveth{
  position: relative;
  letter-spacing: 2px;
  animation: opacityFiveth 14s 1
}

@keyframes opacityFiveth {
  0%{
    opacity: 0;
  }
  100%{
    opacity: 0;
  }
}

#about #fiveth::before{
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  animation: fourthP 4s 1 steps(28, end);
  animation-delay: 14s;
}

@keyframes fivethhP {
  0%{
    background-color: black;
    width: 100%;
    left: 0;
  }
  100%{
    background-color: black;
    width: 0%;
    left: 100%;
  }
}


#about #sixth{
  position: relative;
  letter-spacing: 2px;
  animation: opacitySixth 18s 1;
}

@keyframes opacitySixth {
  0%{
    opacity: 0;
  }
  100%{
    opacity: 0;
  }
}

#about #sixth::before{
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  animation: sixthP 3s 1 steps(20, end);
  animation-delay: 18s;
}

@keyframes sixthP {
  0%{
    background-color: black;
    width: 100%;
    left: 0;
  }
  100%{
    background-color: black;
    width: 0%;
    left: 100%;
  }
}

#about #sixth::after{
  content: '';
  position: absolute;
  top: 10px;
  left: 0;
  width: 0%;
  height: 100%;
  animation: lighter 2s infinite linear alternate-reverse;
  animation-delay: 23.5s;
}

@keyframes lighter {
  0%{
    border-bottom: 3px solid red;
    width: 0%;
    left: 0px;
  }
  50%, 100%{
    border-bottom: 3px solid red;
    width: 100%;
    left: 0px;
  }
}

#codePhp{
  animation: opacityCode 22s 1;
}

#code{
  animation: opacityCode 22.5s 1;
}

#codeJs{
  animation: opacityCode 23s 1;
}


@keyframes opacityCode {
  0%{
    opacity: 0;
  }
  100%{
    opacity: 0;
  }
}
</style>
