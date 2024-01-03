<template>
  <section class="galaxyBlur">
    <section class="galaxy">
      <section class="row justify-content-center border-ultra-violet m-0">
        <!-- POLOROID  DIV -->
        <div class="poloCard ">
          <div class="row justify-content-center">
            <div class="" id="popSound">
              <!-- onclick="mineCheese()" -->
              <img :src="tiffpic" alt="" class="btn-bubble bubble">
            </div>
          </div>
        </div>
        <!-- POLOROID  DIV -->
      </section>
    </section>
  </section>



  <!-- <div class="main">
        <div class="col-6 border">
          <div class="inner-cutout">
            <h1 class="knockout font-PlayfairDis">Hi, I'm Tiffany</h1>
          </div>
        </div>
      </div> -->
  <!-- <div class="col-6">
      </div> -->
  <!-- Section Above the Fold (Two columns) -->
  <section class="container bg-DeepCeruleanOpac50 txt-MidnightNavy rounded my-3 py-3 ">
    <div class="row">
      <h2>Above the fold</h2>
      <div class="col-12 col-md-6">
        <h2>ATF - Column 1</h2>
        <p>Content for ATF - Column 1</p>
      </div>
      <div class="col-12 col-md-6">
        <h2>ATF - Column 2</h2>
        <p>Content for ATF - Column 2</p>
      </div>
    </div>
  </section>

  <section class="container txt-MidnightNavy my-3 py-3">
    <div class="row">
      <div class="col">
        <h1>Education</h1>
        <p>Content for Section 1</p>
      </div>
    </div>
  </section>

  <!-- Section 2 (Two columns) -->
  <section class="container bg-DeepCeruleanOpac50 txt-MidnightNavy rounded my-3 py-3">
    <div class="row">
      <h2>Skills</h2>
      <div class="col-12 col-md-6">
        <h2>Section 2 - Column 1</h2>
        <p>Content for Section 2 - Column 1</p>
      </div>
      <div class="col-12 col-md-6">
        <h2>Section 2 - Column 2</h2>
        <p>Content for Section 2 - Column 2</p>
      </div>
    </div>
  </section>

  <!-- Section 3 -->
  <section class="container txt-MidnightNavy my-3 py-3">
    <div class="row">
      <div class="col">
        <h1>Experience</h1>
        <p>Content for Section 3</p>
      </div>
    </div>
  </section>

  <!-- Section 4 (Two columns) -->
  <section class="container bg-DeepCeruleanOpac50 txt-MidnightNavy rounded my-3 py-3">
    <div class="row">
      <h2>Profiles</h2>
      <div class="col-12 col-md-6">
        <h2>Section 4 - Column 1</h2>
        <p>Content for Section 4 - Column 1</p>
      </div>
      <div class="col-12 col-md-6">
        <h2>Section 4 - Column 2</h2>
        <p>Content for Section 4 - Column 2</p>
      </div>
    </div>
  </section>

  <!-- Section 5 -->
  <section class="container txt-MidnightNavy my-3 py-3">
    <div class="row">
      <div class="col">
        <h1>Clients</h1>
        <p>Content for Section 5</p>
      </div>
    </div>
  </section>

  <!-- Section 6 (Two columns) -->
  <section class="container bg-DeepCeruleanOpac50 txt-MidnightNavy rounded my-3 py-3">
    <div class="row">
      <h1>Portfolio</h1>
      <div class="col-12 col-md-6">
        <h2>Section 6 - Column 1</h2>
        <p>Content for Section 6 - Column 1</p>
      </div>
      <div class="col-12 col-md-6">
        <h2>Section 6 - Column 2</h2>
        <p>Content for Section 6 - Column 2</p>
      </div>
    </div>
  </section>

  <!-- Section 7 -->
  <section class="container txt-MidnightNavy my-3 py-3">
    <h1>Contact Us</h1>
    <p>Use this form to get in touch with us.</p>

    <form action="process_form.php" method="POST">
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" required><br><br>

      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required><br><br>

      <label for="message">Message:</label><br>
      <textarea id="message" name="message" rows="4" required></textarea><br><br>

      <input type="submit" value="Submit">
    </form>
  </section>
</template>

<script>
import tiffpic from '../assets/img/tiffpoloroidpurplebg.png'
export default {
  setup() {
    return {
      tiffpic,
    }
  },

}
</script>

<style scoped lang="scss">
.poloCard {
  height: 52vh;
}

// STUB ANIMATED TEXT GRADIENT
// .border {
//   padding: 5px;
//   background: linear-gradient(110deg, var(--Goldenrod) 33%, rgba(0, 0, 0, 0) 33%), linear-gradient(110deg, var(--SkyMist) 34%, var(--DeepCerulean) 34%);
//   background-size: 400% 400%;

//   background-position: 25% 50%;
// -webkit-animation: Gradient 15s ease infinite;
// -moz-animation: Gradient 5s ease infinite;
// }

// .inner-cutout {
// padding: 40px 0;
// display: block;
// background-color: var(--SunsetOrange);
// margin: 2%;
// padding-bottom: 40px;
// height: 300px;
// background: radial-gradient(var(--SunsetOrange), #fcbe78);
// background-size: 300%;
// background-position: 50% 50%;

// }

// .knockout {
// vertical-align: middle;
// text-align: center;
// font-size: 50pt;
// background: linear-gradient(110deg, var(--Goldenrod) 33%, rgba(0, 0, 0, 0) 33%), linear-gradient(110deg, var(--SkyMist) 34%, var(--DeepCerulean) 34%);
// ;
// background-size: 200%;
// -webkit-text-fill-color: transparent;
// -webkit-background-clip: text;
// }

// .knockout {
//   animation: Gradient 5s ease infinite;
//   -webkit-animation: Gradient 15s ease infinite;
//   -moz-animation: Gradient 5s ease infinite;
// }

// @-webkit-keyframes Gradient {
//   0% {
//     background-position: 30% 50%
//   }

//   50% {
//     background-position: 25% 50%
//   }

//   100% {
//     background-position: 30% 50%
//   }

// }

// .main {
// width: 500px;
// height: 800px;
// margin-left: 40%;
// margin-right: 40%;
// margin-top: 10%;
// }

// STUB ANIMATED TEXT GRADIENT
</style>
