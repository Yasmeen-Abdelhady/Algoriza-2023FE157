<template>
  <div class="sec_title">
    <h3>Enjoy your dream vacation</h3>
    <p>Plan and book our perfect trip with expert advice, travel tips, destination information and  inspiration from us</p>
  </div>
  <div class="row mb-5">
    <div class="col-lg-3 col-md-6 col-12">
      <div class="card">
        <div class="card-image">
          <img src="../../assets/images/sea.png" alt="sea"/>
        </div>
        <div class="card-body">
          <div class="card-title">Australia</div>
          <div class="card-text">2246 properties</div>
        </div>
      </div>
    </div> 
    <div class="col-lg-3 col-md-6 col-12">
      <div class="card">
        <div class="card-image">
          <img src="../../assets/images/vacation 1.png" alt="sea"/>
        </div>
        <div class="card-body">
          <div class="card-title">Japan</div>
          <div class="card-text">1278 properties</div>
        </div>
      </div>
    </div> 
    <div class="col-lg-3 col-md-6 col-12">
      <div class="card">
        <div class="card-image">
          <img src="../../assets/images/Rectangle 10.png" alt="sea"/>
        </div>
        <div class="card-body">
          <div class="card-title">New Zealand</div>
          <div class="card-text">480 properties</div>
        </div>
      </div>
    </div> 
    <div class="col-lg-3 col-md-6 col-12">
      <div class="card">
        <div class="card-image">
          <img src="../../assets/images/Rectangle 11.png" alt="sea"/>
        </div>
        <div class="card-body">
          <div class="card-title">Greece</div>
          <div class="card-text">320 properties</div>
        </div>
      </div>
    </div> 
  </div>
</template>

<script>
export default {

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
  .card-image{
    overflow: hidden;
    border-radius: 8px;
    height: 220px;
    width: 100%;
    img{
      width: 100%;
    }
  }
  .card-body{
    .card-title{
      color: $TitleColor;
      font-size: 20px;
      font-weight: bold;
    }
    .card-text{
      font-size: 14px;
      color: $TitleColor;
    }
  }
}
</style>