<template>
  <section class="process-section">
    <GridContainer>
      <GridRow>
        <GridColumn class="col-12 col-md-4">
          <div class="process-section-item">
            <i class="fab fa-500px"></i>
            <h4>ORDER YOUR FOOD</h4>
            <p>
              Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do
              eius-Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed
              do eius-Lorem ipsum dolor sit amet, consectetur adipisicing elit,
              sed do eius-
            </p>
          </div>
        </GridColumn>
        <GridColumn class="col-12 col-md-4">
          <div class="process-section-item">
            <i class="fab fa-500px"></i>
            <h4>DELIVERY OR PICK UP</h4>
            <p>
              Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do
              eius-Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed
              do eius-Lorem ipsum dolor sit amet, consectetur adipisicing elit,
              sed do eius-
            </p>
          </div>
        </GridColumn>
        <GridColumn class="col-12 col-md-4">
          <div class="process-section-item">
            <i class="fab fa-500px"></i>
            <h4>DELICIOUS RECEIPE</h4>
            <p>
              Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do
              eius-Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed
              do eius-Lorem ipsum dolor sit amet, consectetur adipisicing elit,
              sed do eius-
            </p>
          </div>
        </GridColumn>
      </GridRow>
    </GridContainer>
  </section>
</template>
<script>
export default {
  name: "ProcessSection"
};
</script>
<style lang="scss">
.process-section {
  padding: 60px 0;
  text-align: center;
  background-color: $highlight;
  color: $dark;
  h4 {
    margin-bottom: 16px;
    font-size: 1.5rem;
  }
  i {
    font-size: 5rem;
    margin-bottom: 20px;
    color: $dark;
    transition: all 0.2s ease-in-out;
    position: relative;
    top: 0;
  }
  &-item {
    cursor: pointer;
    &:hover {
      i {
        color: white;
        top: -10px;
      }
    }
  }
}
</style>
