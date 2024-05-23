<template>
  <div class="info">
    <div class="details">
      <div class="location">
        <img class="icon" :src="locationSvg" alt="Location Icon" />
        <div class="text">Torvet, 6700 Esbjerg, Danmark</div>
      </div>
      <div class="date-time">
        <img class="icon" :src="calendarSvg" alt="Calendar Icon" />
        <div class="text">14. September 2024</div>
        <img class="icon" :src="clockSvg" alt="Clock Icon" />
        <div class="text">18.00-22.30</div>
      </div>
      <div class="ticket">
        <button class="btn">
          <img class="arrow" :src="arrowSpecialRightSvg" alt="Arrow Icon" />
          Buy tickets
          <img class="arrow" :src="arrowSpecialRight1Svg" alt="Arrow Icon" />
        </button>
      </div>
    </div>
    <img class="map" :src="EsbjergmapSvg" alt="Map of Esbjerg" />
  </div>
</template>

<script>
import { defineComponent } from "vue";
import locationSvg from '@/assets/location.svg';
import calendarSvg from '@/assets/calendar.svg';
import clockSvg from '@/assets/clock.svg';
import arrowSpecialRightSvg from '@/assets/arrowspecialright.svg';
import arrowSpecialRight1Svg from '@/assets/arrowspecialright1.svg';
import EsbjergmapSvg from '@/assets/Esbjergmap.png';

export default defineComponent({
  name: "EventInfo",
  data() {
    return {
      locationSvg,
      calendarSvg,
      clockSvg,
      arrowSpecialRightSvg,
      arrowSpecialRight1Svg,
      EsbjergmapSvg
    };
  }
});
</script>

<style>

</style>
