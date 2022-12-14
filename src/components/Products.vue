<template>
    <div v-for="item in accessories">
    <img :src="item.image"/>
  {{ item.productName }} ,{{item.productPrice}}
</div>

</template>

<script>
export default {
    data() {
  return {
accessories:[
  {
    id: 1,
    productName: "Ankle-bands",
    productPrice: "R300",
    image:"https://i.postimg.cc/ncPXtHmh/ankle-band.webp",
  },
  {
    id: 2,
    productName: "Neck-piece",
    productPrice: "R600",
    image: "https://i.postimg.cc/T36kWRb2/bead-nacklace-removebg-preview.png",
  },
  {
    id: 3,
    productName: "Hair-band",
    productPrice: "R150",
      image:"https://i.postimg.cc/Y0XW2zQm/elisband-xhosa-removebg-preview.png",
  },
  {
    id: 4,
    productName: "Bag",
    productPrice: "R1000",
    image:
      "https://i.postimg.cc/GtRQTKB7/xhosa-bag-removebg-preview.png",
  },
  {
    id: 5,
    productName: "Earrings",
    productPrice: "R100",
    image:
      "https://i.postimg.cc/kgLhXxyZ/earings-removebg-preview.png",
  },
  {
    id: 6,
    productName: "Necklace",
    productPrice: "R400",
    image:
      "https://i.postimg.cc/nrL11zkB/necklace.jpg",
  },
  {
    id: 7,
    productName: "Hair-cloth",
    productPrice: "R500",
    image:
      "https://i.postimg.cc/7YmVbgq9/iqhiya-removebg-preview.png",
  },
  {
    id: 8,
    productName: "Hand-peice",
    productPrice: "R200",
    image:
      "https://i.postimg.cc/d37bX7x8/ring-removebg-preview.png",
  },
 
]
}
    }}
</script>
<style lang="">
    
</style>