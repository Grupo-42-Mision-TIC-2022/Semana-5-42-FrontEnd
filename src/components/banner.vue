<template>

  <v-carousel
  cycle
  hide-delimiter-background
  show-arrows-on-hover
>
  
    <v-carousel-item
      v-for="(item, i) in items"
      :key="i"
      :src="item.src"
      reverse-transition="fade-transition"
      transition="fade-transition"
    ></v-carousel-item>
  </v-carousel>
  

</template>

<script>
export default {
  data() {
    return {
      items: [
        {
          src: "https://i.postimg.cc/635DyjTG/1-1.png",
        },
        {
          src: "https://i.postimg.cc/x8B7p95K/1-2.jpg",
        },
        {
          src: "https://i.postimg.cc/2jtPSxYV/1-3.jpg",
        },
        {
          src: "https://i.postimg.cc/XYSmw7pW/1-4.jpg",
        },
      ],
    };
  },
};
</script>