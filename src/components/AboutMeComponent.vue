<script>
import { store } from '../../src/store.js'
export default {
  data() {
    return {
      store
    }
  }
}
</script>

<template>
    <div id="about">
        <div class="top">About Me</div>
        <div class="tab">
            <p>name: {{ store.user.name }}<br>surname: {{ store.user.surname }}<br>code: {{ store.user.code }}</p>
        </div>
    </div>
</template>

<style>
#about {
    width: 75%;
}
.top {
    text-transform: uppercase;
}
</style>