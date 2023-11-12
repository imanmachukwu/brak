<script>
import { defineComponent } from "vue";

export default defineComponent({
  name: "AppHeader",
});
</script>

<template>
  <div class="header">
    <div class="header-menu-div">
      <div class="header-logo">
        <p class="logo">
          <span class="svg first-child">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="11"
              height="14"
              viewBox="0 0 11 14"
              fill="none"
            >
              <line
                x1="0.264151"
                y1="7.01883"
                x2="10.2641"
                y2="13.2411"
                stroke="black"
              />
              <line
                x1="10.2642"
                y1="0.424528"
                x2="0.264152"
                y2="6.64675"
                stroke="black"
              />
              <line x1="0.5" y1="1" x2="0.5" y2="13.6667" stroke="black" />
              <line y1="0.5" x2="10" y2="0.5" stroke="black" />
              <line y1="13.166" x2="10" y2="13.166" stroke="black" />
            </svg>
          </span>
          <span class="logo-text">BR</span>
          <span class="svg second-child"
            ><svg
              xmlns="http://www.w3.org/2000/svg"
              width="11"
              height="12"
              viewBox="0 0 11 12"
              fill="none"
            >
              <line
                x1="5.46061"
                y1="0.194522"
                x2="0.881326"
                y2="11.0378"
                stroke="black"
              />
              <line
                x1="10.5473"
                y1="10.8782"
                x2="5.54727"
                y2="0.212227"
                stroke="black"
              />
              <line
                x1="0.999996"
                y1="10.5"
                x2="10"
                y2="10.5"
                stroke="black"
              /></svg
          ></span>
          <span class="logo-text">K</span>
        </p>
      </div>
      <div class="header-menu">
        <ul class="menu-list">
          <li class="menu-list-item selected">Home</li>
          <li class="menu-list-item">Marketplace</li>
          <li class="menu-list-item">Create</li>
          <li class="menu-list-item">Statistics</li>
          <li class="menu-list-item">Profile</li>
        </ul>
      </div>
    </div>
    <div class="header-buttons">
      <div class="header-search">
        <input type="text" class="search-text" placeholder="Search" />
      </div>
      <div class="header-button-div">
        <button class="header-button">Connect Wallet</button>
      </div>
    </div>
    <div class="header-mobile">
      <img src="" alt="Search icon" />
      <img src="" alt="Menu icon" />
    </div>
  </div>
</template>

<style lang="scss" scoped>
.header {
  width: 100%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 2.94rem 0px;
  .header-menu-div {
    display: flex;
    gap: 6.81rem;
    .header-logo {
      width: fit-content;
      .logo {
        width: fit-content;
        .first-child {
          margin-right: 0.37rem;
          width: 0.625rem;
          height: 0.85419rem;
          flex-shrink: 0;
        }
        .second-child {
          width: 0.66119rem;
          height: 0.6875rem;
          flex-shrink: 0;
        }
        .logo-text {
          color: #000;
          font-family: Federo;
          font-size: 1rem;
          font-style: normal;
          font-weight: 400;
          line-height: normal;
        }
      }
    }
    .header-menu {
      width: fit-content;
      ul.menu-list {
        display: flex;
        list-style: none;
        text-decoration: none;
        gap: 1.5rem;
        li.selected {
          color: rgba(0, 0, 0, 1);
          border-bottom: 0.0625rem solid #000;
          padding: 0.19rem 1rem;
        }
        .menu-list-item {
          color: rgba(0, 0, 0, 0.7);
          font-family: Space Grotesk;
          font-size: 0.875rem;
          font-style: normal;
          font-weight: 400;
          line-height: normal;
          padding: 0.19rem 0px;
        }
        .menu-list-item::after {
          background: url(../assets/icons/downward-arrow.svg),
            lightgray 50% / cover no-repeat;
          width: 0.375rem;
          height: 0.375rem;
        }
      }
    }
  }
  .header-buttons {
    display: flex;
    gap: 2.5rem;
    width: fit-content;
    .header-search {
      width: fit-content;
      .search-text {
        border: 1px solid rgba(0, 0, 0, 0.5);
        padding: 0.81rem 0.62rem;
        background: transparent;
        font-family: "Space Grotesk";
        font-size: 0.875rem;
        font-style: normal;
        font-weight: 400;
        line-height: normal;
      }
      .search-text::placeholder {
        color: rgba(0, 0, 0, 0.5);
        font-size: 0.875rem;
        font-style: normal;
        font-weight: 400;
        line-height: normal;
        font-family: "Space Grotesk";
      }
      .search-text::after {
        background: url(../assets/icons/search-icon.svg),
          lightgray 50% / cover no-repeat;
        width: 1.25rem;
        height: 1.11606rem;
        flex-shrink: 0;
        opacity: 0.5;
      }
    }
    .header-button-div {
      width: fit-content;
      .header-button {
        padding: 0.81rem 1.94rem;
        background: #000;
        color: #fff;
        font-size: 0.875rem;
        font-style: normal;
        font-weight: 400;
        line-height: normal;
        border: none;
        font-family: "Space Grotesk";
      }
    }
  }
  .header-mobile {
    display: none;
  }
}

@media only screen and (max-width: 695px) {
  .header {
    background: #fff;
    padding: 3rem 0px 1.38rem;
    .header-logo {
      .logo {
        .first-child {
          width: 0.81738rem;
          height: 1.11663rem;
          flex-shrink: 0;
        }
        .second-child {
          width: 0.87475rem;
          height: 1.10119rem;
          flex-shrink: 0;
        }
        .logo-text {
          font-size: 1.5rem;
        }
      }
    }
    .header-menu {
      display: none;
    }
    .header-buttons {
      display: none;
    }
    .header-mobile {
      display: flex;
      gap: 1.5rem;
    }
  }
}
</style>
