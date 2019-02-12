<template>
    <footer>
        <header>
            <h2>Want to chat? Feel free to reach out...</h2>
        </header>  
        <section>
            <a href="mailto:chris@andrikanich.com">
                <i class="fa fa-envelope"></i>
            </a>
            <a href="https://www.linkedin.com/in/chrisandrikanich/">
                <i class="fa fa-linkedin"></i>
            </a>
            <a href="http://www.twitter.com/alphabet">
                <i class="fa fa-twitter"></i>
            </a>
            <a href="https://www.facebook.com/chris.andrikanich">
                <i class="fa fa-facebook"></i>
            </a>
            <a href="https://github.com/candrikanich/">
                <i class="fa fa-github"></i>
            </a>
            <a href="###">
                <i class="fa fa-codepen"></i>
            </a>
        </section>
        
    </footer>
</template>

<style lang="less" scoped>
    @import url("../assets/styles/variables.less"); 

    footer {
        padding: @basePadding 0;
        background-color: darken(@background-color,20%);    
        width: 100vw;
        position: sticky;
        bottom: 0;

        header {
            justify-content: stretch;
            width: 100vw;
            text-align: center;
            color: @gray10;

            h2 {
                margin: 0 0 15px 0;
                font-size: 1.2em;
            }
        }

        section {
            display: flex;
            width: 100vw;
            justify-content: center;
        
            a {
                color: @gray25;
                // background-color: darken(@background-color,30%);
                text-decoration: none;
                padding: 10px 15px;
                border: 1px solid darken(@background-color,20%);
                border-radius: 5px;
                margin: 0 10px;

                &:hover {
                    // background-color: darken(@background-color,10%);
                    color: @white;
                    border: 1px solid @gray25;
                }
            }
        }
    }
</style>
