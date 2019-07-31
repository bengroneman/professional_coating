<template>
  <div>
    <b-card
      :title="card_title"
      :img-src="image_src"
      img-alt="Image"
      img-top
      tag="article"
      style="max-width: 20rem;"
      class="mb-2"
    >
      <b-card-text>
        <slot></slot>
      </b-card-text>

      <b-button href="#" variant="primary">Go somewhere</b-button>
    </b-card>
  </div>
</template>
<script>
  export default {
      name: 'pservicecard',
      props: {
          image_src: String,
          card_title: String,
      },
  }
</script>
