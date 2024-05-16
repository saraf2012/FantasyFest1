<template>
    <div class="info-details">
      <div class="place-date-container">
        <div class="place-container-wrapper">
          <div class="place-container">
            <div class="place-elements-parent">
              <div class="place-elements">
                <div class="icbaseline-place-parent">
                  <img
                    class="icbaseline-place-icon"
                    loading="lazy"
                    alt=""
                    :src="locationSvg"
                  />
                  <div class="torvet-6700-esbjerg-danmark-wrapper">
                    <div class="torvet-6700-esbjerg">
                      Torvet, 6700 Esbjerg, Danmark
                    </div>
                  </div>
                </div>
                <div class="date-container">
                  <div class="date-icons-parent">
                    <div class="date-icons">
                      <img
                        class="uiwdate-icon"
                        loading="lazy"
                        alt=""
                        :src="calendarSvg"
                      />
                    </div>
                    <div class="month-container-parent">
                      <div class="month-container">
                        <img
                          class="mingcutetime-line-icon"
                          alt=""
                          :src="clockSvg"
                        />
                      </div>
                      <div class="setember-2024-wrapper">
                        <div class="setember-2024">14. setember 2024</div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div class="frame-container">
                <div class="mingcutetime-line-parent">
                  <img
                    class="mingcutetime-line-icon1"
                    alt=""
                    :src="clock1Svg"
                  />
                  <div class="wrapper1">
                    <div class="div2">18.00-22.30</div>
                  </div>
                </div>
              </div>
            </div>
            <div class="ticket-button-wrapper-wrapper">
              <div class="ticket-button-wrapper">
                <img
                  class="ticket-button-wrapper-child"
                  alt=""
                  :src="arrowSpecialRightSvg"
                />
                <button class="ticket-button-label">
                  <div class="ticket-button-label-child"></div>
                  <div class="buy-tickets1">Buy tickets</div>
                </button>
                <img
                  class="ticket-button-wrapper-item"
                  alt=""
                  :src="arrowSpecialRight1Svg"
                />
              </div>
            </div>
          </div>
        </div>
        <img
          class="esbjerg-1-icon"
          loading="lazy"
          alt=""
          :src="EsbjergmapSvg"
        />
      </div>
    </div>
  </template>
  
  <script>
  import { defineComponent } from "vue";
  import locationSvg from '@/assets/location.svg';
  import calendarSvg from '@/assets/calendar.svg';
  import clockSvg from '@/assets/clock.svg';
  import clock1Svg from '@/assets/clock1.svg';
  import arrowSpecialRightSvg from '@/assets/arrowspecialright.svg';
  import arrowSpecialRight1Svg from '@/assets/arrowspecialright1.svg';
  import EsbjergmapSvg from '@/assets/Esbjergmap.png';
  
  export default defineComponent({
    name: "FifthScreen",
    data() {
      return {
        locationSvg,
        calendarSvg,
        clockSvg,
        clock1Svg,
        arrowSpecialRightSvg,
        arrowSpecialRight1Svg,
        EsbjergmapSvg
      };
    }
  });
  </script>
  
  <style scoped>
  /* Add your scoped styles here */
  </style>
  