<script>

export default {
    name: 'FooterBottom',
}
</script>

<template>
  <div class="all col-12">
    <div class="container d-flex align-items-center">
        <div>
            <span>c 2020 Phlox. All Rights Reserved.</span>
        </div>
        <div class="social d-flex">
            <ul class="d-flex">
                <li><i class="fa-brands fa-instagram"></i></li>
                <li><i class="fa-brands fa-linkedin-in"></i></li>
                <li><i class="fa-brands fa-facebook-f"></i></li>
                <li><i class="fa-brands fa-twitter"></i></li>
            </ul>
        </div>
    </div>
  </div>
</template>



<style lang="scss" scoped>
     @use '../../style/partials/variables' as *;
    .all{
        background-color: black;
        width: 100vw;
        height: 100px;
        border-top: 1px solid lightgray;
        .container{
            justify-content: space-between;
            color: $secondary-color-text;
            .social ul li{
                list-style-type: none;
                padding: 20px;
                color: white;
            }
        }
    }
   
</style>