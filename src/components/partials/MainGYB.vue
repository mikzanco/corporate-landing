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
    }

</style>