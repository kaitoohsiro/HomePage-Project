<template>
    <div id="home">
        <div class="display">
            <div class="home">
                <div id="title" class="messages">
                    <span>
                        Everybody
                    </span>
                    <br>
                    <span>
                        has
                    </span>
                    <br>
                    <span>
                        talent
                    </span>
                </div>
                <div class="v_line_fix"></div>
            </div>
        </div>
            <div class="common product">
                <h1>product</h1>
            </div>
            <div class="common blog">
                <h1>blog</h1>
                </div>
            <div class="common portfolio">
                <h1>portfolio</h1>
            </div>
            <div class="common about">
                <h1>about</h1>
            </div>
            <div class="footer">footer</div>
    </div>
</template>

<style scoped>
/* COMMON */
#home {
    background: url(../../images/home1.jpg);
    background-size: cover;
    height: 100vh;
    z-index: 1;
    font-size: 62.5%;
}
.common {
    border: 1px solid #000;
    height: 200px;
    z-index: 30;
    background-color: #999;
}
.common:nth-child(even) {
    background-color: #E8E8E8;
}
/* HOME */
.home {
    width: 100%;
    height: 70vh;
    padding-top: 150px;
    z-index: 10;
}
.home .messages span {
    font-size: 5vw;
    font-family: garamond-premier-pro-display, serif;
    line-height: 1;
    text-transform: uppercase;
    text-align: left;
    letter-spacing: 20px;
    color: #ffffff;
    margin: 0% 10% 60%;
    margin-top: 40%;
}
.v_line_fix {
    width: 1.3px;
    background-color: rgb(251, 251, 249);
    margin-top: 8%;
    margin-left: 90%;
    animation: loop 2s ease-in-out 0s infinite normal;
}
.v_line_fix p{
    color: #fff;
    padding:1px;
}

@keyframes loop {
    0% {
        height: 1px;
    }
    100% {
        height: 150px;
    }
}


/* product */


/* footer */
footer {
    height: 100px;
}
</style>


