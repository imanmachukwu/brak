<template>
  <div id="main">
    <NFTCard
      photo="images/image5.png"
      userphoto="images/person1.png"
      title="#551 Photograph portrays “END RAPE” in  2019"
      username="Mark Imo"
      timer="1 day"
      ethbid="2.40"
      usdbid="11,003.4"
    />
    <NFTCard
      photo="images/image6.png"
      userphoto="images/person1.png"
      title="#410 Print art representing courage men of Liberia"
      username="Mark Imo"
      timer="2 days"
      ethbid="10.50"
      usdbid="43,063.4"
    />
    <NFTCard
      photo="images/image7.png"
      userphoto="images/person2.png"
      title="#290 Painting of the African singer “Bab” in the Congress"
      username="Simon Ayodele"
      timer="2 weeks"
      ethbid="2.4"
      usdbid="14,321"
    />
    <NFTCard
      photo="images/image8.png"
      userphoto="images/person1.png"
      title="#412 Painting from the famous movie titled ‘Stolen Dreams'"
      username="Mark Imo"
      timer="1 day"
      ethbid="2.40"
      usdbid="11,003.4"
    />
    <NFTCard
      photo="images/image9.png"
      userphoto="images/person3.png"
      title="#710 Photograph for the magazine cover of Rwandan model"
      username="Elizabeth Gambi"
      timer="2 days"
      ethbid="10.50"
      usdbid="43,063.4"
    />
    <NFTCard
      photo="images/image10.png"
      userphoto="images/person1.png"
      title="#312 Painting of the richest sisters of Burikan royal family"
      username="Mark Imo"
      timer="2 weeks"
      ethbid="6.1"
      usdbid="21,321"
    />
    <button id="view-all">View All</button>
  </div>
</template>

<style lang="scss" scoped>
#main {
  margin-top: 6.25rem;
  width: 100%;
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  justify-content: space-between;
  row-gap: 9.81rem;
  button#view-all {
    grid-column: 2 / 3;
    position: relative;
    bottom: 4rem;
    justify-self: center;
    width: fit-content;
    padding: 1.31rem 3.5rem;
    background: transparent;
    border: 1px solid #000;
    color: #000;
    text-align: center;
    font-family: "Space Grotesk", sans-serif;
    font-size: 1.25rem;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
  }
}
</style>

<script>
import { defineComponent } from "vue";
import NFTCard from "@/components/NFTCard.vue";

export default defineComponent({
  name: "FeaturedNFTs",
  components: {
    NFTCard,
  },
});
</script>
