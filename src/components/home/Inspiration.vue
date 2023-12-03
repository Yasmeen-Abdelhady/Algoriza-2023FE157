<template>
  <div class="sec_title">
    <h3>Get inspiration for your next trip</h3>
  </div>
  <div class="row mb-5">
    <div class="col-lg-4 col-md-6 col-12">
      <div class="card">
        <div class="card-image">
          <img src="../../assets/images/Rectangle 8.png" alt="sea"/>
        </div>
        <div class="card-body">
          <div class="card-title">Sydeny’s 10 most fashionable 5 star hotels</div>
          <div class="card-text">Browse the fastest growing tourism sector in the heart of Australia tourism capital ....</div>
        </div>
      </div>
    </div> 
    <div class="col-lg-4 col-md-6 col-12">
      <div class="card">
        <div class="card-image">
          <img src="../../assets/images/Rectangle 16.png" alt="sea"/>
        </div>
        <div class="card-body">
          <div class="card-title">Sydeny’s 10 most fashionable 5 star hotels</div>
          <div class="card-text">Browse the fastest growing tourism sector in the heart of Australia tourism capital ....</div>
        </div>
      </div>
    </div>
    <div class="col-lg-4 col-md-6 col-12">
      <div class="card">
        <div class="card-image">
          <img src="../../assets/images/Rectangle 17.png" alt="sea"/>
        </div>
        <div class="card-body">
          <div class="card-title">Sydeny’s 10 most fashionable 5 star hotels</div>
          <div class="card-text">Browse the fastest growing tourism sector in the heart of Australia tourism capital ....</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
    name: "InspirationSec"
}
</script>

<style lang="scss" scoped>
@import "../../assets/scss/_variables.scss";

.sec_title{
  h3{
    color: $TitleColor;
    font-size: 28px;
    font-weight: bold;
  }
  p{
    color: $Gray3;
    font-size: 16px;
    max-width: 610px;
  }
}
.card{
    position: relative;
  .card-image{
    overflow: hidden;
    border-radius: 8px;
    height: 100%;
    width: 100%;
    img{
      width: 100%;
      height: 100%;
    }
  }
  .card-body{
    position: absolute;
    display: flex;
    flex-direction: column;
    justify-content: flex-end;
    height: 100%;
    width: 100%;
        .card-title{
        color: #fff;
        font-size: 20px;
        font-weight: bold;
        }
        .card-text{
        font-size: 14px;
        color: #fff;
        }
    }
}
</style>