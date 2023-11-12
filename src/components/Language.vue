<script>
import { defineComponent } from "vue";

export default defineComponent({
  name: "AppLanguage",
});
</script>

<template>
  <div class="language-div">
    <ul class="language-list">
      <li class="languages selected">English</li>
      <li class="languages">Arabic</li>
      <li class="languages">Swahili</li>
      <li class="languages">French</li>
    </ul>
  </div>
</template>

<style lang="scss" scoped>
.language-div {
  width: 100%;
  padding: 3.94rem 0px 1.75rem;
  display: flex;
  justify-content: center;
  border-bottom: 0.0625rem solid rgba(0, 0, 0, 0.3);
  //align-items: center;
  .language-list {
    list-style: none;
    text-decoration: none;
    display: flex;
    gap: 7.19rem;
    width: fit-content;
    .languages {
      color: rgba(0, 0, 0, 0.5);
      font-size: 1.25rem;
      font-style: normal;
      font-weight: 400;
      line-height: normal;
    }
    .selected {
      color: #000;
    }
  }
}

@media only screen and (max-width: 695px) {
  .language-div {
    padding: 2.87rem 0px 1rem;
    border: none;
    .language-list {
      gap: 0rem;
      border-bottom: none;
      width: 100%;
      justify-content: space-between;
      .languages {
        font-size: 0.875rem;
      }
    }
  }
}
</style>
