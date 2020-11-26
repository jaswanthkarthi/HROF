<template>
  <div class="home" style="margin-top: 132px">
    <!-- First container-->
    <div class="homepage-con-1">
      <section class="container-1">
      <section id="homepage-con-1-textcon">
        <section id="homepage-con-1-textbox">
          <div class="bold">We are there for code</div>
          <div class="medium">We build products that empower developers and
            connect them to solutions that enable pro-grow,
            growth, and discovery.</div>
          <div class="button-class">
            <button class="developers-button">Developers</button>
            <button class="Business-button">Business</button>
          </div>
        </section>
      </section>
      <section id="homepage-con-1-image">
        <img src="./../assets/homepage-image-1.png" class="homepage-image-1"> <!--ondragstart="return false"-->
      </section>
      </section>
    </div>

    <!-- Second container-->
<div class="con-2">
    <div class="homepage-con-2">
      <section id="homepage-con-2-title">
        Developers by Developers
      </section>
      <section id="homepage-con-2-maincontent">
        <div class="homepage-box" id="box-1">
          <div class="content">
            <div class="icon">
              <img src="./../assets/design1.png" class="icon-img">
            </div>
            <div class="contenttext">
              <div class="text">Public Q/A</div>
            </div>
          </div>
          <div class="bottom-content">
            <div class="bottom-text">
              Get answers to more than 16.5 million questions and give back by sharing your knowledge with others
            </div>
          </div>
        </div>

        <div class="homepage-box marginleft-67" id="box-2">
          <div class="content">
            <div class="icon">
              <img src="./../assets/design1.png" class="icon-img">
            </div>
            <div class="contenttext">
              <div class="text">Private Q/A</div>
            </div>
          </div>
          <div class="bottom-content">
            <div class="bottom-text">
              Get answers to more than 16.5 million questions and give back by sharing your knowledge with others
            </div>
          </div>
        </div>

        <div class="homepage-box marginleft-67" id="box-3">
          <div class="content">
            <div class="icon">
              <img src="./../assets/design2.png" class="icon-img">
            </div>
            <div class="contenttext">
              <div class="text">Search Jobs</div>
            </div>
          </div>
          <div class="bottom-content">
            <div class="bottom-text">
              Get answers to more than 16.5 million questions and give back by sharing your knowledge with others
            </div>
          </div>
        </div>
      </section>
    </div>
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

  .container-1{
    width: 1115px;
    height: inherit;
    margin: auto;
    padding-left: 25px;
    padding-right: 25px;
  }

  .homepage-con-1{
    height: 354px;
    width: 100%;
  }
  #homepage-con-1-textcon{
    width: 480px;
    height: inherit;
    display: flex;
    float: left;
    justify-content: flex-end;
  }
  #homepage-con-1-image{
    width: 50%;
    height: inherit;
    display: flex;
    justify-content: flex-start;
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
    height: 81px;
    width: 100%;
  }

  .button-class{
    margin-top: 44px;
  }

  .developers-button{
    width: 172px;
    height: 46px;
    font-size: 16px;
    border-radius: 5px;
    box-shadow: 0 6px 4px 0 rgba(25, 104, 252, 0.3);
    border: solid 1px #1968fc;
    display: inline-block;
  }

  .Business-button{
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

  .homepage-con-2{
    width: 1100px;
    margin: auto;
    height: inherit;
  }
  .con-2{
    width: 100%;
    height: 415px;
    margin-top: 135px;
  }

#homepage-con-2-maincontent {
  display: inline-flex;
  flex-wrap: wrap;
  flex-direction:row;
  height: 290px;
  width: inherit;
  margin-top: 77px;
}

  .homepage-box{
    height: 285px;
    width: 320px;
    background-color: white;
    box-shadow: 0 20px 60px 0 rgba(49, 69, 244, 0.1);
  }

  #box-1{
    margin-left: 5px;
  }
  #box-2{
    margin-left: 67px;
  }
  #box-3{
    margin-left: 67px;
  }

  .content{
    height: 41.4%;
    background-color: #F3F7FF;
    width: inherit;

  }

  .icon{
    width: 37.4%;
    height: 100%;
    background-color: aliceblue;
    float: left;
  }

  .icon-img{
    height: 118px;
    width: 118px;
  }

  .contenttext{
    width: 62.6%;
    height: 100%;
    float: right;
    display: flex;
    align-items: center;
  }

  .text{
    font-size: 20px;
    font-weight: 600;
    font-stretch: normal;
    font-style: normal;
    line-height: 1.5;
    letter-spacing: normal;
    color: #11223f;
    margin-left: 20px;
  }

  .bottom-content{
    height: 58.6%;
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
  }




  .bottom-text{
    font-size: 18px;
    font-weight: 600;
    font-stretch: normal;
    font-style: normal;
    line-height: 1.5;
    letter-spacing: normal;
    color: #11223f;
    height: 108px;
    width: 250px;
  }

  #homepage-con-2-title{
    font-size: 35px;
    font-weight: 600;
    font-stretch: normal;
    font-style: normal;
    line-height: normal;
    letter-spacing: normal;
    color: #11223f;
  }

  @media screen and (max-width: 1180px) {
    #homepage-con-1-image{
      position: absolute;
      width: 100%;
      justify-content: center;
      float: none;
      z-index: -5;
      opacity: 0.4;
    }
    .container-1{
      width: 100%;
      padding-left: 0;
      padding-right: 0;
      display: flex;
      align-items: center;
      justify-content: center;
    }

    #homepage-con-2-maincontent{
      flex-direction: column;
      height: unset;
      display: flex;
      align-items: center;
      margin-top: 30px;
    }
    #box-1{
      margin-left: 0;
      margin-top: 10px;
    }
    #box-2{
      margin-left: 0;
      margin-top: 35px;
    }
    #box-3{
      margin-left: 0;
      margin-top: 35px;
    }

    #homepage-con-2-title{
      display: flex;
      justify-content: center;
     }

    .homepage-con-2{
      width: inherit;
    }

    .con-2{
      height: unset;
    }

    .button-class{
      display: flex;
      justify-content: center;
    }

    .bold{
      display: flex;
      justify-content: center;
    }

    .medium{
      text-align: center;
    }
  }

</style>



