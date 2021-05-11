<template>
  <div>
    <div>
      <!-- Image and text -->
      <b-navbar variant="info" type="dark">
        <b-container>
          <b-navbar-brand href="/">
            <img src="~/assets/coolmart360_logo_final.png" style="height: 50px" class="d-inline-block align-top" alt="Kitten">
          </b-navbar-brand>
          <b-navbar-brand href="/">
            Administrators
          </b-navbar-brand>

          <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

           <b-collapse id="nav-collapse" is-nav>
            <b-navbar-nav class="ml-auto">
              <b-nav-item href="/test">Link</b-nav-item>

            </b-navbar-nav>
           </b-collapse>
        </b-container>
      </b-navbar>
    </div>

    <b-container>
      <Nuxt />
    </b-container>
  </div>
</template>

<style>

</style>
