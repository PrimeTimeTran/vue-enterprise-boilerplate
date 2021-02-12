<template>
  <div :class="$style.container">
    <div :class="$style.sidebar">Left</div>
    <div :class="$style.main"><slot /></div>
    <div :class="$style.info">Left</div>
  </div>
</template>

<style lang="scss" module>
@import '@design';

.container {
  display: flex;
  height: 100vh;
  margin: 0 auto;
}

.sidebar {
  flex: 2;
  background-color: red;
}

.main {
  flex: 7;
  background-color: orange;
}

.info {
  flex: 2;
  background-color: blue;
}
</style>
