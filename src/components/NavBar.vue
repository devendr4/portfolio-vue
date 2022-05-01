<template>
  <nav>
    <ul>
      <li><a>home</a></li>
      <li><a>about</a></li>
      <li><a>contact</a></li>
    </ul>
  </nav>
</template>
<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "NavBar",
});
</script>

<style scoped lang="scss">
nav {
  width: 100vw;
}

ul {
  display: flex;
  height: 3rem;
  align-items: center;
  background-color: red;
  justify-content: space-around;
}
li {
  list-style-type: none;
}
</style>
