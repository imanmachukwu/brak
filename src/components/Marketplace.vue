<template>
  <div id="main">
    <div id="marketplace-buttons">
      <button class="most">
        Most Viewed
        <span
          ><svg
            xmlns="http://www.w3.org/2000/svg"
            width="21"
            height="16"
            viewBox="0 0 21 16"
            fill="none"
          >
            <path
              d="M20.7071 8.70711C21.0976 8.31658 21.0976 7.68342 20.7071 7.29289L14.3431 0.928932C13.9526 0.538408 13.3195 0.538408 12.9289 0.928932C12.5384 1.31946 12.5384 1.95262 12.9289 2.34315L18.5858 8L12.9289 13.6569C12.5384 14.0474 12.5384 14.6805 12.9289 15.0711C13.3195 15.4616 13.9526 15.4616 14.3431 15.0711L20.7071 8.70711ZM0 9L20 9V7L0 7L0 9Z"
              fill="white"
            /></svg
        ></span>
      </button>
      <button class="recommended">Recommended</button>
      <button class="recommended">Trending</button>
      <button class="recommended">Arts & Painting</button>
      <button class="recommended see-more">See More</button>
    </div>
    <div id="marketplace-divider">
      <div id="marketplace-indicator"></div>
    </div>
    <div id="marketplace-container">
      <NFTCards />
      <button id="view-all">View All</button>
    </div>
  </div>
</template>

<style lang="scss" scoped>
#main {
  width: 100%;
  display: flex;
  gap: 3.31rem;
  margin-top: 6.19rem;
  #marketplace-buttons {
    display: flex;
    flex-direction: column;
    flex-grow: 1;
    gap: 1.87rem;
    button {
      width: 100%;
      padding: 1.5rem 1.75rem;
      text-align: left;
      font-family: "Space Grotesk", sans-serif;
      font-size: 1.25rem;
      font-style: normal;
      font-weight: 400;
      line-height: normal;
    }
    button.most {
      border-radius: 0.1875rem;
      background: #000;
      border: none;
      color: #fff;
      display: flex;
      justify-content: space-between;
    }
    button.recommended {
      background: transparent;
      color: #000;
      border: 1px solid #000;
    }
    button.see-more {
      margin-top: 3.44rem;
      text-align: center;
    }
    button.see-more::after {
      background: url(../assets/icons/downward-arrow.svg),
        lightgray 50% / cover no-repeat;
      width: 0.375rem;
      height: 0.375rem;
    }
  }
  #marketplace-divider {
    width: 0.5rem;
    height: 28.8125rem;
    flex-shrink: 0;
    border-radius: 2.5rem;
    border: 1px solid rgba(0, 0, 0, 0.5);
    background: #fff;
    #marketplace-indicator {
      width: 95%;
      height: 86%;
      flex-shrink: 0;
      border-radius: 2.5rem;
      background: #d9d9d9;
    }
  }
  #marketplace-container {
    display: flex;
    flex-direction: column;
    gap: 4.01rem;
    align-items: center;
    button#view-all {
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
}
</style>

<script>
import { defineComponent } from "vue";
import NFTCards from "@/components/NFTCards.vue";

export default defineComponent({
  name: "MarketPlace",
  components: {
    NFTCards,
  },
});
</script>
