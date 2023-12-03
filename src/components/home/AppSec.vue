<template>
  <section class="app-sec mb-5">
    <div class="title">
        <h3>Download the mobile application for bonus coupons and travel codes</h3>
        <button type="button" class="PrimaryButton">Download mobile app</button>
    </div>
   
    <img src="../../assets/images/smartphone.png" />    
  </section>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.app-sec{
    position: relative;
    width: 100%;
    height: 280px;
    min-height: 280px;
    background-image: url('../../assets/images/beach.png');
    background-size: cover;
    background-repeat: no-repeat;
    border-radius: 8px;
    display: flex;
    align-items: center;
    padding-left: 70px;

    .title{
        position: relative;
        z-index: 700;
        h3{
            font-size: 28px;
            max-width: 558px;
            margin-bottom: 30px;
        }
    }

    img{
        position: absolute;
        right: 0;
        top: 0;
        z-index: 500;
    }

    .title{
        h3{
            color: #fff;
            font-size: 28px;
            font-weight: bold;
        }
    }
}
</style>