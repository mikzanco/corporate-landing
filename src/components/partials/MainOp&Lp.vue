<script>

import Op from './Op.vue'
import Lp from './Lp.vue'

export default {
    name: 'MainOp&Lp',
    components:{
        Op,
        Lp,
    }
}
</script>

<template>

    <div class="main4">
        <Op/>
        <div class="centerCard">
        
        </div>
        <Lp/>
    </div>
  
</template>


<style lang="scss" scoped>
    @use '../../style/partials/variables' as *;
    .main4{
        position: relative;
        min-width: 100vw;
        height: 1500px;
        
    }

</style>