<template>
  <div class="container">
    <slot></slot>
  </div>
</template>

<script>
export default {
  name: "Container"
};
</script>

<style lang="scss">
* {
  box-sizing: border-box;
}

body {
  font-family: sans-serif;
}

.container {
  max-width: 1230px;
  margin: 0 auto;
  justify-content: center;
}
div[class^="col-"] {
  padding-right: 1rem;
  padding-left: 1rem;
}
.row {
  display: flex;
  flex-wrap: wrap;
  margin-right: -1rem;
  margin-left: -1rem;
  margin: 0 auto;
}
$breakpoint-xl: 1920px;
$breakpoint-lg: 1536px;
$breakpoint-md: 768px;
$breakpoint-sm: 576px;
$breakpoint-xs: 360px;
$columns: 12;

@for $i from 1 through $columns {
  .col-#{$i} {
    flex: 0 0 100% / $columns * $i;
  }
  .col-offset-#{$i} {
    margin-left: 100% / $columns * $i;
  }
}
@media (min-width: $breakpoint-xs) {
  @for $i from 1 through $columns {
    .col-xs-#{$i} {
      flex: 0 0 100% / $columns * $i;
    }
  }
}
@media (min-width: $breakpoint-sm) {
  @for $i from 1 through $columns {
    .col-sm-#{$i} {
      flex: 0 0 100% / $columns * $i;
    }
  }
}
@media (min-width: $breakpoint-md) {
  @for $i from 1 through $columns {
    .col-md-#{$i} {
      flex: 0 0 100% / $columns * $i;
    }
  }
}
@media (min-width: $breakpoint-lg) {
  @for $i from 1 through $columns {
    .col-lg-#{$i} {
      flex: 0 0 100% / $columns * $i;
    }
  }
}
@media (min-width: $breakpoint-xl) {
  @for $i from 1 through $columns {
    .col-xl-#{$i} {
      flex: 0 0 100% / $columns * $i;
    }
  }
}
img {
  width: 100%;
}
</style>
