<template>
  <div class="first">
    <p>tomroodnat.com</p>
  </div>
  <div class="second">
    <h4>info@tomroodnat.com</h4>
  </div>
</template>

<script>
export default {
  name: 'App',
  components: {}
}
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.first {
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  font-family: "Libre Barcode 39 Extended", cursive;
  color: #7d9cb6;
  background-color: #223f57;
}

.second {
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  font-family: "Muli", sans-serif;
  background-color: #315b7d;
  color: #7d9cb6;
  letter-spacing: 0.3em;
}
</style>
