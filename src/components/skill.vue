<template>
    <div class="skill__container">
  <b-card
    title="ポートフォリオ"
    img-src="https://picsum.photos/600/300/?image=25"
    img-alt="Image"
    img-top
    tag="article"
    style="max-width: 20rem;"
    class="mb-2"
  >
    <b-card-text>
      {{ title }}
    </b-card-text>

    <b-button href="#" variant="primary">Go somewhere</b-button>
  </b-card>
</div>
</template>
<script>
export default {
    name: "skill_container",
    data: {
        title: "このサイトです。"
    }
}
</script>

<style scoped>
.skill__container {
    margin: 20px 10px;
    width: 60%;
    height: 500px;
    margin-left: auto;
    margin-right: auto;
}
</style>