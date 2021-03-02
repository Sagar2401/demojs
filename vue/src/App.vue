<template>
  <div class="component-1">
    <p class="tanay">{{ tanay }}</p>
    <img
      alt=""
      class="icons"
      src="https://static.overlay-tech.com/assets/1172f1ef-0e05-4361-9c14-1db886ab7b71.svg"
    />
    <div class="flex-wrapper-one">
      <img
        alt=""
        class="icons-two"
        src="https://static.overlay-tech.com/assets/458ddb53-a91d-4820-852f-c2d4c01c1ec4.svg"
      /><img
        alt=""
        class="icons-three"
        src="https://static.overlay-tech.com/assets/2b12a375-fb49-4523-89ef-3f833b01b9b9.svg"
      />
      <p class="hyphen">{{ hyphen }}</p>
      <p class="hyphen">{{}}</p>
    </div>
    <img
      alt=""
      src="https://static.overlay-tech.com/assets/5b122f56-bd21-41c5-bc37-2e4c60e5ca18.png"
    />
  </div>
</template>

<script>

export default {
  name: "Component1",
  props: {
  tanay: { type: String, default: 'Tanay' },
  hyphen: { type: String, default: '-' },
 
  }
};
</script>

<style lang="scss" scoped>
.component-1 {
  display: flex;
  align-items: flex-start;
}

.icons {
  margin-top: 130px;
  margin-right: 20px;
}
.flex-wrapper-one {
  margin-right: 274px;
  padding: 130px 0 0;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}
.icons-two {
  margin-bottom: 1018px;
}
.icons-three {
  margin-bottom: 432px;
  margin-left: 15px;
}
.hyphen {
  width: 17px;
 
  text-align: right;
  margin-left: 9px;
  &:not(:last-of-type) {
    margin-bottom: 210px;
  }
}
</style>