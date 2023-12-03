<template>
  <div class="home">
    <div id="ellipse-1"></div>
    <div id="ellipse-2"></div>
    <div id="ellipse-3"></div>
    <div id="landing">
      <div id="landing-content">
        <h1 id="landing-content-title">
          Explore the best <span class="bold clip">NFT</span> collection in
          <span class="bold">Africa</span>
        </h1>
        <p id="landing-content-subtitle">
          Explore the top NFT platform in Africa. Create and trade your digital
          ART on a secure platform like BR K
        </p>
        <div id="landing-content-buttons">
          <button id="explore">Explore</button>
          <button id="create">Create NFT</button>
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="100"
            height="184"
            viewBox="0 0 100 184"
            fill="none"
          >
            <path
              d="M0.670795 16.215C0.13328 16.8906 0.199952 17.838 0.819709 18.3311L10.9193 26.3666C11.539 26.8597 12.4772 26.7117 13.0147 26.0361C13.5522 25.3606 13.4855 24.4132 12.8658 23.9201L3.8884 16.7774L11.6745 6.99136C12.212 6.31578 12.1453 5.36837 11.5255 4.87527C10.9058 4.38217 9.96762 4.53011 9.43011 5.20569L0.670795 16.215ZM13.6056 13.7322L1.68767 15.6115L1.89827 18.6041L13.8162 16.7248L13.6056 13.7322Z"
              fill="black"
            />
            <path
              d="M43.5138 180.37C67.2402 164.08 87.7198 150.429 93.1696 122.538C96.3418 106.304 91.9533 91.1875 78.0187 82.976C67.0782 76.5289 43.108 71.3271 28.9352 77.2175C24.5941 79.0218 26.1751 85.7856 29.1885 87.0881C43.5673 93.303 68.9128 71.4789 73.2905 58.9979C76.4418 50.0132 76.6257 34.57 72.7651 26.4723C68.9173 18.4013 48.6474 14.8559 39.3298 14.835C30.2752 14.8146 19.0723 13.8887 9.90975 15.878"
              stroke="black"
              stroke-width="3"
              stroke-linecap="round"
            />
          </svg>
        </div>
        <div id="landing-content-stats">
          <div class="stat-detail">
            <p class="stat-numbers">27K+</p>
            <p class="stat-label">Artworks</p>
          </div>
          <div class="stat-detail">
            <p class="stat-numbers">20K</p>
            <p class="stat-label">Auctions</p>
          </div>
          <div class="stat-detail">
            <p class="stat-numbers">10K</p>
            <p class="stat-label">Artists</p>
          </div>
        </div>
      </div>
      <div id="landing-cover">
        <img
          src="../assets/images/brak-cover.png"
          alt=""
          id="landing-cover-photo"
        />
        <div id="landing-cover-label">
          <p id="landing-cover-label-text">
            #115 Photograph for Model woman in Banda, Guinea.
          </p>
          <div id="landing-cover-label-pricing">
            <p id="landing-cover-label-price-label">Current Bid</p>
            <p id="landing-cover-label-price">
              7.23 ETH - <span>33,000.7 USD</span>
            </p>
          </div>
        </div>
      </div>
    </div>
    <div id="info-container">
      <p id="info-text">info</p>
      <div id="info-divider"></div>
      <p id="info-description">
        The most popular platform for publishing <br />
        promoting your art in the NFT format in Africa.
      </p>
    </div>
    <div id="marketplace-container">
      <h1 id="marketplace-title">
        Welcome to the BR K<br />
        NFT Market Place
      </h1>
      <p id="marketplace-description">
        Welcome to the Africa’s best virtual store for digital assets. <br />
        Here you can search and buy creators’s assests from AIRBIB.
      </p>
      <MarketPlace />
    </div>
    <div id="learn-and-earn">
      <div id="ellipse-4"></div>
      <div id="ellipse-5"></div>
      <div id="ellipse-6"></div>
      <div id="learn-and-earn-text">
        <h1 id="learn-and-earn-title">Learn and Earn free ETH with your NFT</h1>
        <p id="learn-and-earn-description">
          Brak NFT marketplace brings together artist, creators and<br />
          crypto enthusiasts on a single platform to create and explore<br />
          top NFT’s
        </p>
        <button id="learn-and-earn-button">Explore</button>
      </div>
      <div id="eth-square">
        <img src="../assets/images/etherum-2.png" alt="" class="eth-icon" />
        <img src="../assets/images/etherum-2.png" alt="" class="eth-icon" />
        <img src="../assets/images/etherum-2.png" alt="" class="eth-icon" />
        <img src="../assets/images/etherum-2.png" alt="" class="eth-icon" />
      </div>
    </div>
    <div id="featured">
      <h1 id="featured-title">Featured NFTs</h1>
      <p id="featured-description">
        This digital art has the highest rating and it will be displayed <br />
        on all our social media for auctions.
      </p>
      <FeaturedNFTs />
    </div>
    <div id="create-and-sell">
      <h1 id="create-and-sell-title">Create and Sell NFT</h1>
      <p id="create-and-sell-description">
        Feel free to add, list, set up your digital art in a collection to
        <br />
        provide a better layout.
      </p>
      <div id="create-and-sell-cards-container">
        <div class="create-card">
          <img src="../assets/icons/plus.svg" alt="" class="create-card-svg" />
          <p class="create-card-title">Add NFTs</p>
          <p class="create-card-text">
            Add your <span>digital art, images, audios and videos</span> that
            will be uploaded on our website for auction.
          </p>
        </div>
        <div class="create-card">
          <img src="../assets/icons/list.svg" alt="" class="create-card-svg" />
          <p class="create-card-title">List for Sale</p>
          <p class="create-card-text">
            <span>Create a list</span> containing all the NFT (digital art) you
            have made and generate your link.
          </p>
        </div>
        <div class="create-card">
          <img
            src="../assets/icons/wallet.svg"
            alt=""
            class="create-card-svg"
          />
          <p class="create-card-title">Set up Wallet</p>
          <p class="create-card-text">
            Set up a wallet to save all your <span>ethereum and coins</span> to
            make a sale of your NFT.
          </p>
        </div>
        <div class="create-card">
          <img src="../assets/icons/apps.svg" alt="" class="create-card-svg" />
          <p class="create-card-title">Create Collections</p>
          <p class="create-card-text">
            Create a collection of all your works associated to that field.
          </p>
        </div>
        <div class="ellipse1"></div>
        <div class="ellipse2"></div>
        <div class="ellipse3"></div>
      </div>
    </div>
    <div id="top-creators">
      <div id="top-creators-title">Top Creators of the week</div>
      <div id="top-creators-desc">
        View the profile of our best creators of the week with mind<br />
        blowing NFT collection.
      </div>
    </div>
    <div id="learn-and-earn">
      <div id="ellipse-4"></div>
      <div id="ellipse-5"></div>
      <div id="ellipse-6"></div>
      <div id="learn-and-earn-text">
        <h1 id="learn-and-earn-title">Learn and Earn free ETH with your NFT</h1>
        <p id="learn-and-earn-description">
          Brak NFT marketplace brings together artist, creators and<br />
          crypto enthusiasts on a single platform to create and explore<br />
          top NFT’s
        </p>
        <button id="learn-and-earn-button">Explore</button>
      </div>
      <div id="eth-square">
        <img src="../assets/images/etherum-2.png" alt="" class="eth-icon" />
        <img src="../assets/images/etherum-2.png" alt="" class="eth-icon" />
        <img src="../assets/images/etherum-2.png" alt="" class="eth-icon" />
        <img src="../assets/images/etherum-2.png" alt="" class="eth-icon" />
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.home {
  width: 100%;
  height: 100%;
  #ellipse-1 {
    width: 23.25rem;
    height: 23.25rem;
    flex-shrink: 0;
    border-radius: 23.25rem;
    background: rgba(194, 36, 45, 0.8);
    filter: blur(215px);
    position: absolute;
    top: 19.5rem;
    right: 0.56rem;
    z-index: -1;
  }
  #ellipse-2 {
    width: 18.875rem;
    height: 18.875rem;
    flex-shrink: 0;
    border-radius: 18.875rem;
    background: rgba(163, 191, 80, 0.8);
    filter: blur(215px);
    position: absolute;
    top: 44.69rem;
    right: 29.38rem;
    z-index: -1;
  }
  #ellipse-3 {
    width: 23.25rem;
    height: 23.25rem;
    flex-shrink: 0;
    border-radius: 23.25rem;
    background: #fff8eb;
    filter: blur(215px);
    position: absolute;
    top: 8.81rem;
    left: -2.81rem;
    z-index: -1;
  }
  #landing {
    width: 100%;
    height: 100%;
    display: flex;
    gap: 3.38rem;
    #landing-content {
      display: flex;
      flex-direction: column;
      gap: 2.69rem;
      max-width: 50%;
      #landing-content-title {
        color: #000;
        font-family: "Space Grotesk", sans-serif;
        font-size: 4rem;
        font-style: normal;
        font-weight: 400;
        line-height: normal;
        text-align: left;
        .bold {
          font-weight: 700;
        }
        span.clip {
          background-clip: text;
          background-image: url(../assets/images/nft-clip.png);
          -webkit-background-clip: text;
          -webkit-text-fill-color: transparent;
        }
      }
      #landing-content-subtitle {
        color: rgba(0, 0, 0, 0.7);
        font-family: "Space Grotesk", sans-serif;
        font-size: 1.25rem;
        font-style: normal;
        font-weight: 400;
        line-height: 2.1875rem; /* 175% */
        text-align: left;
      }
      #landing-content-buttons {
        width: fit-content;
        margin-top: 2.19rem;
        display: flex;
        gap: 1.25rem;
        position: relative;
        svg {
          rotate: 12.5deg;
          position: absolute;
          right: -5.5rem;
          top: 1rem;
        }
        button {
          padding: 1.31rem 3.44rem;
          font-family: "Space Grotesk", sans-serif;
          font-size: 1.25rem;
          font-style: normal;
          font-weight: 400;
          line-height: normal;
        }
        #explore {
          background: #000;
          color: #fff;
          border: none;
        }
        #create {
          background: transparent;
          border: 1px solid #000;
          color: #000;
        }
      }
      #landing-content-stats {
        display: flex;
        gap: 4.38rem;
        margin-top: 4.25rem;
        .stat-detail {
          display: flex;
          gap: 0.75rem;
          flex-direction: column;
          .stat-numbers {
            color: #000;
            font-family: "Space Grotesk", sans-serif;
            font-size: 3rem;
            font-style: normal;
            font-weight: 400;
            line-height: 1.875rem; /* 62.5% */
          }
          .stat-label {
            color: #000;
            font-family: "Space Grotesk", sans-serif;
            font-size: 0.875rem;
            font-style: normal;
            font-weight: 400;
            line-height: normal;
          }
        }
      }
    }
    #landing-cover {
      width: fit-content;
      height: fit-content;
      position: relative;
      img {
        width: 100%;
        height: 100%;
        object-fit: cover;
      }
      #landing-cover-label {
        padding: 1.12rem 1.69rem;
        background: #3b3b3b;
        display: flex;
        flex-direction: column;
        gap: 0.94rem;
        position: absolute;
        bottom: 1.06rem;
        right: -4.31rem;
        #landing-cover-label-text {
          color: #fff;
          font-family: "Space Grotesk", sans-serif;
          font-size: 0.875rem;
          font-style: normal;
          font-weight: 400;
          line-height: 1.25rem; /* 142.857% */
        }
        #landing-cover-label-pricing {
          background: #5c5c5c;
          text-align: left;
          display: flex;
          flex-direction: column;
          padding: 0.88rem 1.44rem;
          gap: 0.94rem;
          p#landing-cover-label-price-label {
            color: rgba(255, 255, 255, 0.5);
            font-family: "Space Grotesk", sans-serif;
            font-size: 0.75rem;
            font-style: normal;
            font-weight: 700;
            line-height: normal;
          }
          p#landing-cover-label-price {
            color: #fff;
            font-family: "Space Grotesk", sans-serif;
            font-size: 1.25rem;
            font-style: normal;
            font-weight: 700;
            line-height: normal;
            span {
              color: rgba(255, 255, 255, 0.5);
              font-size: 0.75rem;
            }
          }
        }
      }
    }
  }
  #info-container {
    width: 100%;
    height: 35rem;
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 1.66rem;
    #info-text {
      color: rgba(0, 0, 0, 0.5);
      font-family: "Space Grotesk", sans-serif;
      font-size: 6rem;
      font-style: normal;
      font-weight: 700;
      line-height: normal;
    }
    #info-divider {
      rotate: 105deg;
      width: 10.95675rem;
      height: 1px;
      background: #000;
    }
    #info-description {
      text-align: left;
      color: #000;
      font-family: "Space Grotesk", sans-serif;
      font-size: 1rem;
      font-style: normal;
      font-weight: 400;
      line-height: 1.875rem; /* 187.5% */
    }
  }
  #marketplace-container {
    width: 100%;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    gap: 1.44rem;
    text-align: left;
    margin-bottom: 13.75rem;
    #marketplace-title {
      color: #000;
      font-family: "Space Grotesk", sans-serif;
      font-size: 3rem;
      font-style: normal;
      font-weight: 400;
      line-height: normal;
    }
    #marketplace-description {
      color: rgba(0, 0, 0, 0.5);
      font-family: "Space Grotesk", sans-serif;
      font-size: 1.25rem;
      font-style: normal;
      font-weight: 400;
      line-height: normal;
    }
  }
  #learn-and-earn {
    position: relative;
    display: flex;
    justify-content: space-between;
    background: linear-gradient(
      269deg,
      #fff 1.82%,
      rgba(255, 255, 255, 0.5) 99.92%
    );
    padding: 3.38rem;
    margin-bottom: 13.87rem;
    #ellipse-4 {
      position: absolute;
      top: -7.31rem;
      left: -6.5rem;
      z-index: -1;
      width: 23.25rem;
      height: 23.25rem;
      flex-shrink: 0;

      border-radius: 23.25rem;
      background: #fff8eb;
      filter: blur(215px);
    }
    #ellipse-5 {
      position: absolute;
      top: -7rem;
      right: -4.75rem;
      z-index: -1;
      width: 21.625rem;
      height: 21.625rem;
      flex-shrink: 0;

      border-radius: 21.625rem;
      background: rgba(194, 36, 45, 0.8);
      filter: blur(215px);
    }
    #ellipse-6 {
      position: absolute;
      bottom: -10.62rem;
      right: -24.37rem;
      z-index: -1;
      width: 20rem;
      height: 20rem;
      flex-shrink: 0;

      border-radius: 20rem;
      background: rgba(163, 191, 80, 0.8);
      filter: blur(215px);
    }
    #learn-and-earn-text {
      width: fit-content;
      display: flex;
      flex-direction: column;
      gap: 1.44rem;
      text-align: left;
      #learn-and-earn-title {
        color: #000;
        font-family: "Space Grotesk", sans-serif;
        font-size: 2rem;
        font-style: normal;
        font-weight: 400;
        line-height: normal;
      }
      #learn-and-earn-description {
        color: rgba(0, 0, 0, 0.5);
        font-family: "Space Grotesk", sans-serif;
        font-size: 1rem;
        font-style: normal;
        font-weight: 400;
        line-height: 1.5625rem; /* 156.25% */
      }
      #learn-and-earn-button {
        width: fit-content;
        color: #fff;
        font-family: "Federo", serif;
        font-size: 1rem;
        font-style: normal;
        font-weight: 400;
        line-height: normal;
        background: #000;
        border: none;
        margin-top: 2.19rem;
        padding: 1.06rem 4.12rem;
      }
    }
    #eth-square {
      width: fit-content;
      height: fit-content;
      display: grid;
      grid-template-columns: 1fr 1fr;
      grid-template-rows: 1fr 1fr;
      row-gap: 1.15rem;
      column-gap: 1.57rem;
      .eth-icon:nth-of-type(odd) {
        position: relative;
        top: 1.14rem;
      }
      .eth-icon {
        width: 5.625rem;
        height: 5.625rem;
        transform: rotate(15deg);
        flex-shrink: 0;
      }
    }
  }
  #featured {
    width: 100%;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    gap: 1.44rem;
    text-align: left;
    #featured-title {
      color: #000;
      font-family: "Space Grotesk", sans-serif;
      font-size: 3rem;
      font-style: normal;
      font-weight: 400;
      line-height: normal;
    }
    #featured-description {
      color: rgba(0, 0, 0, 0.5);
      font-family: "Space Grotesk", sans-serif;
      font-size: 1.25rem;
      font-style: normal;
      font-weight: 400;
      line-height: normal;
    }
  }
  #create-and-sell {
    margin-top: 9.94rem;
    width: 100%;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    gap: 1.44rem;
    text-align: left;
    #create-and-sell-title {
      color: #000;
      font-family: "Space Grotesk", sans-serif;
      font-size: 3rem;
      font-style: normal;
      font-weight: 400;
      line-height: normal;
    }
    #create-and-sell-description {
      color: rgba(0, 0, 0, 0.5);
      font-family: "Space Grotesk", sans-serif;
      font-size: 1.25rem;
      font-style: normal;
      font-weight: 400;
      line-height: normal;
    }
    #create-and-sell-cards-container {
      margin-top: 3.25rem;
      display: grid;
      justify-content: space-between;
      grid-template-columns: 1fr 1fr 1fr 1fr;
      column-gap: 1.25rem;
      position: relative;
      .create-card {
        padding: 1.5rem 2.69rem;
        background: #fff;
        display: flex;
        flex-direction: column;
        gap: 0.31rem;
        .create-card-svg {
          margin-bottom: 1.26rem;
          width: 2.5rem;
          height: 2.5rem;
          flex-shrink: 0;
        }
        .create-card-svg:nth-child(1) {
          width: 1.875rem;
          height: 1.93013rem;
        }
        .create-card-svg:nth-child(2) {
          width: 3rem;
          height: 3rem;
        }
        .create-card-title {
          color: #000;
          font-family: "Space Grotesk", sans-serif;
          font-size: 1.5rem;
          font-style: normal;
          font-weight: 400;
          line-height: normal;
        }
        .create-card-text {
          //max-width: 14.3125rem;
          color: rgba(0, 0, 0, 0.5);
          font-family: "Space Grotesk", sans-serif;
          font-size: 0.875rem;
          font-style: normal;
          font-weight: 400;
          line-height: normal;
          span {
            font-weight: 700;
          }
        }
      }
      .ellipse1 {
        position: absolute;
        top: -10.44rem;
        left: -13.81rem;
        width: 23.25rem;
        height: 23.25rem;
        flex-shrink: 0;
        border-radius: 23.25rem;
        background: rgba(255, 248, 235, 0.7);
        filter: blur(215px);
        z-index: -1;
      }
      .ellipse2 {
        position: absolute;
        bottom: -15.25rem;
        left: -29.7525rem;
        width: 19.375rem;
        height: 19.375rem;
        flex-shrink: 0;
        border-radius: 19.375rem;
        background: rgba(163, 191, 80, 0.8);
        filter: blur(215px);
        z-index: -1;
      }
      .ellipse3 {
        position: absolute;
        top: -3.38rem;
        right: -10.5rem;
        width: 19.9375rem;
        height: 19.9375rem;
        flex-shrink: 0;
        border-radius: 19.9375rem;
        background: rgba(194, 36, 45, 0.8);
        filter: blur(215px);
        z-index: -1;
      }
    }
  }
}
</style>

<script>
import { defineComponent } from "vue";
import MarketPlace from "@/components/Marketplace.vue";
import FeaturedNFTs from "@/components/FeaturedNFTs.vue";

export default defineComponent({
  name: "HomeView",
  components: {
    MarketPlace,
    FeaturedNFTs,
  },
});
</script>
