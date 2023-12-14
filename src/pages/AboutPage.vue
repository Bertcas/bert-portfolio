<style lang="sass" scoped>
.picture
  width: 100%
  height: 500px
  object-fit: cover
  -webkit-filter: brightness(110%) contrast(110%) grayscale(100%)
  filter: brightness(110%) contrast(110%) grayscale(100%)

.q-mt-xl
  margin-top: 3em
</style>

<template>
  <q-page padding class="column q-gutter-y-lg q-pb-xl">
    <span class="text-h3 q-mt-xl text-weight-bold">About Me</span>
    <img src="src/assets/Group 17.jpg"  />

    <div class="column">
      <span class="text-h6 text-weight-bolder">Bert Casquejo</span>
      <span class="text-subtitle1">UI/UX DESIGN</span>
    </div>

    <q-separator />

    <span class="text-h6 text-weight-light text-grey-7">
      I’m an aspiring UI/UX Designer who follows user
centered design approach while making mobile
and web application. I enjoy turning complex
problem Into simple, beautiful and intuitive design.

My approach to good design is finding the right
balance os user empathy, usability, aesthetic, a
Keen business acumen and a deep understanding
of my users. 

    </span>

    <q-separator />

    <div class="row q-gutter-x-lg">
      <div class="column q-gutter-y-md">
        <div class="row q-gutter-x-md items-center">
          <span class="text-substitle text-weight-bold">UX Skills:</span>
          <span class="text-subtitle1 text-weight-light text-grey-7">User Research,Prototyping,Visual Design,
            User Personas,Wireframing
          </span>
        </div>
        <div class="row q-gutter-x-md items-center">
          <span class="text-substitle text-weight-bold">Tools:</span>
          <span class="text-subtitle1 text-weight-light text-grey-7">Figma,Adobe Photoshop,Canva,HTML/CSS</span>
        </div>
        <div class="row q-gutter-x-md items-center">
          <span class="text-substitle text-weight-bold">Personal Skills:</span>
          <span class="text-subtitle1 text-weight-light text-grey-7">Communication,Creativity,Teamwork,Learning,</span>
        </div>
        <div class="row q-gutter-x-md items-center">
          <span class="text-substitle text-weight-bold">Interest & Activities:</span>
          <span class="text-subtitle1 text-weight-light text-grey-7">Travel,Music,Camping,Computer games</span>
        </div>
        <div class="row q-gutter-x-md items-center">
          <span class="text-substitle text-weight-bold">Achievements:</span>
          <span class="text-subtitle1 text-weight-light text-grey-7">Creative Web design,NCII Computer systems servicing.Java Programming</span>
        </div>
      </div>

      <div class="column q-gutter-y-md">
        <div class="row q-gutter-x-md items-center">
          <span class="text-substitle text-weight-bold">Email:</span>
          <span class="text-subtitle1 text-weight-light text-grey-7">bert.casquejo.5@gmail.com</span>
        </div>
        <div class="row q-gutter-x-md items-center">
          <span class="text-substitle text-weight-bold">Phone:</span>
          <span class="text-subtitle1 text-weight-light text-grey-7">09205798371</span>
        </div>
        <div class="row q-gutter-x-md items-center">
          <span class="text-substitle text-weight-bold">Nationality:</span>
          <span class="text-subtitle1 text-weight-light text-grey-7">Filipino</span>
        </div>
        <div class="row q-gutter-x-md items-center">
          <span class="text-substitle text-weight-bold">Design Experience:</span>
          <span class="text-subtitle1 text-weight-light text-grey-7">4 month and counting intensive training course for
UX designers, specializing in UX process and 
methodology.</span>
        </div>
      </div>
    </div>
  </q-page>
</template>

<script >


export default {
  // name: 'PageName',
}
</script>
