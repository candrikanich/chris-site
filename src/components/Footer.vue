<template>
    <footer>
        <a href="mailto:chris@andrikanich.com"><i class="fas fa-envelope"></i> Email</a>
        <a href="###"><i class="fas fa-linkedin"></i> LinkedIn</a>
        <a href="http://www.twitter.com/alphabet"><i class="fas fa-twitter"></i> Twitter</a>
    </footer>
</template>

<style lang="less" scoped>
    @import url("../assets/styles/variables.less"); 

    footer {
        padding: @basePadding 0;
        background-color: @background-color;
        display: flex;
        justify-content: space-evenly;
        width: 100vw;

        a {
            color: #2c3e50;
            text-decoration: none;
            padding: 4px 3px 3px;
        }
    }
</style>
