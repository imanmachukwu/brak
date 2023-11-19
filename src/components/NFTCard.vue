<template>
  <div class="nft-card">
    <img v-bind:src="require(`../assets/${photo}`)" alt="" class="nft-image" />
    <h1 class="nft-title">{{ title }}</h1>
    <div class="nft-bid">
      <p class="nft-bid-label">Current Bid</p>
      <div class="nft-bid-price">
        <p class="nft-bid-eth">
          {{ ethbid }} ETH - <span>{{ usdbid }} USD</span>
        </p>
        <p class="nft-bid-timer">
          <span
            ><svg
              xmlns="http://www.w3.org/2000/svg"
              width="10"
              height="10"
              viewBox="0 0 10 10"
              fill="none"
            >
              <circle
                cx="5"
                cy="5"
                r="4.5"
                stroke="black"
                stroke-opacity="0.5"
              />
              <line
                x1="4.94531"
                y1="1.11133"
                x2="4.94531"
                y2="5.55577"
                stroke="black"
                stroke-opacity="0.5"
              />
              <line
                x1="4.44179"
                y1="5.07814"
                x2="7.58437"
                y2="5.05601"
                stroke="black"
                stroke-opacity="0.5"
              /></svg></span
          >{{ timer }} left
        </p>
      </div>
    </div>
    <div class="nft-user">
      <img
        v-bind:src="require(`../assets/${userphoto}`)"
        alt=""
        class="nft-user-photo"
      />
      <p class="user-name">{{ username }}</p>
    </div>
    <button class="bid">Place a Bid</button>
    <button class="view">View NFT</button>
  </div>
</template>

<style lang="scss" scoped>
.nft-card {
  width: 22.8125rem;
  height: fit-content;
  border-radius: 0.1875rem;
  background: #fff;
  padding: 1.63rem;
  display: flex;
  flex-direction: column;
  gap: 0.81rem;
  .nft-image {
    width: 19.625rem;
    height: 20.4375rem;
    flex-shrink: 0;
    object-fit: cover;
  }
  .nft-title {
    margin-top: 0.94rem;
    color: #000;
    font-family: Space Grotesk;
    font-size: 1.5rem;
    font-style: normal;
    font-weight: 400;
    line-height: 1.875rem;
    overflow: hidden;
    text-overflow: ellipsis;
    display: -webkit-box;
    -webkit-line-clamp: 2;
    line-clamp: 2;
    -webkit-box-orient: vertical;
  }
  .nft-bid {
    display: flex;
    flex-direction: column;
    gap: 0.87rem;
    width: 100%;
    p.nft-bid-label {
      color: #000;
      font-family: "Space Grotesk", sans-serif;
      font-size: 0.625rem;
      font-style: normal;
      font-weight: 400;
      line-height: normal;
    }
    .nft-bid-price {
      display: flex;
      justify-content: space-between;
      width: 100%;
      p.nft-bid-eth {
        color: #000;
        font-family: "Space Grotesk", sans-serif;
        font-size: 1.25rem;
        font-style: normal;
        font-weight: 700;
        line-height: normal;
      }
      p.nft-bid-eth > span {
        color: rgba(0, 0, 0, 0.7);
        font-size: 0.875rem;
        font-style: normal;
        font-weight: 400;
        line-height: normal;
      }
      p.nft-bid-timer {
        color: rgba(0, 0, 0, 0.5);
        font-family: "Space Grotesk", sans-serif;
        font-size: 0.625rem;
        font-style: normal;
        font-weight: 400;
        line-height: normal;
      }
      p.nft-bid-timer > span {
        margin-right: 0.44rem;
      }
    }
  }
  .nft-user {
    margin-top: 1.15rem;
    display: flex;
    gap: 1.48rem;
    align-items: center;
    img.nft-user-photo {
      object-fit: cover;
      border-radius: 50%;
      width: 2.19544rem;
      height: 2.00556rem;
      flex-shrink: 0;
    }
    p.user-name {
      color: #000;
      font-family: "Space Grotesk", sans-serif;
      font-size: 0.875rem;
      font-style: normal;
      font-weight: 400;
      line-height: normal;
    }
  }
  button {
    width: 100%;
    padding: 0.94rem 0px;
    font-family: "Space Grotesk", sans-serif;
    font-size: 1rem;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
  }
  button.bid {
    margin-top: 1.09rem;
    background: #000;
    border: none;
    color: #fff;
  }
  button.view {
    background: transparent;
    color: #000;
    border: 1px solid #000;
  }
}
</style>

<script>
import { defineComponent } from "vue";

export default defineComponent({
  name: "NFTCard",
  props: {
    photo: String,
    title: String,
    userphoto: String,
    username: String,
    ethbid: String,
    usdbid: String,
    timer: String,
  },
});
</script>
