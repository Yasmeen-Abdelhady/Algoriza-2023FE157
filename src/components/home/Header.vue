<template>
  <section class="header_sec">
    <div class="container">
        <div class="main_header">
            <div class="text">
                <h2>Enjoy Your Dream Vacation</h2>
                <p>Plan and book our perfect trip with expert advice, travel tips, destination information and  inspiration from us</p>
            </div>
        </div>
    </div>
  </section>
</template>

<script>
export default {
    name: "headerSec"
}
</script>

<style lang="scss" scoped>
.header_sec{
    width: 100%;
    height: calc(95vh - 68px);
    .container{
        height: 100%;
        .main_header{
            height: 100%;
            width: 100%;
            position: relative;
            display: flex;
            align-items: center;
            justify-content: center;
            background-image: url('../../assets/images/header-img.png');
            background-size: cover;
            background-repeat: no-repeat;
            background-position: right center;
            border-radius: 10px;
            .text{
                color: #fff;
                text-align: center;
                h2{
                    font-size: 32px;
                    font-weight: 700;
                    text-transform: capitalize;
                    margin-bottom: 20px;
                }
                p{
                    font-size: 20px;
                    max-width: 650px;
                }
            }
        }
    }
}
</style>