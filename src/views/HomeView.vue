<template>
  <div class="home">
    <div id="ellipse-1"></div>
    <div id="ellipse-2"></div>
    <div id="ellipse-3"></div>
    <div id="landing-content">
      <h1 id="landing-content-title">
        Explore the best NFT collection in <span id="bold">Africa</span>
      </h1>
      <p id="landing-content-subtitle">
        Explore the top NFT platform in Africa. Create and trade your digital
        ART on a secure platform like BR K
      </p>
      <div id="landing-content-buttons">
        <button id="explore">Explore</button>
        <button id="create">Create NFT</button>
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
</template>

<style lang="scss" scoped>
.home {
  width: 100%;
  height: 100%;
  display: flex;
  gap: 3.38rem;
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
      #bold {
        font-weight: 700;
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
      margin-top: 2.19rem;
      display: flex;
      gap: 1.25rem;
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
</style>

<script>
export default {
  name: "HomeView",
};
</script>
