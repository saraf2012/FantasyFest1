<template>
    <div class="faq-container">
      <div class="faq-title">
        <h3 class="faq1">FAQ</h3>
      </div>
      <div class="faq-top-decorations">
        <div class="top-decoration1" />
        <div class="top-decoration2" />
      </div>
      <div class="faq-content">
        <div class="faq-top-border">
          <div class="delusive-vortex" />
          <div class="top-border-decoration" />
        </div>
        <div class="faq-input">
          <div class="faq-input-wrapper">
            <div class="faq-input-description-parent">
              <div class="faq-input-description">
                <div class="couldnt-find-the">
                  Couldn’t find the answer? Write it below
                </div>
              </div>
              <textarea class="textarea" rows="16" cols="34"></textarea>
            </div>
            <div class="send-button-wrapper-wrapper">
              <div class="send-button-wrapper">
                <button class="send-button-label">
                  <div class="send-button-label-child"></div>
                  <div class="send">Send</div>
                </button>
                <img
                  class="send-button-wrapper-child"
                  alt=""
                  :src="sendButtonChildSvg"
                />
                <img
                  class="send-button-wrapper-item"
                  alt=""
                  :src="sendButtonItemSvg"
                />
              </div>
            </div>
          </div>
          <img
            class="theme-logo"
            loading="lazy"
            alt=""
            :src="themeLogoSvg"
          />
        </div>
      </div>
    </div>
  </template>
  
  <script>
  import { defineComponent } from "vue";
  import sendButtonChildSvg from "@/assets/arrowspecialright.svg";
  import sendButtonItemSvg from "@/assets/arrowspecialright1.svg";
  import themeLogoSvg from "@/assets/Portal.png";
  
  export default defineComponent({
    name: "SixthScreen",
    data() {
      return {
        sendButtonChildSvg,
        sendButtonItemSvg,
        themeLogoSvg
      };
    }
  });
  </script>
  
  <style>
  /* Add your styles here */
  </style>
  