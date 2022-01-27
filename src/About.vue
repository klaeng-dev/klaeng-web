<template>
  <div class="container">
    <h1 class="text top-bar"><b>About us</b></h1>
    <span class="text description"
      ><h3>
        <b>Klaeng Marketing Solutions</b> is a digital marketing firm in
        Cambodia that specializes in digital marketing.
      </h3></span
    >
    <h1 class="text title"><b>Vision</b></h1>
    <span class="text description"
      ><h3>
        To be a leading digital marketing firm in Cambodia that focuses on
        social media management and marketing campaigns.
      </h3></span
    >
    <h1 class="text title"><b>Missions</b></h1>
    <ul class="description">
      <li>
        <h3>To provide the best quality service that suits customers’ needs</h3>
      </li>
      <li>
        <h3>
          To consult with customers in building their brand images and brand
          awareness
        </h3>
      </li>
      <li>
        <h3>
          To provide the most creative and innovative ideas for clients’
          marketing plan
        </h3>
      </li>
    </ul>
    <h1 class="text title"><b>Values</b></h1>
    <ul id="last-list" class="description">
      <li>
        <h3><b>Quality</b> - we aims to deliver the best quality services</h3>
      </li>
      <li>
        <h3><b>Customer’s satisfaction</b> - is our priority</h3>
      </li>
      <li>
        <h3>
          <b> Brands’ image</b> - we deliver and consult with our clients to
          deliver the image they want
        </h3>
      </li>
      <li>
        <h3>
          <b> Brands’ awareness</b> - focuses on highest reaches and awareness
          in the largest market
        </h3>
      </li>
      <li>
        <h3>
          <b>Sales Generation</b>
          - we help our clients generate more sales
        </h3>
      </li>
    </ul>
  </div>
</template>

<style scoped>
.container {
  display: flex;
  flex-direction: column;
}
.text {
  color: #000000;
}
.top-bar {
  margin-top: 60px;
}
.title {
  margin-top: 50px;
}
.description {
  margin-top: 20px;
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