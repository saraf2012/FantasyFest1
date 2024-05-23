<template>
  <section class="characters-container-wrapper">
    <div class="characters-container">
      <h3 class="meet-our-characters">meet our characters</h3>
      <div class="character-container">
        <div class="character" v-for="index in 3" :key="index">
          <div class="character-elements">
            <img
              class="polygon-icon"
              loading="lazy"
              :src="index === 1 ? LeftTriangle : RightTriangle"
              v-if="index !== 2"
            />
            <div class="ellipse-div" v-else></div>
          </div>
          <div class="character-details">
            <div class="name">Name</div>
            <div class="description">
              ddfsfsewfewfnwenfwfnjnfengkbdkgdgdkjgjdgjdjgdjkgbdjkjkngkjdfkfgjkwuie
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import { defineComponent } from "vue";
import LeftTriangle from "@/assets/LeftTriangle.svg";
import RightTriangle from "@/assets/RightTriangle.svg";

export default defineComponent({
  name: "FourthScreen",
  setup() {
    return {
      LeftTriangle,
      RightTriangle
    };
  }
});
</script>

<style>

</style>
