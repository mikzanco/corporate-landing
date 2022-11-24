<script>

import MainWWD from './partials/MainWWD.vue';
import MainGYB from './partials/MainGYB.vue';
import MainLW from './partials/MainLW.vue';
import MainOpLp from './partials/MainOp&Lp.vue';
import MainWPS from './partials/MainWPS.vue';

export default {
    name: 'AppMain',
    components:{
        MainWWD,
        MainGYB,
        MainLW,
        MainOpLp,
        MainWPS
    }
}
</script>

<template>
  <main>
    <MainWWD/>
    <MainGYB/>
    <MainLW/>
    <MainOpLp/>
    <MainWPS/>
  </main>
</template>



<style lang="scss" scoped>
    @use '../style/partials/variables' as *;

</style>