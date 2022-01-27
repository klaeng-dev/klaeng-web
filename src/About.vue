<template>
  <div class="container">
    <h1 class="text top-bar"><b>About us</b></h1>
    <span class="text"
      ><h3>
        <b>Klaeng Marketing Solutions</b> is a digital marketing firm in
        Cambodia that specializes in digital marketing.
      </h3></span
    >
    <h4 class="text title"><b>Vision</b></h4>
    <span class="text"
      ><h6>
        To be a leading digital marketing firm in Cambodia that focuses on
        social media management and marketing campaigns.
      </h6></span
    >
    <h4 class="text title"><b>Missions</b></h4>
    <ul>
      <li>To provide the best quality service that suits customers’ needs</li>
      <li>
        To consult with customers in building their brand images and brand
        awareness
      </li>
      <li>
        To provide the most creative and innovative ideas for clients’ marketing
        plan
      </li>
    </ul>
    <h4 class="text title"><b>Values</b></h4>
    <ul id="last-list">
      <li>
        <span>Quality</span> - we aims to deliver the best quality services
      </li>
      <li>
        <span>Customer’s satisfaction</span> - is our priority
      </li>
      <li>
        <span> Brands’ image</span> - we deliver and consult with our clients to
        deliver the image they want
      </li>
      <li>
        <span> Brands’ awareness</span> - focuses on highest reaches and
        awareness in the largest market
      </li>
      <li>
        <span>Sales Generation</span>
        - we help our clients generate more sales
      </li>
    </ul>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.container {
  display: flex;
  flex-direction: column;
}
.text {
  color: #000000;
}
.top-bar {
  margin-top: 50px;
}
.title {
  margin-top: 40px;
}
.description {
    margin-top: 20px
}
ul {
  margin: auto;
}
li {
  text-align: left;
  font-weight: normal;
}
li > span {
  text-align: left;
  font-weight: bold;
}
#last-list {
    margin-bottom: 100px;
}
</style>