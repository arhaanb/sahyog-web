<template>
  <div class="container">
    <div class="product" style="margin-top: 1em;">
      <div class="six columns prodtext">
        <h2 class="semi">Product</h2>
        <p>
          Founded in 2020, Sahyog started life as an idea to not only change the
          way the healthcare system works, but also consolidate all the
          hospitals in the nearby areas and their equipment to make management
          and governing the system easier. Mainly a mobile app, Sahyog allows
          hospitals to work together and share resources during this pandemic.
        </p>
        <a href="/sahyog.apk" target="_blank">
          <button class="cool">Download</button>
        </a>
      </div>
      <div class="six columns">
        <img draggable="false" src="../assets/mockup.svg" alt />
      </div>
    </div>

    <div class="u-cf"></div>

    <div class="product">
      <div class="six columns">
        <img src="@/assets/illustration2.svg" alt />
      </div>
      <div class="six columns prodtext">
        <h2 class="semi">Dashboard</h2>
        <p>
          Our web app modernises the way our health industry operates, and aims
          to provide a more fast-tracked and elegant solution to the chaos of
          hospitals. Integrated with a real time feedback and update, we ensure
          that no hospital has to suffer due to not having enough resources. A
          quick and easy scan through your personal dashboard gives our users
          all the necessary information, and also grants the ability to make
          requests when in need.
        </p>
        <a href="//arhaanb.co/sahyog/app" target="_blank">
          <button class="cool">dashboard</button>
        </a>
      </div>
    </div>

    <div class="u-cf"></div>

    <div class="product">
      <div class="six columns worktext">
        <h2 class="semi">How we work</h2>
        <p>
          Hospitals can register at our website after creating their account the
          can upload the list of all their equpment that they have on the
          dashboard, they can further contact other hospitals for the equipments
          required by them.
        </p>
        <a href="https://siddhayak.co/sahyog" target="_blank">
          <button class="cool">Branding</button>
        </a>
      </div>
      <div class="six columns">
        <img src="../assets/logo.svg" draggable="false" alt />
      </div>
    </div>

    <div class="u-cf"></div>

    <br />
    <br />
    <br />

    <div class="vidpen">
      <div>
        <iframe
          width="100%"
          src="https://www.youtube.com/embed/"
          frameborder="0"
          allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture"
          allowfullscreen
          class="video"
        ></iframe>
      </div>
    </div>

    <br />
    <br />
    <br />
  </div>
</template>

<style scoped>
.product h2 {
  margin: 0;
}

.vidpen {
  position: relative;
  width: 100%;
  height: 0;
  padding-bottom: 56.25%;
}

.video {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}

.prodtext {
  margin-top: 4em;
}

.worktext {
  margin-top: 7em;
}
</style>
