<template>
    <div>
        <div class="container">
            <div class="row">
                <div class="col-6">
                    <ul>
                        <li class="h5">{{myDataFooter[0].title}}</li>
                        <li>{{myDataFooter[1].street}}</li>
                        <li>{{myDataFooter[2].info}}</li>
                        <li>{{myDataFooter[3].mail}}</li>
                        <li>
                            <i class="fa-brands fa-facebook icons"></i>
                            <i class="fa-brands fa-twitter icons"></i>
                            <i class="fa-brands fa-instagram icons"></i>
                            <i class="fa-brands fa-linkedin icons"></i>
                        </li>
                    </ul>
                    </div>
                <div class="col-2">
                    <ul>
                        <li v-for="dato in NewDataFooter" :key="dato"><a href="#"></a>{{dato.link}}</li>
                    </ul>
                </div>
                <div class="col-2">
                    <ul>
                        <li></li>
                        <li v-for="dato in NewDataFooter" :key="dato"><a href="#"></a>{{dato.linkB}}</li>
                    </ul>
                </div>
                <div class="col-2">
                    <ul>
                        <li v-for="dato in NewDataFooter" :key="dato"><a href="#"></a>{{dato.info}}</li>
                    </ul>
                </div>
            </div>
        </div>
        <div class="container text-center">
            <p class="fs-6">© 2020 MaxCoach. All Rights Reserved</p>
        </div>
    </div>
</template>

<script>
import datiFooter from '../datiFooter.json'
export default {
    name: 'AppFooter',
    data(){
        return{
            myDataFooter : datiFooter,

            NewDataFooter:[{
                link: 'Explore',
                info: 'Information'
            },
            {
                link: 'Start Here',
                linkB:'Success story',
                info: 'Membership'
            },
            {
                link: 'Blog',
                linkB:'Courses',
                info: 'Purchase guides'
            },
            {
                link: 'About Us',
                linkB:'Contact Us',
                info: 'Privacy policy'
            },
            {
                info: 'Term of services'
            }
                
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
.icons{
    font-size: 18px;
    padding: 10px;
}

</style>