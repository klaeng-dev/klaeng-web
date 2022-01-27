<template>
  <div>
    <div class="icon-container container">
      <img :src="require(`../assets/${service.icon}`)" class="img-fluid" />
      <h3 id="title">
        <b>{{ service.title }}</b>
      </h3>
      <h5 id="description">{{ service.description }}</h5>
    </div>
  </div>
</template>

<script>
export default {
  name: "ServicePart",
  props: ["service"],
};
</script>

<style scoped>
img {
  width: 20%;
  height: 20%;
}
.icon-container {
  position: relative;
  padding-bottom: 50px;
}

#title {
  margin-top: 20px;
}

#description {
  margin-top: 10px;
}
</style>