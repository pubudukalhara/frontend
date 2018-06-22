<template>
  <section class="container">
    <div>
      <logo/>
      <h1 class="title">
        Mancester United Fan Club
      </h1>
      <h2 class="subtitle">
        Login
      </h2>

      <form class="form-horizontal">


              <div class="form-group">
                  <label class="col-md-4 control-label" for="textinput">Username</label>
                  <div class="col-md-4">
                      <input id="textinput" name="textinput" type="text" placeholder="" class="form-control input-md">

                  </div>
              </div>

              <!-- Text input-->
              <div class="form-group">
                  <label class="col-md-4 control-label" for="textinput">Password</label>
                  <div class="col-md-4">
                      <input id="textinput" name="textinput" type="text" placeholder="" class="form-control input-md">

                  </div>
              </div>



              <!-- Button -->
              <div class="form-group">
                  <label class="col-md-4 control-label" for=""></label>
                  <div class="col-md-4">
                      <button id="" name="" class="btn btn-success">New User</button>
                      <button id="" name="" class="btn btn-primary">Login</button>


                  </div>
              </div>

          </fieldset>
      </form>












    </div>
  </section>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>
.container
{
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
.title
{
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}
.subtitle
{
  font-weight: 100;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.form-group
{
  min-height: 5vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.col-md-4
{
  font-weight: 100;
  font-size: 25px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}



.links
{
  padding-top: 15px;
}
</style>
