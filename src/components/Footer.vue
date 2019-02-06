<template>
    <footer>
        <header>
            <h2>Want to chat? Feel free to reach out...</h2>
        </header>  
        <section>
            <a href="mailto:chris@andrikanich.com"><i class="fa fa-envelope"></i> Email</a>
            <a href="https://www.linkedin.com/in/chrisandrikanich/"><i class="fa fa-linkedin"></i> LinkedIn</a>
            <a href="http://www.twitter.com/alphabet"><i class="fa fa-twitter"></i> Twitter</a>
            <a href="https://www.facebook.com/chris.andrikanich"><i class="fa fa-facebook"></i> Facebook</a>
            <a href="https://github.com/candrikanich/"><i class="fa fa-github"></i> GitHub</a>
            <a href="###"><i class="fa fa-codepen"></i> CodePen</a>
        </section>
        
    </footer>
</template>

<style lang="less" scoped>
    @import url("../assets/styles/variables.less"); 

    footer {
        padding: @basePadding 0;
        background-color: @alternate-color;
        width: 100vw;

        header {
            justify-content: stretch;
            width: 100vw;
            text-align: center;
            color: darken(@alternate-color,30%);
        }

        section {
            display: flex;
            width: 100vw;
            justify-content: space-around;
        
            a {
                color: #fff;
                text-decoration: none;
                padding: 10px 15px;
                border: 1px solid @font-color;
                border-radius: 5px;

                &:hover {
                    background-color: darken(@alternate-color,10%);
                }
            }
        }
    }
</style>
