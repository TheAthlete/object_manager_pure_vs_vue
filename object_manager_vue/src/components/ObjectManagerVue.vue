<template>
  <div class="object_manager">

    <yandex-map 
      :coords="[55.76, 37.64]"
      style="width: 600px; height: 600px;"
      zoom="10"
      :use-object-manager="true"
    >
    </yandex-map>
  </div>
</template>

<script>
import { yandexMap, ymapMarker } from 'vue-yandex-maps'

export default {
  name: 'HelloWorld',
  components: {
    yandexMap, 
    ymapMarker
  }
}
</script>
