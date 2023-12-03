<template>
    <footer>
        <div class="container">
            <div class="data">
                <div class="row">
                    <div class="col-lg-4 col-md-4">
                        <div class="column">
                            <h4>my Dream Place</h4>
                            <p>Your next goto companion for travel</p>
                        </div>
                    </div>
                    <div class="col-lg-2 col-md-4">
                        <div class="column">
                            <h4>Company</h4>
                            <ul>
                                <li>
                                    <a href="#">About</a>
                                </li>
                                <li>
                                    <a href="#">Jobs</a>
                                </li>
                                <li>
                                    <a href="#">Newsroom</a>
                                </li>
                                <li>
                                    <a href="#">Advertising</a>
                                </li>
                                <li>
                                    <a href="#">Contact us</a>
                                </li>
                                
                            </ul>
                        </div>
                    </div>
                    <div class="col-lg-2 col-md-4">
                        <div class="column">
                            <h4>Explore</h4>
                            <ul>
                                <li>
                                    <a href="#">Australia</a>

                                </li>
                                <li>
                    
                                    <a href="#">New Zealand</a>
                
                                </li>
                                <li>
                            
                                    <a href="#">United States America (USA)</a>
                
                                </li>
                                <li>
                
                                    <a href="#">Greece</a>
                    
                                </li>
                                <li>
                                    <a href="#">Maldives</a>
                                </li>
                                <li>
            
                                    <a href="#">Singapore</a>

                                </li>
                                <li>
                                    <a href="#" class="seeMore">See more</a>
                                </li>
                            </ul>
                        </div>
                    </div>
                    <div class="col-lg-2 col-md-4">
                        <div class="column">
                            <h4>Terms and Policies</h4>
                            <ul>
                                <li>
                                    <a href="#">Privacy Policy</a>
                                </li>
                                <li>
                                    <a href="#">Terms of use</a>
                                </li>
                                <li>
                                    <a href="#">Acessibility</a>
                                </li>
                                <li>
                                    <a href="#">Reward system policy</a>
                                </li>
                            </ul>
                        </div>
                    </div>
                    <div class="col-lg-2 col-md-4">
                        <div class="column">
                            <h4>Help</h4>
                            <ul>
                                <li>
                                    <a href="#">Support</a>
                                </li>
                                <li>
                                    <a href="#">Cancel your bookings</a>
                                </li>
                                <li>
                                    <a href="#">Use Coupon</a>
                                </li>
                                <li>
                                    <a href="#">Refund Policies</a>
                                </li>
                                <li>
                                    <a href="#">International Travel Documents</a>
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        
    </footer>
    <div class="caption"><div class="container"> &copy; my Dream Place 2022 </div></div>
</template>

<script>
export default {
    name: "footerSec"
}
</script>

<style lang="scss" scoped>
@import "../../assets/scss/_variables.scss";

.column{
    h4{
        color: #000000;
        font-size: 16px;
        font-weight: bold;
    }
    ul{
        margin-top: 20px;
        list-style-type: none;
        margin: 0;
        padding: 0;
        display: flex;
        flex-direction: column;
        li{
            margin-bottom: 5px;
            a{
                text-decoration: none;
                color: $Gray2;
                font-size: 14px;
                &:hover{
                    color: $PrimaryColor;
                }
                &.seeMore{
                    color: $PrimaryColor;
                }
            }
        }
    }
}

.caption{
    background-color: #EBEBEB;
    padding: 5px;
    .container{
        display: flex;
        justify-content: flex-end;
    }
}

</style>