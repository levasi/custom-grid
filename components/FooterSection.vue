<template>
  <section class="footer-section">
    <GridContainer>
      <GridRow>
        <GridColumn class="col-12 col-md-4">
          <img
            class="logo-image"
            src="@/assets/images/header-logo.png"
            alt=""
          />
          <p>
            20 Carrochan Rd, Balloch, Alexandria G83 8EG, UK 69QJ+2F Alexandria,
            United Kingdom
          </p>
          <p>
            PHONE - +91 123 456 789 0 , +91 123 456 789 0
          </p>
          <p>
            EMAIL - support@pizzon.com
          </p>
        </GridColumn>
        <GridColumn class="col-12 col-md-4">
          <h3>OPENING HOURS</h3>
          <p>
            <span>Mon - Tues :</span>
            <span>6.00 am - 10.00 pm</span>
          </p>
          <p>
            <span>Wednes - Thurs :</span>
            <span>6.00 am - 10.00 pm</span>
          </p>
          <p>
            <span>Launch :</span>
            <span>Everyday</span>
          </p>
          <p>
            <span>Sunday :</span>
            <span>Closed </span>
          </p>
        </GridColumn>
        <GridColumn class="col-12 col-md-4">
          <h3>USEFUL LINKS</h3>
          <ul>
            <li>Privacy Policy</li>
            <li>Order Tracking</li>
            <li>Warranty and Services</li>
            <li>About</li>
            <li>Contact Us</li>
            <li>Wishlist</li>
          </ul>
        </GridColumn>
      </GridRow>
      <GridRow class="py-60">
        <GridColumn class="col-12 col-md-6">
          <p>© Pizzon all Rights Reserved.</p>
        </GridColumn>
        <GridColumn class="col-12 col-md-6">
          <ul>
            <li>f</li>
            <li>t</li>
            <li>in</li>
            <li>instagram</li>
          </ul>
        </GridColumn>
      </GridRow>
    </GridContainer>
  </section>
</template>
<script>
export default {
  name: "FooterSection"
};
</script>
<style lang="scss">
.footer-section {
  padding-top: 60px;
  background-color: $dark;
  color: white;
}
</style>
