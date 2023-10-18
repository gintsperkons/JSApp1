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
    <div id="nav" v-if="store.login">
        <button>Home</button>
        <button>About Me</button>
    </div>
</template>


<style>
#nav {
    width: 25%;
    display: flex;
    flex-direction: column;
    margin:10px;
}

</style>
