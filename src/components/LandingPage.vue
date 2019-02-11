<template>
    <section class="landingPage">
        <header>
            <h1>Hi, I'm Chris.</h1>
            <h2>Nice to meet you. </h2>
        </header>
    </section>
    
</template>

<script>
    export default {
        name: 'landing-page',
        data() {
            return {
                pageName: 'landingPage'
            }
        }
    }
</script>

<style lang="less" scoped>
    @import url("../assets/styles/main.less");

    section.landingPage {
        background: url("../assets/img/cwa.png") center center no-repeat;
        background-attachment: fixed;
        background-size: cover;
        background-color: @background-color;
        height: 100vh;
        width: 100vw;
        overflow-x: hidden; 
        overflow-y: auto;
        position: sticky;
        z-index: -1;

        header {
            padding: 1em;

            h1 {
                font-size: 3.0em;
                font-weight: bold;
            }

            h2 {
                font-size: 1.8em;
                font-weight: normal;
            }

            h1, h2 {
                padding: 0;
                margin: 0;
                line-height: 1.0em;
                text-shadow: 0 0 3px #464646;
                color: @white;
            }
        }

        i {
            margin-right: 5px;
        }
    }
</style>

