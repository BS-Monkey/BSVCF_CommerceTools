<template>
  <Banner
    :title="title"
    :subtitle="subtitle"
    :description="description"
    :button-text="button_text"
    :link="button_link"
    :image="image.url"
    :background="background"
  />
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'Banner',
  props: {
    title: {
      type: String,
    },
    subtitle: {
      type: String,
    },
    description: {
      type: String,
    },
    button_text: {
      type: String,
    },
    button_link: {
      type: String,
    },
    image: {
      type: Object,
    },
    background: {
      type: String,
    },
  },
})
</script>