<script setup>
import TheWelcome from "../components/TheWelcome.vue";
</script>

<template>
  <main>
  <div class="svg-wrap">
    <svg preserveAspectRatio="none" width="375" height="284" viewBox="0 0 375 284" fill="none" xmlns="http://www.w3.org/2000/svg">
    <path fill-rule="evenodd" clip-rule="evenodd" d="M0 229.276L18.5191 241.701C36.3996 254.126 72.7992 278.976 109.199 276.905C146.237 274.834 182.637 245.842 219.036 247.913C255.436 249.984 298.86 279.8 335.259 283.941C381.657 285.85 374.619 240.538 374.619 240.538L373.675 192C337.275 192 364.635 192 328.235 192C291.835 192 255.436 192 219.036 192C182.637 192 146.237 192 109.199 192C72.7992 192 36.3996 192 18.5191 192H0V229.276Z" fill="#FDCFEF"/>
    <path fill-rule="evenodd" clip-rule="evenodd" d="M0 257.773C23.1667 252.734 35.8333 232.313 59 222.235C82.1666 212.157 105.333 212.157 128.5 220.555C151.667 228.954 174.833 245.751 198 255.829C221.167 265.908 244.333 269.267 267.5 267.588C290.667 265.908 308.333 253.094 331.5 246.376C354.667 239.657 375 243.526 375 243.526V230.704V217.882V211.471V205.06V192.237C343 192.237 363.417 192.237 375 192.237C351.833 192.237 360.167 192 337 192C313.833 192 290.667 192 267.5 192C244.333 192 221.167 192 198 192C174.833 192 151.667 192 128.5 192C105.333 192 82.1666 192 59 192C35.8333 192 23.1667 192 0 192V257.773Z" fill="#79649E"/>
    <path d="M0 0H375V214H0V0Z" fill="#79649E"/>
    </svg>
  </div>

    <div class="title">
      <h1 class="first">Anny's</h1>
      <h1 class="second"> Flowers</h1>
    </div>

    <!-- end of header here -->

    <a class="intro-wrapper">
      <div class="wrapper-1">
        <!-- text img -->
        <h2 class="h2-1">Handpicked just for you </h2>
        <div class="image-center-1">
          <div class=" squircle img-wrapper-1"> <img src="src\assets\num8.JPG" alt=""> </div>
        </div>
      </div>

      <div class="wrapper-2">
        <!-- img text -->
        <div class="image-center-2">
          <div class=" squircle img-wrapper-2"><img src="src\assets\num8.JPG" alt=""> </div>
        </div>
        <h2 class="h2-2">To say I Love You </h2>
      </div>
    </a>

    <!-- end of 2 image text combos here -->

    <div class="svg-wrap">
      <svg width="375" height="284" viewBox="0 0 375 284" fill="none" xmlns="http://www.w3.org/2000/svg">
<path fill-rule="evenodd" clip-rule="evenodd" d="M0 54.7245L18.5191 42.2993C36.3996 29.8741 72.7992 5.02382 109.199 7.09468C146.237 9.16554 182.637 38.1576 219.036 36.0867C255.436 34.0159 298.86 4.20039 335.259 0.0586639C381.657 -1.85015 374.619 43.462 374.619 43.462L373.675 92C337.275 92 364.635 92 328.235 92C291.835 92 255.436 92 219.036 92C182.637 92 146.237 92 109.199 92C72.7992 92 36.3996 92 18.5191 92H0V54.7245Z" fill="#FDCFEF"/>
<path fill-rule="evenodd" clip-rule="evenodd" d="M0 26.227C23.1667 31.2661 35.8333 51.6866 59 61.765C82.1666 71.8433 105.333 71.8433 128.5 63.4447C151.667 55.0461 174.833 38.2489 198 28.1705C221.167 18.0922 244.333 14.7327 267.5 16.4125C290.667 18.0922 308.333 30.9056 331.5 37.6245C354.667 44.3434 375 40.4738 375 40.4738V53.296V66.1182V72.5293V78.9404V91.7626C343 91.7626 363.417 91.7626 375 91.7626C351.833 91.7626 360.167 92 337 92C313.833 92 290.667 92 267.5 92C244.333 92 221.167 92 198 92C174.833 92 151.667 92 128.5 92C105.333 92 82.1666 92 59 92C35.8333 92 23.1667 92 0 92V26.227Z" fill="#79649E"/>
<path d="M0 247C0 267.435 16.5655 284 37 284H338C358.435 284 375 267.435 375 247V70H0V247Z" fill="#79649E"/>
</svg>

    </div>
  </main>
</template>

<style>
:root {
  --font-1: 'Roboto', sans-serif;
  overflow-x: hidden;
}

/* site header/banner */
main, header {
  width: 99vw;
}
.title {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  width: 99vw;
  height: 20rem;
  position: relative;
  top: -31rem;
  font-size: 7vw;
  margin: 0;
  padding: 0;

  font-family: var(--font-1);
  font-weight: 900;
  color: rgb(43, 43, 43)

}

.first {
  right: 7rem;
}

.second {
  left: 5rem;
}

svg {
  width: 99vw;
  height: 100vh;
  bottom: 1rem;
  left: 0;
  margin: 0;
  z-index: -1;
  position: absolute;
}

.svg-wrap {
  width: 99vw;
  height: 80vh;
  position: relative;
  margin: 0;
  padding: 0;
  overflow: hidden;
  z-index: -1;
}


/* text + img combos here */

.squircle {
  position: relative;
  height: 17rem;
  width: 17rem;
  bottom: 2rem;
  border-radius: 24px;
}

.intro-wrapper {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  height: 120vh;
  width: 100%;
}

.wrapper-1 {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  width: 99vw;
  align-items: center;
}

.wrapper-2 {
  display: flex;
  width: 99vw;
justify-content: flex-end;
}

.img-wrapper-1 {
  width: 17rem;
  height: 17rem;
  object-fit: cover;
  display: grid;
  place-items: center;
}

.img-wrapper-2 {
  width: 17rem;
  height: 17rem;
  object-fit: cover;
}

img {
  width: 17rem;
  height: 17rem;
  border-radius: 24px;
  max-width: 100%;
  max-height: 100%;
}

.image-center-1 {
  display: flex;
  justify-content: flex-end;
  width: 100%;  
  height: 100%;
  padding-right: 2rem;
}

.image-center-2 {
  display: flex;
  justify-content: start;
  width: 100%;  
  height: 100%;
  padding-left: 2rem;
}

.h2-1 {
font-family: var(--font-1);
font-size: 3rem;
position: absolute;
bottom: 19rem;
right: 3rem;
text-align: left;
margin: 1rem;
padding-left: 1rem
}

.h2-2 {
font-family: var(--font-1);
font-size: 3rem;
position: absolute;
text-align: right;
bottom: 19rem;
left: 8rem;
margin: 2rem;
padding-right: 1rem;
}
/* 
@media (max-width: 576px) {

.title {
bottom: 31rem;
}
}

@media (min-width: 1000px) {

  .title {
    font-size: 4rem;
    bottom: 32rem;
  }
} */

</style>