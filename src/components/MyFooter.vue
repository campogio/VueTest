<template>
  


<section>


<footer>
            <div class="container-lg">
                <div class="box-footer-header">

                    <!-- BOX LOGO FOOTER -->
                    <div class="box-item-header">
                        <div class="box-logo-header">
                            <img src="./footer-logo.png" alt="footer-logo">
                        </div>

                        <div class="box-text-footer">
                            <p>We are specialists in the construction of unique and exclusive properties. Our work inspires. We pride ourselves on delivering outstanding quality and design for leading clients across the world.</p>
                        </div>

                        <div class="box-btn-footer">
                            <a href="#">learn more</a>
                        </div>
                    </div>
                    <!-- /BOX LOGO FOOTER -->
    
                    <!-- BOX LATEST -->
                    <div class="box-item-header">
                        <h2>latest tweets</h2>
                        <div class="box-spot-header">
                            <div class="box-logo-spot">
                                <img src="./3a74ce3d0532b7773b174c45ca3bd05a_normal.png" alt="normal">
                            </div>
                            <div class="box-item-spot">
                                <div class="container-spot">
                                    <div class="box-right">
                                        <h5>ThemeFusion</h5>
                                        <p>@Theme_Fusion</p>
                                    </div>
    
                                    <div class="box-left">
                                        <i class="fab fa-twitter"></i>
                                    </div>
                                </div>
                                <div class="box-text-spot">
                                    <p>Do you need sublime Wordpress hosting for your next website? Take advantage of exclusive partner offers that we have secured just for you, &amp; launch your site in seconds with <span>#avada</span> on WP Engine Hosting &amp; get 30% Off This Black Friday <span>bit.ly/3kjLLE2#BlackFriday2020</span></p>
                                </div>

                                <div class="box-img-spot">
                                    <img src="./En2TRxLW4AEiWUN.jpeg" alt="En2TRxLW4AEiWUN">
                                </div>

                                <div class="box-icon-spot">
                                    <div class="box-icon-right">
                                        <i class="far fa-heart"></i>
                                        <i class="fas fa-sign-out-alt"></i>
                                    </div>
                                    <div class="box-icon-left">
                                        <small>22h</small>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <!-- / BOX LATEST -->
    
                    <!-- BOX CONTACT-->
                    <div class="box-item-header">
                        <div class="box-title-contacts">
                            <h2>contacts us today</h2>
                        </div>
                        <div class="box-item-contacts">
                            <ul>
                                <li>
                                    <i class="fas fa-globe"></i>
                                    <span>Corporate Location
                                        1600 Amphitheatre Parkway
                                        London WC1 1BA</span>
                                </li>
                                <li>
                                    <i class="fas fa-home"></i>
                                    <span>Residential Location
                                        9521 Broadsberry Avenue
                                        Paddington RC7 9ZA</span>
                                </li>
                                <li>

                                </li>
                                <li>
                                    <i class="fas fa-phone"></i>
                                    <span>1.800.458.556 / 1.800.532.2112</span>
                                </li>
                                <li>
                                    <i class="far fa-envelope"></i>
                                    <span>info@your-domain.com</span>
                                </li>
                                <li>
                                    <i class="far fa-envelope"></i>
                                    <span>Monday - Friday: 9:00 AM - 6:00 PM</span>
                                </li>
                                <li>
                                    <i class="far fa-envelope"></i>
                                    <span>Saturday - Sunday: 9:00 AM - 12:00 PM</span>
                                </li>
                            </ul>
                        </div>
                    </div>
                    <!-- /BOX CONTACT-->
    
                    <!-- BOX MAPP -->
                    <div class="box-item-header">
                        <div class="box-title-find">
                            <h2>find us</h2>
                        </div>
                        <div class="box-img">
                            <img src="./staticmap-construction.png" alt="staticmap">
                        </div>
                    </div>
                    <!-- / BOX MAPP -->
                </div>
            </div>
    
                <div class="box-footer-bottom">
                    <div class="container-lg">
                        <div class="box-item-footer-bottom">

                            <div class="box-copyright">
                                <small>COPYRIGHT 2012 - 2015 AVADA THEME BY THEME FUSION   |   ALL RIGHTS RESERVED   |   POWERED BY WORDPRESS</small>
                            </div>
                            <div class="box-link-social">
                                <i class="fab fa-facebook-f"></i>
                                <i class="fab fa-twitter"></i>
                                <i class="fab fa-youtube"></i>
                                <i class="fab fa-instagram"></i>
                            </div>
                        </div>

                    </div>
                </div>

        </footer>




</section>

</template>

<script>
export default {
    name: 'MyFooter'

}
</script>

<style lang="scss" scoped>

/* FOOTER */
footer{
    background-color: #f1eaea;

    background-color: #333333;
}

footer .box-footer-header{
    width: 100%;
    display: flex;
    justify-content: space-around;
    padding: 40px 0;
}

footer .box-item-header{
    width: 293px ;
    height: 400px;
}

footer .box-text-footer{
    padding: 30px 0;
    line-height: 1.6;
    color: #f1eaea;
}

footer .box-footer-bottom{
    width: 100%;
    height: 70px;
    background-color: #000;
}

footer .box-spot-header{
    display: flex;
    padding: 20px 0;
}

footer .box-item-header h2,
footer .box-title-contacts h2,
footer .box-title-find h2{
    color:#fed03d;
    text-transform: uppercase;
}

footer .container-spot{
    display: flex;
    justify-content: space-between;
    width: 100%;
}

footer .box-item-spot{
    width: 100%;
}

footer.box-item-spot h5{
    color: #fff;
}

footer .box-item-spot p,
footer .box-item-spot i{
    color: #666665;
}

footer .box-text-spot{
    text-align: justify;
    font-size: 0.8em;
    padding: 10px;
}

footer .box-text-spot span {
    color: rgb(46, 13, 165);
    cursor: pointer;
}

footer .box-img-spot img{
    width: 100%;
}

footer .box-icon-spot{
    display: flex;
    justify-content: space-between;
}

footer .box .icon-right{
    height: 30px;
    width: 80%;
}

footer .box-icon-right i{
    margin-right: 8px;
}

footer .box-icon-left{
    color: #727272;
    font-size: 0.9em;
}

footer .box-item-contacts{
    color: #66666e;
}

footer .box-item-contacts ul li {
    margin: 15px 0;
    font-size: 0.8em;
    line-height: 1.6;
}

footer .box-item-contacts i{
    margin-right: 6px;
}

footer .box-img{
    margin-top: 20px;
}

footer .box-img img{
    width: 100%;
}

footer .box-item-footer-bottom{
    display: flex;
    color: #fff;
    justify-content: space-between;
}

.box-copyright{
    height: 100%;
    display: flex;
    justify-content: center;
    line-height: 70px;
}

.box-link-social{
    line-height: 70px;
}

.box-link-social i {
    margin-right: 15px;
}
/* / FOOTER */

.box-link-rewind{
    bottom: 10px;
    right: 10px;
    position: fixed;
}

.box-link-rewind a{
    color: #fff;
    padding: 10px;
    background-color: #747474ad;
}



</style>