<template>
  <header class="header">
    <ul class="nav justify-content-center">
      <li class="nav-item">
        <a class="nav-link" href="#">HOME</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">ABOUT</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">INFO</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">FAQ</a>
      </li>
    </ul>
  </header>
</template>

<script>
import { defineComponent } from "vue";

export default defineComponent({
  name: "FirstScreen",
});
</script>

<style scoped>
.header {
  width: 100%;
  padding: 20px 0;
}

.nav {
  display: flex;
  flex-direction: row;
  justify-content: center;
  gap: 1rem; /* Adjust the gap as needed */
}

.nav-link {
  font-size: 1.25rem;
  font-family: 'Sell Your Soul';
  text-transform: uppercase;

}
  
</style>
