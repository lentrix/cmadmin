<template>
  <div class="row">
    <div class="col-md-4 offset-md-4 mt-4">
      <h3>User Login</h3>
      <b-alert variant="info" show>
        This site is for Coolmart360 administrators only.
        Your regular Coolmart360 credentials will not be
        given access here.
      </b-alert>
      <b-form @submit="onSubmit">

        <b-form-group id="input-group-1" label="Email Address" label-for="email">
          <b-form-input id="email" v-model="form.email" type="email" required></b-form-input>
        </b-form-group>

        <b-form-group id="input-group-2" label="Password" label-for="password">
          <b-form-input id="password" v-model="form.password" type="password" required></b-form-input>
        </b-form-group>

        <b-form-group>
          <div class="row">
            <div class="col-sm-4">
              <b-button block type="reset" variant="info">
                Clear
              </b-button>
            </div>
            <div class="col-sm-4 offset-sm-4">
              <b-button block type="submit" variant="primary">
                Login
              </b-button>
            </div>
          </div>
        </b-form-group>

      </b-form>
    </div>
  </div>
</template>

<script>
export default {
  name: "LoginForm",
  data: () => {
    return {
      form: {
        email: '',
        password: ''
      }
    }
  },
  methods: {
    onSubmit() {

    }
  }
}
</script>
