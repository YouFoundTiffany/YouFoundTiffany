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
          <!-- 🎠LANGUAGES CAROUSEL -->
          <div id="LangCarousel" class="carousel slide" data-ride="carousel">
            <!-- <ol class="carousel-indicators">
              <li data-target="#LangCarousel" data-slide-to="0" class="active"></li>
              <li data-target="#LangCarousel" data-slide-to="1"></li>
              <li data-target="#LangCarousel" data-slide-to="2"></li>
            </ol> -->
            <div class="carousel-inner">
              <div class="carousel-item active">
                <img class="d-block w-100 langIcons"
                  src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original-wordmark.svg" alt=" First
                slide">
              </div>
              <div class="carousel-item">
                <img class="d-block w-100 langIcons"
                  src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original-wordmark.svg"
                  alt="Second slide">
              </div>
              <div class="carousel-item">
                <img class="d-block w-100 langIcons"
                  src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original-wordmark.svg"
                  alt="Third slide">
              </div>
              <div class="carousel-item">
                <img class="d-block w-100 langIcons"
                  src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-original-wordmark.svg"
                  alt="Fourth slide">
              </div>
              <div class="carousel-item">
                <img class="d-block w-100 langIcons"
                  src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/canva/canva-original.svg" alt="Fifth slide">
              </div>
              <div class="carousel-item">
                <img class="d-block w-100 langIcons"
                  src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/figma/figma-original.svg" alt="Sixth slide">
              </div>
              <div class="carousel-item">
                <img class="d-block w-100 langIcons"
                  src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg"
                  alt="Seventh slide">
              </div>
              <div class="carousel-item">
                <img class="d-block w-100 langIcons"
                  src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-plain.svg"
                  alt="Eighth slide">
              </div>
              <div class="carousel-item">
                <img class="d-block w-100 langIcons"
                  src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/inkscape/inkscape-original.svg"
                  alt="Ninth slide">
              </div>
              <div class="carousel-item">
                <img class="d-block w-100 langIcons"
                  src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" alt="Tenth slide">
              </div>
              <div class="carousel-item">
                <img class="d-block w-100 langIcons"
                  src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-plain.svg" alt="Eleventh slide">
              </div>
              <div class="carousel-item">
                <img class="d-block w-100 langIcons"
                  src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/google/google-original.svg" alt="Twelth slide">
              </div>
              <div class="carousel-item">
                <img class="d-block w-100 langIcons"
                  src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original-wordmark.svg"
                  alt="Thirteenth slide">
              </div>
              <div class="carousel-item">
                <img class="d-block w-100 langIcons"
                  src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original-wordmark.svg"
                  alt="Fourteenth slide">
              </div>
              <div class="carousel-item">
                <img class="d-block w-100 langIcons"
                  src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original-wordmark.svg"
                  alt="Fifthteenth slide">
              </div>
              <div class="carousel-item">
                <img class="d-block w-100 langIcons"
                  src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original-wordmark.svg"
                  alt="Sixteenth slide">
              </div>
              <div class="carousel-item">
                <img class="d-block w-100 langIcons"
                  src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/photoshop/photoshop-plain.svg"
                  alt="Seventeenth slide">
              </div>
              <div class="carousel-item">
                <img class="d-block w-100 langIcons"
                  src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/trello/trello-plain-wordmark.svg"
                  alt="Eighteenth slide">
              </div>
              <div class="carousel-item">
                <img class="d-block w-100 langIcons"
                  src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vuejs/vuejs-original-wordmark.svg"
                  alt="Nineteenth slide">
              </div>
              <div class="carousel-item">
                <img class="d-block w-100 langIcons"
                  src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original-wordmark.svg"
                  alt="Twentieth slide">
              </div>
              <div class="carousel-item">
                <img class="d-block w-100 langIcons"
                  src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jira/jira-original-wordmark.svg"
                  alt="Twentyfirst slide">
              </div>
              <div class="carousel-item">
                <img class="d-block w-100 langIcons"
                  src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-original-wordmark.svg"
                  alt="Twentysenth slide">
              </div>
              <div class="carousel-item">
                <img class="d-block w-100 langIcons"
                  src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/gimp/gimp-original-wordmark.svg"
                  alt="Twentythird slide">
              </div>

            </div>
            <a class="carousel-control-prev" href="#LangCarousel" role="button" data-slide="prev">
              <span class="carousel-control-prev-icon" aria-hidden="true"></span>
              <span class="sr-only">Previous</span>
            </a>
            <a class="carousel-control-next" href="#LangCarousel" role="button" data-slide="next">
              <span class="carousel-control-next-icon" aria-hidden="true"></span>
              <span class="sr-only">Next</span>
            </a>
          </div>
          <!-- 🎠LANGUAGES CAROUSEL -->

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

<style scoped lang="scss">
.langIcons {
  max-height: 100px;
  max-width: 100%;
}
</style>
