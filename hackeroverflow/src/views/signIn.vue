<template>
  <div class="signin">
    <div class="signin-container">
      <section class="inner-container">

        <section id="signin-image">
          <img src="./../assets/homepage-image-1.png" class="signin-image-1"> <!--ondragstart="return false"-->
        </section>

        <section id="signin-form-container">
          <div id="signin-form-container-heading-container">
            <div id="signin-form-container-heading-text">Sign in</div>
            <div class="line">
            </div>
          </div>

          <div style="margin-top: 40px">
          <input type="email" class="input" placeholder="Username">
            </div>
            <div style="margin-top: 20px;">
          <input type="password" class="input" placeholder="Password">
            </div>
          <div class="button-class2">
            <button class="signin-button">Sign In</button>
          </div>

          <div class="singin-bottom">Don’t have an account ? <a style="color: #1968FC;cursor: pointer;">Sign Up</a></div>
        </section>

      </section>
    </div>

  </div>
</template>

<script>
  // @ is an alias to /src

  export default {
    name: 'SignIn',
    components: {}
  }
</script>
<style>

  .signin-container{
    width: 100%;
    height: 520px;
    margin-top: 135px;
  }

  .inner-container{
    width: 1115px;
    height: inherit;
    margin: auto;
    padding-left: 25px;
    padding-right: 25px;
  }

  #signin-image{
    width: 56%;
    height: inherit;
    display: flex;
    justify-content: flex-start;
    float: left;
  }

  .signin-image-1{
    width: 520px;
    height: 450px;
  }

  #signin-form-container{
    width: 44%;
    height: 100%;
    float: right;
  }

  #signin-form-container-heading-container {
    width: 100%;
    height: 118px;
    background-color: #F3F7FF;
    overflow:auto
  }

  #signin-form-container-heading-text {
    margin-left: 5.1%;
    font-size: 30px;
    font-weight: 500;
    margin-top: 35px;
  }

  .line{
    background: #1968FC;
    box-shadow: 0 2px 0 0 #D1E1FE;
    width: 71px;
    height: 2px;
    margin-top: 10px;
    margin-left: 5.1%;
  }

  .input{
    background: #FFFFFF;
    box-shadow: 0 20px 60px 0 rgba(49,69,244,0.10);
    height: 80px;
    width: 94%;
    border: none;
    font-size: 30px;
    padding-left: 25px;
    cursor: default;
  }

  .button-class2{
    width: 100%;
    height: 69px;
    display: flex;
    justify-content: center;
    margin-top: 40px;
  }

  .signin-button{
    border: none;
    font-weight: normal;
    width: 165px;
    height: inherit;
    background: #1968FC;
    box-shadow: 0 9px 6px 0 rgba(25,104,252,0.30);
    border-radius: 7.5px;
    font-size: 24px;
    color: #FFFFFF;
    letter-spacing: 0;
    outline: none;
    cursor: pointer;
  }

  ::-webkit-input-placeholder {
    opacity: 0.7;

  }

  :-moz-placeholder { /* Firefox 18- */
    opacity: 0.7;
  }

  ::-moz-placeholder { /* Firefox 19+ */
    opacity: 0.7;
  }

  :-ms-input-placeholder { /* IE 10+ */
    opacity: 0.7;
  }

  ::-ms-input-placeholder { /* Edge */
    opacity: 0.7;
  }

  :placeholder-shown { /* Standard one last! */
    opacity: 0.7;
  }

  .singin-bottom{
    margin-top: 40px;
    text-align: center;
    font-size: 24px;
    font-weight: 500;
  }

  @media screen and (max-width: 1180px) {
    .inner-container{
      width: 95%;
      padding-left: 10px;
      padding-right: 10px;
      display: flex;
      justify-content: center;
    }
  }

  @media screen and (max-width: 1080px) {
    .inner-container{
      width: 100%;
      padding-left: 0;
      padding-right: 0;

    }

    #signin-image{
      /*position: absolute;*/
      /*width: 100%;*/
      /*justify-content: center;*/
      /*float: none;*/
      /*z-index: -5;*/
      /*opacity: 0.4;*/
      display: none;
    }

    #signin-form-container{
      width: 490px;
    }

  }

</style>
