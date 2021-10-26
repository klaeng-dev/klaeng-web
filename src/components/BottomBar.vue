<template>
  <div class="container-fluid backpanel">
    <div class="container left-info">
      <h5 class="bottom-bar-text"><b>Contact Us</b></h5>
      <h6 class="bottom-bar-text" id="email">info@klaengcambodia.com</h6>
      <h6 class="bottom-bar-text" id="phone">(+855) 77 69 37 76</h6>
      <a href="https://www.facebook.com/KlaengMarketingSolution"
        ><img
          src="../assets/fb_logo.png"
          id="fb-logo"
          width="24px"
          height="24px"
      /></a>
    </div>
    <div class="container right-info">
      <p class="slogan">With Us Your Brand Will Fly High Up Like A Kite</p>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.backpanel {
  display: flex;
  background-color: black;
  justify-content: space-between;
  padding: 30px 30px 70px 30px;
}
.left-info {
  flex-direction: column;
  display: flex;
  justify-content: flex-end;
  align-items: flex-start;
}
.right-info {
  flex-direction: row;
  display: flex;
  justify-content: flex-end;
  align-items: center;
}
.slogan {
  color: #686471;
}
.bottom-bar-text {
  color: white;
  font-family: "Poppins", sans-serif;
}
#fb-logo {
  margin: 20px 0px 0px 0px;
}
#phone {
  margin: 20px 0px 0px 0px;
}
#email {
  margin: 20px 0px 0px 0px;
}
</style>