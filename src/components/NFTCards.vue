<template>
  <div class="nft-cards">
    <NFTCard
      photo="images/image1.png"
      userphoto="images/person1.png"
      title="#410 Print art representing Richest children of Liberia"
      username="Mark Imo"
      timer="2 days"
      ethbid="10.50"
      usdbid="43,063.4"
    />
    <NFTCard
      photo="images/image2.png"
      userphoto="images/person2.png"
      title="#371 Textile art representing the school education system"
      username="Simon Ayodele"
      timer="2 weeks"
      ethbid="2.4"
      usdbid="14,321"
    />
    <NFTCard
      photo="images/image3.png"
      userphoto="images/person3.png"
      title="#021 Painting of the women who saved the girl from the beast"
      username="Chidinma Gideon"
      timer="2 days"
      ethbid="10.50"
      usdbid="43,063.4"
    />
    <NFTCard
      photo="images/image4.png"
      userphoto="images/person1.png"
      title="#212 Photograph for Model man in Banda, Guinea."
      username="Mark Imo"
      timer="2 weeks"
      ethbid="6.1"
      usdbid="21,321"
    />
  </div>
</template>

<style lang="scss" scoped>
.nft-cards {
  width: fit-content;
  background: rgba(217, 217, 217, 0.1);
  display: grid;
  padding: 0px 0px 0.94rem;
  column-gap: 3.25rem;
  row-gap: 6.87rem;
  grid-template-columns: 1fr 1fr;
}
</style>

<script>
import { defineComponent } from "vue";
import NFTCard from "@/components/NFTCard.vue";

export default defineComponent({
  name: "NFTCards",
  components: {
    NFTCard,
  },
});
</script>
