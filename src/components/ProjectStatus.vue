<template>
    <section class="site">
        <header>
            <h1>About this project</h1>
        </header>
        <article>
            <p>Here is a list of the technologies used to create this web site.</p>
            <ul>
                <li><i class="fab fa-vuejs"></i> Built using Vue.js</li>
                <li><i class="fab fa-less"></i> Styled using LESS</li>
                <li><i class="fab fa-aws"></i> Hosted by Amazon Web Services S3</li>
                <li><i class="fab fa-github"></i> Code repository stored on Github</li>
            </ul>
        </article>
    </section>
</template>

<style lang="less" scoped>
    @import url("../assets/styles/variables.less");

    section.site {

        article {

            ul {
                list-style: none;

                li {
                    margin: 0 0 10px 0;
                }
            }

        }

    }
</style>
