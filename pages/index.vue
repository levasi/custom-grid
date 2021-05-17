<template>
  <div class="custom-grid">
    <Menu />
    <section class="banner-section">
      <GridContainer>
        <GridRow>
          <GridColumn class="col-12 col-md-6">
            <img src="@/assets/images/pizza-banner-2.png" alt="" />
          </GridColumn>
          <GridColumn class="col-12 col-md-6">
            <div class="inner">
              <h1>Quality foods</h1>
              <p>HEALTHY FOOD FOR HEALTHY BODY</p>
            </div>
          </GridColumn>
        </GridRow>
      </GridContainer>
    </section>
    <ProcessSection />
    <SpecialMenuSection />
    <OurSpecialitySection />
  </div>
</template>

<script>
import Vue from "vue";
export default Vue.extend({});
</script>

<style lang="scss">
.banner-section {
  background-color: $dark;
  position: relative;
  padding-top: 100px;
  &:before {
    content: "";
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-image: url("@/assets/images/chef-bg.png");
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    opacity: 0.3;
  }
  .inner {
    display: flex;
    align-items: flex-start;
    justify-content: center;
    height: 100%;
    flex-direction: column;
    h1 {
      color: $highlight;
      font-size: 5rem;
    }
    p {
      font-size: 1.5rem;
      color: white;
    }
  }
}
</style>
