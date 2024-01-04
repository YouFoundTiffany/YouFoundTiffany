<template>
  <!-- 📸 POLOROID  DIV -->
  <div class="galaxy m-0 p-0">
    <img :src="tiffpic" alt="" class="poloroid">
  </div>
  <!-- 📸 POLOROID  DIV -->



  <section class="bg-dark m-0 p-0">
    <!-- 🚀 spacer div -->
    <div style="height:5vh;"></div>
    <!-- 🚀 spacer div -->
    <!-- <section class="container bg-DeepCeruleanOpac50 txt-MidnightNavy rounded">
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
    </section> -->

    <section class="container txt-Passion my-3 py-3">
      <div class="row">
        <div class="col">
          <h1>Education</h1>
          <p>Content for Section 1</p>
        </div>
      </div>
    </section>

    <!-- Section 2 (Two columns) -->
    <section class="container bg-DeepCeruleanOpac50 txt-SunsetOrange rounded my-3 py-3">
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
    <section class="container txt-Jonquil my-3 py-3">
      <div class="row">
        <div class="col">
          <h1>Experience</h1>
          <p>Content for Section 3</p>
        </div>
      </div>
    </section>

    <!-- Section 4 (Two columns) -->
    <section class="container bg-DeepCeruleanOpac50 txt-Sea-Green rounded my-3 py-3">
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
    <section class="container txt-Moonstone my-3 py-3">
      <div class="row">
        <div class="col">
          <h1>Clients</h1>
          <p>Content for Section 5</p>
        </div>
      </div>
    </section>

    <!-- Section 6 (Two columns) -->
    <section class="container bg-DeepCeruleanOpac50 txt-SkyMist rounded my-3 py-3">
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
    <section class="container txt-Goldenrod my-3 py-3">
      <h1>Contact Me</h1>
      <p>Use this form to get in touch with me.</p>

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

<style scoped lang="scss"></style>
