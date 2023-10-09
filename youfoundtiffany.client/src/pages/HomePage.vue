<template>
  <div class="container">
    <section class="row">
      <div class="main">
        <div class="col-6 border">
          <div class="inner-cutout">
            <h1 class="knockout font-PlayfairDis">Hi, I'm Tiffany</h1>
          </div>
        </div>
      </div>
      <div class="col-6">
      </div>
    </section>
  </div>
</template>

<script>
export default {
  setup() {
    return {}
  }
}
</script>

<style scoped lang="scss">
// STUB ANIMATED TEXT GRADIENT


.border {
  padding: 5px;
  background: linear-gradient(110deg, var(--Goldenrod) 33%, rgba(0, 0, 0, 0) 33%), linear-gradient(110deg, var(--SkyMist) 34%, var(--DeepCerulean) 34%);
  background-size: 400% 400%;

  background-position: 25% 50%;
  -webkit-animation: Gradient 15s ease infinite;
  -moz-animation: Gradient 5s ease infinite;
}

.inner-cutout {
  padding: 40px 0;
  display: block;
  background-color: var(--SunsetOrange);
  margin: 2%;
  padding-bottom: 40px;
  height: 300px;
  // background: radial-gradient(var(--SunsetOrange), #fcbe78);
  background-size: 300%;
  background-position: 50% 50%;

}

.knockout {
  vertical-align: middle;
  text-align: center;
  font-size: 50pt;
  background: linear-gradient(110deg, var(--Goldenrod) 33%, rgba(0, 0, 0, 0) 33%), linear-gradient(110deg, var(--SkyMist) 34%, var(--DeepCerulean) 34%);
  ;
  background-size: 200%;
  -webkit-text-fill-color: transparent;
  -webkit-background-clip: text;
}

.knockout {
  animation: Gradient 5s ease infinite;
  -webkit-animation: Gradient 15s ease infinite;
  -moz-animation: Gradient 5s ease infinite;
}

@-webkit-keyframes Gradient {
  0% {
    background-position: 30% 50%
  }

  50% {
    background-position: 25% 50%
  }

  100% {
    background-position: 30% 50%
  }

}

// .main {
// width: 500px;
// height: 800px;
// margin-left: 40%;
// margin-right: 40%;
// margin-top: 10%;
// }

// STUB ANIMATED TEXT GRADIENT
</style>
