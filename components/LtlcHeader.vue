<template>
  <header class="nhsuk-header nhsuk-header" role="banner">
    <div class="nhsuk-width-container-fluid nhsuk-header__container">
      <div class="nhsuk-header__logo nhsuk-header__logo--only">
        <a class="nhsuk-header__link" href="https://ergonomics.org.uk/" aria-label="CIEHF website">
          <img class="cieh-logo" src="../assets/img/ciehf-logo.png" />
        </a>
      </div>
    </div>
  </header>
</template>

<script>
export default {}
</script>

<style lang="scss">
@import 'node_modules/nhsuk-frontend/packages/components/header/header';

.nhsuk-header {
  background-color: #fff;
}

.nhsuk-header__container {
  padding: 8px 0;
}

.nhsuk-header__link {
  height: auto;
  width: auto;
}

.cieh-logo {
  width: 260px;
}
</style>
