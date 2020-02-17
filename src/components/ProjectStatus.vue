<template>
    <section class="site">
        <header>
            <h1>About this project</h1>
        </header>
        <article>
            <p>Here is a list of the technologies used to create this web site.</p>
            <ul>
                <li>Built using Vue.js <i class="fab fa-vuejs"></i> and HTML <i class="fab fa-html5"></i></li>
                <li>Styled using CSS <i class="fab fa-css3"></i> and LESS <i class="fab fa-less"></i></li>
                <li>Hosted by Netlify <i class="fab fa-netlify"></i></li>
                <li>Code repository stored on Github <i class="fab fa-github"></i></li>
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
