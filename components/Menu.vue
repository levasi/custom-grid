<template>
  <div class="main-menu">
    <GridContainer>
      <GridRow>
        <GridColumn class="col-12 col-sm-4">
          <img
            class="logo-image"
            src="@/assets/images/header-logo.png"
            alt=""
          />
        </GridColumn>
        <GridColumn class="col-12 col-sm-4">
          <div class="inner">
            <ul class="menu-items">
              <li>HOME</li>
              <li>MENU</li>
              <li>BLOG</li>
              <li>RESERVATION</li>
            </ul>
          </div>
        </GridColumn>
        <GridColumn class="col-12 col-sm-4">
          <div class="inner">
            <button class="btn-green">ORDER ONLINE</button>
          </div>
        </GridColumn>
      </GridRow>
    </GridContainer>
  </div>
</template>
<script>
export default {
  name: "MainMenu"
};
</script>

<style lang="scss">
.logo-image {
  max-width: 200px;
}
.main-menu {
  color: white;
  padding: 10px 0;
  position: fixed;
  z-index: 2;
  top: 0;
  width: 100%;

  .menu-items {
    list-style-type: none;
    display: flex;
    align-items: center;
    padding-left: 0;
    li {
      margin-right: 1rem;
      cursor: pointer;
    }
  }
  .menu-items-wrapper {
    display: flex;
    align-items: center;
  }
  .inner {
    display: flex;
    align-items: center;
    height: 100%;
    justify-content: center;
    width: 100%;
  }
}
</style>
