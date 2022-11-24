<script>

import Jumbotron from './jumbotron.vue'

export default {
    name: 'AppHeader',
    components:{
        Jumbotron,
    }
}
</script>

<template>
  <header>
    <div class="container">
        <div class="container-hea d-flex">
            <div class="logo p-2">
                <img src="/white-logo-2.png" alt="Phlox Corporated">
            </div>
            <div class="nav ">
                <ul class="list d-flex">
                    <li>Home</li>
                    <li>About</li>
                    <li>Services</li>
                    <li>Blog</li>
                    <li>Contact</li>
                    <li>Portfolio</li>
                    <button class="blue"><span>Sign In</span></button>
                </ul>
            </div>
        </div>
        <div class="container-jumbotron">
            <Jumbotron/>
        </div>
        
    </div>
    
  </header>
</template>



<style lang="scss" scoped>
    @use '../style/partials/variables' as *;
    header{
        height: 700px;
        max-width: 100vw;
        background: linear-gradient(185deg, rgba(82,124,235,1) 0%, rgba(0,0,0,1) 81%);
        .container-hea{ 
            justify-content: space-between;
            .nav .list li{
                padding: 20px;
                list-style-type: none;
                &:hover{
                    color: rgba(249,99,107,1);
                }

            }
            button{
                height: 40px;
                margin-top: 10px;
                padding: 5px;
                border-radius: 20px;
                border: none;
                background: linear-gradient(153deg, rgba(3,167,211,1) 0%, rgba(82,124,235,1) 60%);
                span{
                    padding: 10px;
                    color: white;
                    font-size: 0.9rem;
                }
            }
        }
    }

</style>