<template>
    <div class="container">
            <nav id="nav" class="header">
                <ul>
                    <li>
                        <RouterLink class="nav" to="/">
                            <span class="menu" id="title_menu">TECHINTERN</span>
                        </RouterLink>
                    </li>
                    <li>
                        <RouterLink class="nav" to="/product">
                            <span class="menu sub_menu">Product</span>
                        </RouterLink>
                    </li>
                    <li>
                        <RouterLink class="nav" to="/blog">
                            <span class="menu sub_menu">Blog</span>
                        </RouterLink>
                    </li>
                    <li>
                        <RouterLink class="nav" to="/portfolio">
                            <span class="menu sub_menu">Portfolio</span>
                        </RouterLink>
                    </li>
                    <li>
                        <RouterLink class="nav" to="/about">
                            <span class="menu sub_menu">About</span>
                        </RouterLink>
                    </li>
                </ul>
            </nav>
            <div id="main">
                <transition name="slide" mode="out-in">
                    <RouterView />
                </transition>
            </div>
    </div>
</template>


<style scoped>
.header ul {
    margin-top:30px;
    padding: 0;
}
.header ul li {
    display: inline-block;
    vertical-align: middle;
    list-style: none;
}

.nav{
    text-decoration: none;
}
.menu {
    color: #000;
    font-size: 14px;
    font-family: 'Montserrat', sans-serif;
    font-weight: 600;
    text-indent: 0.05em;
    letter-spacing: 0.05em;
}
.sub_menu {
    padding: 20px;
}
.menu-exact-active {
    color: lightgreen;
}
.slide-enter-active {
    transition: all .8s ease;
}
.slide-leave-active {
    transition: all .8s cubic-bezier(1.0, 0.5, 0.8, 1.0);
}
.slide-enter, .slide-leave-to
/* .slide-fade-leave-active below version 2.1.8 */ {
    transform: translateY(10px);
    opacity: 0;
}
#title_menu {
    font-weight: 600;
    font-size: 20px;
    padding-right:20px;
}
</style>


<style>
#title h1 {
    margin-top: 100px;
}
#title h1 span{
    font-size: 137px;
    font-family: 'Monteserrat', sans-serif;
    font-weight: 600;
    line-height: 1;
    text-transform: uppercase;
    text-align: left;
    letter-spacing: 0;
}

#title h1 span:nth-child(even){
    color: transparent;
    text-align: left;

    -webkit-text-stroke: 2px #000;
}


</style>


<script>

</script>