<script>
export default {
    name: 'Jumbotron',
}
</script>

<template>
  <div class="jumbotron d-flex">
    <div class="text pt-5">
        <div>
            <h1> <span>Business Planing Digital</span>  Technology <span>Modern Solution!</span> </h1>
        </div>
        <div>
            <p>When, while the lovely valley teems with vapour around meand the meruduan sun strikes the upper surface.</p>
        </div>
        <div class="button d-flex">
            <button class="red"><span>Try It Now</span> </button>
            <button class="blue"><span>Explore More</span></button>
        </div>
    </div>
    <div class="img-header d-flex">
        <img src="../assets/img/header.png" alt="img jumbotron man and desktop">
    </div>
  </div>
</template>



<style lang="scss" scoped>

@use '../style/partials/variables' as *;
    .jumbotron{
        height: calc(700px - 80px);
        padding-top: 10px;
        .text{
            width: 40%;
            height: 95%;
            
            ;
            h1{
                font-size: 3.5rem;
                span{
                font-weight: 700;
            }
            }
            p{
                padding-top: 30px;
                color: $primary-color;
                
            }
            button{
                height: 40px;
                margin-top: 10px;
                padding: 5px;
                border-radius: 20px;
                border: none;
                margin: 20px;
                .blue{
                    background: linear-gradient(153deg, rgba(3,167,211,1) 0%, rgba(82,124,235,1) 60%);
                }
                .red{
                    background: linear-gradient(267deg, rgba(249,99,107,1) 0%, rgba(182,36,110,1) 60%);
                }
                span{
                    padding: 30px;
                }
            }
            
        }
        .img-header{
            width: 60%;
            height: 95%;
            justify-content: center;
            img{
                
                height: 500px;
                object-fit: cover;
            }
        }
    }
</style>