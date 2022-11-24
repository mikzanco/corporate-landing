<script>

import FooterBottom from './partials/FooterBottom.vue'

export default {
    name: 'AppFooter',
    components:{
        FooterBottom,
    }
}
</script>

<template>
  <footer>
    <div class="container">
        <div class="ul d-flex">
            <div class="logo col-3 align-items-center">
                <img src="../assets/img/white-logo-2.png" alt="Phlox Corporated">
                <p>When, while lovely valley teems vapour aroundmeand meridian sun strikes the upper impenetrable</p>
            </div>
            <div class="col-3">
                <span>Quick Links</span>
                <ul>
                    <li>Services</li>
                    <li>Contact</li>
                    <li>Blog</li>
                </ul>
            </div>
            <div class="col-3">
                <span>Resources</span>
                <ul>
                    <li>Art Design</li>
                    <li>Computer</li>
                    <li>IT News</li>
                    <li>Networking</li>
                    <li>Web Security</li>
                </ul>
            </div>
            <div class="col-3">
                <span>Contact Us</span>
                <ul>
                    <li><Span>Addres:</Span>Patricia C. Amedee 4401 Waldeck Street Grapevine NashVille, Tx 76051</li>
                    <li><Span>Phone:</Span>+99 (0) 101 0000 888</li>
                    <li><Span>Email:</Span>Info@yourdomain.com</li>
                </ul>
            </div>
        </div>
        
    </div>
    <FooterBottom/>
  </footer>
  
</template>



<style lang="scss" scoped>
    @use '../style/partials/variables' as *;
    footer{
        height: 500px;
        max-width: 100vw;
        background: linear-gradient(180deg, rgba(82,124,235,1) 0%, rgba(0,0,0,1) 81%);
        color: $secondary-color-text;
        padding-top: 200px;
        .col-3{
            padding-left: 20px;
            span{
                color: white;
                font-weight: 700;
                padding-left: 20px;
            }
        }
        li{
            list-style-type: none;
            span{
                color: white;
            }
        }
    }
</style>