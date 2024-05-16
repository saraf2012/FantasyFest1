<template>
  <section class="characters-container-wrapper">
    <div class="characters-container">
      <div class="meet-our-characters-wrapper">
        <h3 class="meet-our-characters">meet our characters</h3>
      </div>
      <div class="character-one-container">
        <div class="character-one-elements-parent">
          <div class="character-one-elements">
            <div class="character-one-elements-inner">
              <img
                class="polygon-icon"
                loading="lazy"
                alt=""
                :src="LeftTriangle"
              />
            </div>
            <div class="div1"/>
          </div>
          <div class="character-one-details">
            <div class="character-one-name-container">
              <div class="name-wrapper">
                <div class="name">Name</div>
              </div>
              <div class="ddfsfsewfewfnwenfwfnjnfengkbdk">
                ddfsfsewfewfnwenfwfnjnfengkbdkgdgdkjgjdgjdjgdjkgbdjkjkngkjdfkfgjkwuie
              </div>
            </div>
          </div>
        </div>
        <div class="character-two-container">
          <div class="character-two-container-inner">
            <div class="ellipse-div" />
          </div>
          <div class="character-two-details">
            <div class="character-two-name-container">
              <div class="name1">Name</div>
            </div>
            <div class="ddfsfsewfewfnwenfwfnjnfengkbdk1">
              ddfsfsewfewfnwenfwfnjnfengkbdkgdgdkjgjdgjdjgdjkgbdjkjkngkjdfkfgjkwuie
            </div>
          </div>
        </div>
        <div class="character-three-container">
          <div class="character-three-elements-wrapper">
            <div class="character-three-elements">
              <div class="character-three-elements-child" />
              <div class="character-three-elements-inner">
                <img
                  class="frame-child1"
                  loading="lazy"
                  alt=""
                  :src="RightTriangle"
                />
              </div>
            </div>
          </div>
          <div class="character-three-details">
            <div class="character-three-name-container">
              <div class="name2">Name</div>
            </div>
            <div class="ddfsfsewfewfnwenfwfnjnfengkbdk2">
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

<style scoped>
/* Add your scoped styles here */
</style>
