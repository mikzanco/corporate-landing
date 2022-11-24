<script>
export default {
    name: 'MainGYB',
}
</script>

<template>

    <div class="main2 d-flex align-items-center">
        <div class="imgs">
            <img class="front" src="../../assets/img/men-data.png" alt="">
            <img class="back" src="../../assets/img/nemoodar.png" alt="">
        </div>
        <div class="text">
            <p>Start Your project</p>
            <h2><strong>Grow Your Business</strong></h2>
            <h2>With Our Strategy</h2>
            <p class="blue">When, while the lovely valley teems with vapour around meand the meridian sun strikes the upper surface.of the impenetrambe follage of my trees, and but a few stray gleams steal into the inner sanctuary</p>
            <div class="button d-flex">
            <button class="red"><span>Try It Now</span> </button>
            <button ><span>Explore More</span></button>
        </div>
        </div>
    </div>
  
</template>


<style lang="scss" scoped>
    @use '../../style/partials/variables' as *;
    .main2{
        width: 100vw;
        height: 500px;
        background: linear-gradient(185deg, rgba(82,124,235,1) 0%, rgba(0,0,0,1) 81%);
        .imgs{
            width: 50%;
            height: 100%;
            position: relative;
            img.front{
                height: 350px;
                position: absolute;
                right: 100px;
                top: 70px;
                z-index: 2;
            }
            img.back{
                height: 350px;
                position: absolute;
                right: 150px;
                top: 50px;
                z-index: 1;
            }
        }
        .text{
            
            width: 40%;
            
            height: 100%;
            display: flex;
            flex-direction: column;
            justify-content: center;
            padding: 50px;
            h2{
                font-size: 3.2rem;
                
            }
            .blue{
                padding-top: 20px;
                color: $primary-color;
            }
            button{
                height: 40px;
                margin-top: 10px;
                padding: 5px;
                border-radius: 20px;
                border: none;
                margin: 20px;

                span{
                    padding: 30px;
                }
            }
        }
    }

</style>