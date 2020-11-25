<template>
  <div class="home" style="margin-top: 132px">
    <div class="homepage-con-1">
      <section id="homepage-con-1-textcon">
        <section id="homepage-con-1-textbox">
          <div class="bold">We are there for code</div>
          <div class="medium">We build products that empower developers and
            connect them to solutions that enable productivity,
            growth, and discovery.</div>
          <div style="margin-top: 20px;">
            <button class="developers-button">Developers</button>
            <button class="Business-button">Business</button>
          </div>
        </section>
      </section>
      <section id="homepage-con-1-image">
        <img src="./../assets/homepage-image-1.png" class="homepage-image-1" ondragstart="return false">
      </section>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'Home',
  components: {}
}
</script>
<style>
  .homepage-con-1{
    height: 354px;
    width: 100%;
  }
  #homepage-con-1-textcon{
    width: 46%;
    height: inherit;
    display: flex;
    float: left;
    justify-content: flex-end;
  }
  #homepage-con-1-image{
    width: 50%;
    height: inherit;
    display: flex;
    justify-content: center;
    float: right;
  }
  .homepage-image-1{
    width: 568px;
    height: inherit;
  }
  #homepage-con-1-textbox{
    height: 231px;
    width: 476px;
    text-align: unset;
    margin-top: 66px;
  }
  .bold{
    font-size: 35px;
    font-weight: 600;
    font-stretch: normal;
    font-style: normal;
    line-height: normal;
    letter-spacing: 1px;
    color: #11223f;
    text-align: unset;
  }

  .medium{
    font-size: 20px;
    font-weight: 500;
    font-stretch: normal;
    font-style: normal;
    line-height: normal;
    letter-spacing: 0.5px;
    color: #11223f;
    margin-top: 20px;
    text-align: unset;
  }

  .developers-button{
    width: 172px;
    height: 46px;
    font-family: 'Proxima Nova';
    font-size: 16px;
    border-radius: 5px;
    box-shadow: 0 6px 4px 0 rgba(25, 104, 252, 0.3);
    border: solid 1px #1968fc;
    display: inline-block;
  }

  .Business-button{
    font-family: 'Proxima Nova';
    font-size: 16px;
    color: #ffffff;
    width: 172px;
    height: 46px;
    border-radius: 5px;
    box-shadow: 0 6px 4px 0 rgba(25, 104, 252, 0.3);
    background-color: #1968fc;
    margin-left: 15px;
    display: inline-block;
  }

</style>