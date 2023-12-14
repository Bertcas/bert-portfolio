<style lang="sass" scoped>
.picture
  border-radius: 100px 29px 100px 29px
  width: 100%
  -webkit-filter: brightness(110%) contrast(110%) grayscale(100%)
  filter: brightness(110%) contrast(110%) grayscale(100%)
  height: 50vh
  object-fit: fill

.details
  font-weight: 700
  h3
    font-weight: 800
</style>

<template>
  <q-page padding class="flex flex-center q-pb-xl">
    <div :class="!Platform.is.mobile ? 'flex flex-center row items-center q-gutter-x-lg' : 'flex flex-center column items-center q-gutter-y-md'">
      <div class="col-4">
        <img :src="Picture" class="picture" />
      </div>
      <div :class="!Platform.is.mobile ? 'col-5 column details' : 'column details'">
        <h3>
          Bert
          <span>Casquejo</span>
        </h3>
        <div class="column">
          <span class="text-h6 text-weight-light">
            "As a seasoned UI/UX designer, I excel in crafting professional and intuitive user interfaces, employing a strategic blend of design aesthetics and user-centric functionality to elevate digital experiences."
          </span>
        </div>
      </div>
    </div>
  </q-page>
</template>

<script setup>
import { defineComponent } from 'vue';
import { Platform } from 'quasar';
import Picture from 'src/assets/bert.jpg'

defineComponent({
  name: 'IndexPage'
})
</script>
