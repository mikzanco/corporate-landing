<script>
export default {
    name: 'Lp',
}
</script>

<template>

    <div class="main4-2">
        <div class="d-flex flex-column justify-content-center align-items-center pt-5">
            <p class="red-text">Blog</p>
            <h2><strong>Latest</strong>Post</h2>
            <p class="gray-color mt-2">When, while the lovely valley teems with vapour around meand the upper surface.</p>
        </div>
        <div class="container d-flex p-5  justify-content-center">
            <div class="col-6 justify-content-center m-3 ">
                <img src="../../assets/img/headway-537308-unsplash-1380x703.jpg" alt="">
            </div>
            <div class="col-3 justify-content-center m-3 ">

            </div>
            <div class="col-3 justify-content-center m-3 ">

            </div>
        </div>
    </div>
  
</template>


<style lang="scss" scoped>
    @use '../../style/partials/variables' as *;
    
    .main4-2{
        padding-top: 200px;
        width: 100vw;
        height: 1000px;
        h2{
            color: black;
        }
        .container{
            height: 500px;
            
        }
        .col-3{
            background-color: #283c71;
            border-radius: 50px;
        }
        .col-6{
            
            border-radius: 50px ;
            img{
                width: 100%;
                height: 100%;
                border-radius: 50px;
            }
        }
    }

</style>