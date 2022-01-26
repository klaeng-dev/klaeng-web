<template>
  <div class="main-container">
    <div class="background-image-container">
      <img
        id="background-image"
        src="./assets/cloud_background.png"
        width="100%"
        height="100%"
      />
      <div class="title-block">
        <h2 id="title">
          GLIDE HIGHER <br />
          WITH US
        </h2>
      </div>
    </div>
    <h4 id="intro-text">
      <b>Klaeng Marketing Solutions</b> is a digital marketing firm in Cambodia
      which specializes in digital marketing.
    </h4>
    <div id="proposal-button">
      <a href="cloud_background.png" download="testDoc.pdf"
        ><h4 class="rouned-corner">GET A FREE PROPOSAL</h4></a
      >
    </div>
    <h3 id="track_records_title">Our Track Records</h3>
    <div>
      <img
        class="record-logo"
        v-for="image in imageList"
        :key="image"
        :src="require(`./assets/${image}`)"
      />
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      imageList: [
        "leng.png",
        "ize_cola.png",
        "carlsberg.png",
        "kamu.png",
        "legend.png",
        "nextlevel.png",
        "sting.png",
        "misterbrew.png",
        "mirinda.png",
      ],
    };
  },
};
</script>

<style scoped>
.main-container {
  position: relative;
  text-align: center;
  margin-top: 30px;
}

.background-image-container {
  position: relative;
}

.background-image {
  position: relative;
}

.title-block {
  position: absolute;
  top: 35%;
  left: 60px;
}

#title {
  font-weight: bold;
}

#intro-text {
  margin: 30px;
}

a {
  text-decoration: none;
}

.rouned-corner {
  align-items: center;
  border-radius: 25px;
  border: 2px solid #655798;
  padding: 20px;
  color: #655798;
  width: 400px;
  margin: auto;
  font-weight: bold;
}

#proposal-button {
  background-color: white;
  color: #655798;
  transition: 0.3s;
  margin: 30px;
}
#proposal-button :hover {
  background-color: #655798;
  cursor: pointer;
  color: white;
}

#track_records_title {
  margin: 40px 40px;
  color: #655798;
}

.record-logo {
  width: 170px;
  height: 150px;
  flex: 0 0 auto;
  margin: 20px 20px;
}
</style>