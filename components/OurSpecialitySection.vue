<template>
  <div class="our-speciality-section">
    <GridContainer>
      <GridRow>
        <GridColumn class="col-12">
          <div
            class="header d-flex flex-column align-items-center justify-content-center"
          >
            <span>Fresh From Pizzon</span>
            <h2>
              OUR SPECIALITY
            </h2>
          </div>
        </GridColumn>
      </GridRow>
      <GridRow>
        <GridColumn class="col-12 col-md-4">
          <div class="our-speciality-section-item">
            <img src="@/assets/images/speciality-1.jpg" alt="" />
            <h5>
              MEXICAN GREEN WAVE
            </h5>
          </div>
        </GridColumn>
        <GridColumn class="col-12 col-md-4">
          <div class="our-speciality-section-item">
            <img src="@/assets/images/speciality-2.jpg" alt="" />
            <h5>
              DOUBLE CHEEZE PIZZA
            </h5>
          </div>
        </GridColumn>
        <GridColumn class="col-12 col-md-4">
          <div class="our-speciality-section-item">
            <img src="@/assets/images/speciality-3.jpg" alt="" />
            <h5>
              MAERGERITA PIZZA
            </h5>
          </div>
        </GridColumn>
      </GridRow>
      <GridRow>
        <GridColumn class="col-12">
          <button class="view-more-button btn-highlight">VIEW MORE</button>
        </GridColumn>
      </GridRow>
    </GridContainer>
  </div>
</template>
<script>
export default {
  name: "OurSpecialitySection"
};
</script>
<style lang="scss">
.our-speciality-section {
  padding: 60px 0;
  .header {
    padding: 30px 0;
  }
  &-item {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    img {
      margin-bottom: 30px;
      border-radius: 50%;
    }
  }
  .view-more-button {
    display: block;
    margin: 0 auto;
    margin-top: 30px;
  }
}
</style>
