<template>
    <div id="product">
        <div id="title">
            <h1>
                <span>P</span>
                <span>r</span>
                <span>o</span>
                <span>d</span>
                <span>u</span>
                <span>c</span>
                <span>t</span>
            </h1>
        </div>
        <Project />
    </div>
</template>

<script>
import Project from './productComponents/Project.vue' //importするだけでcssが適用される

export default {
  components: {
    Project,
  }
}
</script>

<style>
div#product > div#title > h1 > span {
    font-size: 11vw;
    margin: 0 0.5%;
}

div#product > div#title > h1{
    text-align: center;
    color: #42b883;
	white-space: nowrap;
}
</style>