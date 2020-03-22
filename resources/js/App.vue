<template>
    <div>
        <main>
            <div class="container">
                    <nav class="header">
                        <ul>
                            <li>
                                <RouterLink class="nav" to="/">
                                    <span class="menu">Home</span>
                                </RouterLink>
                            </li>
                            <li>
                                <RouterLink class="nav" to="/product">
                                    <span class="menu">Product</span>
                                </RouterLink>
                            </li>
                            <li>
                                <RouterLink class="nav" to="/blog">
                                    <span class="menu">Blog</span>
                                </RouterLink>
                            </li>
                            <li>
                                <RouterLink class="nav" to="/portfolio">
                                    <span class="menu">Portfolio</span>
                                </RouterLink>
                            </li>
                            <li>
                                <RouterLink class="nav" to="/about">
                                    <span class="menu">About</span>
                                </RouterLink>
                            </li>
                        </ul>
                    </nav>
                <RouterView />
            </div>
        </main>
    </div>
</template>


<style scoped>

.header ul {
    display: flex;
}
.header ul li {
    list-style: none;
}
.nav{
    text-decoration: none;
}
.menu {
    font-size: 14px;
    font-family: 'Montserrat', sans-serif;
    font-weight: 600;
    text-indent: 0.05em;
    letter-spacing: 0.05em;
    text-align: center;
    padding: 20px;
}
</style>