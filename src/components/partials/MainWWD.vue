<script>
export default {
    name: 'MainWhatWeDo',
}
</script>

<template>
    <div class="main1">
        <div class="container ">

            <div class="d-flex flex-column justify-content-center align-items-center mt-5">
                <p class="red-text">Our Services</p>
                <h2><strong>What</strong> We Do</h2>
                <p class="gray-color mt-2">When, while the lovely valley teems with vapour around meand the</p>
            </div>

            <!-- successivamente da ricreare in store un array per ricreare le quattro schede con un ciclo -->
            <div class="functions d-flex p-5  justify-content-center">
                <div class="col-3 justify-content-center m-2 p-4">
                    <img src="../../assets/img/Group-247.png" alt="">
                    <h3><strong>Data Analysis</strong></h3>
                    <p class="gray-color mt-2 ">When, while the lovely valley teems with vapour around meand the meridian sun strikes the upper</p>
                </div>
                <div class="col-3 justify-content-center m-2 p-4">
                    <img src="../../assets/img/Group-567.png" alt="">
                    <h3><strong>Data Analysis</strong></h3>
                    <p class="gray-color mt-2 ">When, while the lovely valley teems with vapour around meand the meridian sun strikes the upper</p>
                </div>
                <div class="col-3 justify-content-center m-2 p-4">
                    <img src="../../assets/img/Group-538.png" alt="">
                    <h3><strong>Data Analysis</strong></h3>
                    <p class="gray-color mt-2 ">When, while the lovely valley teems with vapour around meand the meridian sun strikes the upper</p>
                </div>
                <div class="col-3 justify-content-center m-2 p-4">
                    <img src="../../assets/img/Group-566.png" alt="">
                    <h3><strong>Data Analysis</strong></h3>
                    <p class="gray-color mt-2 ">When, while the lovely valley teems with vapour around meand the meridian sun strikes the upper</p>
                </div>
            </div>
            <div class="d-flex justify-content-center">
                <button class="d-flex justify-content-center">View All Services</button>
            </div>
            
        </div>
    </div>
    
</template>


<style lang="scss" scoped>
    @use '../../style/partials/variables' as *;
    .main1{
        width: 100vw;
        height: 800px;
        color: black;
        h2{
            font-size: 3rem;
        }
        .col-3{
            height: 400px;
            // background-color: red;
            display: flex;
            flex-direction: column;
            align-items: center;
            img{
                height: 200px;
                width: 150px;
                padding-bottom: 50px;
            }
            p{
                text-align: center;
            }
        }
        button{
                height: 40px;
                width: 200px;
                margin-top: 10px;
                padding: 5px;
                border-radius: 20px;
                border: none;
                color: white;
                background: linear-gradient(267deg, rgba(249,99,107,1) 0%, rgba(182,36,110,1) 60%);;
                span{
                    padding: 10px;
                    color: white;
                    font-size: 0.9rem;
                }
            }
    }
</style>