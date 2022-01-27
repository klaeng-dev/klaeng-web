
<template>
  <div class="container">
    <h1 class="title">
      <b>To Build Up Your Brands, We Can Help You With</b>
    </h1>
    <div id="services-container" class="container">
      <div class="row">
        <div class="col-sm-6" v-for="service in services" :key="service.id">
          <ServicePart :service="service" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import ServicePart from "./components/ServicePart";

export default {
  components: {
    ServicePart,
  },
  data() {
    return {
      service: {
        id: 1,
        icon: "megaphone.png",
        title: "Social Media Management",
        description: "We manage",
      },
      services: [
        {
          id: 1,
          icon: "megaphone.png",
          title: "Social Media Management",
          description:
            "We manage your social media platforms and help your brand appear to target customers.",
        },
        {
          id: 2,
          icon: "megaphone.png",
          title: "Content Marketing",
          description:
            "We have the team with creative marketing concepts and we ensure that our design visuals are appealing to your target customers.",
        },
        {
          id: 3,
          icon: "megaphone.png",
          title: "Marketing Campaign",
          description:
            "We offer marketing consultancy service and propose marketing campaigns.",
        },
        {
          icon: "megaphone.png",
          title: "Media Buying",
          description: "We ensure cost-effectiveness of your ads.",
        },
      ],
    };
  },
};
</script>

<style scoped>
.title {
  margin-top: 60px;
}
#services-container {
  margin: 80px 0px;
}
</style>