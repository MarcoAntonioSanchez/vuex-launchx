<template>
    <div class="counter">
      {{ $store.state.contador }}
    </div>
</template>

<script>
import Contador from "../components/Contador.vue";

export default {
  name: 'Contador',
}
</script>