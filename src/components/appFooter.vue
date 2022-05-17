<template>
    <div>
        <div class="container">
            <div class="row">
                <div class="col-6">
                    <ul>
                        <li>{{myDataFooter[0].title}}</li>
                    </ul>
                    </div>
                <div class="col-2">grthbtr</div>
                <div class="col-2">hwrshb</div>
                <div class="col-2">rthwrhtrshr56</div>
            </div>
        </div>
    </div>
</template>

<script>
import datiFooter from '../datiFooter.json'
export default {
    name: 'AppFooter',
    data(){
        return{
            myDataFooter: datiFooter
        }
    }
}
</script>

<style lang="scss" scoped>

</style>