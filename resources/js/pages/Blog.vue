<template>
    <div id="blog">
        <div id="title">
            <h1>
                <span>B</span>
                <span>l</span>
                <span>o</span>
                <span>g</span>
            </h1>
        </div>
        <!-- <div class="main" v-for="title of titles" :key="title">
                <div>
                    <b-card
                        title="aaa"
                        img-src="https://picsum.photos/600/300/?image=25"
                        img-alt="Image"
                        img-top
                        tag="article"
                        style="max-width: 20rem;"
                        class="mb-2"
                    >
                        <b-card-text>
                        {{ title }}
                        </b-card-text>

                        <b-button href="#" variant="primary">Go somewhere</b-button>
                    </b-card>
                </div>
            </div> -->
    </div>
</template>



<script>
// import axios from 'axios'
// export default {
//     data () {
//     return {
//         titles: []
//     }
//     },
//     mounted () {
//         axios
//             .get('https://note.com/kai123note/rss',{
//                 timeout: 3000,
//                 responseType: 'document'
//             })
//             .then(response => {
//                 const xml = response.data
//                 const areas = xml.getElementsByTagName('title');
//                 for (let i = 0;  i < areas.length; i++) {
//                 this.titles.unshift(areas[i].textContent);
//                 }
//                 console.log(this.titles)

//         })
//     }

// }
</script>
<style scoped>
.main{
    max-width: 100px;
    padding:0;
}
.main div{
    display: inline-block;
}
</style>