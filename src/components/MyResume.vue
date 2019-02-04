<template>
    <!-- MY RESUME SECTION -->
    <section id="myResume" class="container mainView">
        <div class="row">
            <header class="col-md-12 jumbotron">
                <h2>My Resume</h2>
                <h3>Learn more about my experience...</h3>
            </header>
        </div>
        <div class="row">
            <div class="col-md-1"></div>
            <article class="col-md-10">
                <h4>Objective</h4>
                <p>As a Front-End Developer, my passion for semantic HTML & CSS pushes myself to learn more, to work with my team to create high-quality code and to continuously enhance my skillset. My experience with taking someone else's vision and translating it to good usable code makes me a great fit for your team.</p>
                <h4>Experience</h4>

                <!-- DEALER TIRE -->
                <h5>Dealer Tire, LLC, Web Developer, Cleveland, OH &mdash; 2016-Present</h5>
                <ul>
                    <li>Coordinated with team to launch Dealer Tire China by designing & skinning Porsche dealership web site</li>
                    <li>Support web applications and branding updates for US and Canadian dealership websites</li>
                    <li>Led project to move Online Tire Store application to Nissan & Infiniti Canada dealerships</li>
                </ul>

                <!-- TEALS -->
                <h5>TEALS, Volunteer Teaching Assistant, Cleveland, OH &mdash; 2018-Present</h5>
                <ul>
                    <li>Assisted Campus International High School teacher with the Intro to Computer Science curriculum</li>
                    <li>Help students understand basic Computer Science concepts using Snap and Python programming languages</li>
                </ul>

                <!-- TECH ELEVATOR-->
                <h5>Tech Elevator, Student: Java Cohort, Cleveland, OH &mdash; 2016-Present</h5>
                <ul>
                    <li>Java Language Fundamentals: variables, data types, loops, conditional statements, exception handling, collections framework, I/O</li>
                    <li>Object Oriented Programming: classes and objects, interfaces, access modifiers, packages, the Java classpath, class modeling, encapsulation, inheritance, and polymorphism, UML class diagrams</li>
                    <li>Web Application Development: HTML, CSS, Javascript, Servlets, JSP, Spring Web MVC, Tomcat</li>
                    <li>Database Programming: JDBC, JPA (Hibernate), table design and creation, SQL queries and DML, PostgreSQL, E/R diagrams</li>
                    <li>Development tools and techniques: unit testing (JUnit), TDD, unix command line navigation, Git, Eclipse</li>
                </ul>

                <!-- GRAY & COMPANY -->
                <h5>Gray & Company, Publishers, Digital Marketing, Cleveland, OH &mdash; 1998-2016</h5>
                <ul>
                    <li>Built and designed company web site using HTML, CSS, and FileMaker databases, also managed and maintained updates, fixes, and feature requests via Coda</li>
                    <li>Organized and designed promotional materials, coordinated and scheduled events, and managed book sales partnerships for appearances for 40+ authors</li>
                    <li>Crafted content, designed assets, and implemented social media campaigns on Facebook and Twitter in conjunction with product releases, special offers, and timely content</li>
                    <li>Planned, managed, and researched office logistics for 6 full-time and part-time employees</li>
                </ul>

                <!-- BURNING RIVER SPORTS -->
                <h5>Burning River Sports, Co-owner, Cleveland, OH &mdash; 2002-2005</h5>
                <ul>
                    <li>Built, managed and maintained company web site using HTML and CSS</li>
                    <li>Organized, scheduled, and coordinated dozens of local social and sport events in Greater Cleveland</li>
                    <li>Designed marketing materials and promotional giveaways using Adobe InDesign</li>
                </ul>

                <!-- SIGNATURES -->
                <h5>Signatures Network, Merchandising Assistant, San Francisco, CA &mdash; 2005-2009</h5>
                <ul>
                    <li>Assisted with inventory supply and management, venue transactions, and logistics for Coldplay concert tours in the summers of 2006, 2008, and 2009 in the United States and Canada</li>
                </ul>

                <!-- EDUCATION -->
                <h4>Education</h4>
                <ul>
                    <li>Tech Elevator, Cleveland, OH — Certificate, Expected Aug 2016
                        <p>14 week accelerated coursework on Java software language</p>
                    </li>
                    <li>Ohio University, Athens, OH — B.A. English, 1998</li>
                </ul>
            </article>
        </div>
        <div class="col-md-1"></div>
    </section>
</template>

<script>
export default {
}
</script>

<style>
/* eslint-disable */
    h1,
    h2,
    h3,
    h4,
    h5,
    h6,
    a.navbar-brand {
      font-family: 'Nunito', sans-serif;
      color: #30477A;
    }

    a:link,
    a:visited,
    a:hover,
    a:active {
      color: #479932;
    }

    span.glyphicon {
      margin-right: 10px;
    }

    section {
      margin-top: 40px;
    }

    .mainView {
      margin-top: 48px;
    }

    #myStory img {
      margin: 20px 0;
      box-shadow: 2px 2px 3px #ccc;
    }

    #myStory .twitter {
      height: 550px;
      overflow: auto;
      margin-bottom: 40px;
    }

    p {
      font-size: 1.3em;
      line-height: 1.25em;
    }

    .jumbotron {
      border: 1px solid #ccc;
      box-shadow: 0 0 4px #666;
      margin-bottom: 10px;
      padding-bottom: 10px;
    }

    .jumbotron h3 {
      margin-top: 0;
      font-size: 1.4em;
    }

    h4 {
      border-top: 1px solid #ccc;
      padding-top: 15px;
      margin-top: 15px;
      font-weight: bold;
      font-size: 1.5em;
    }

    #myResume h4:first-child {
      border: none;
    }

    .projectCard {
      border: 1px solid #ccc;
      box-shadow: 0 0 3px #666;
      padding: 10px;
      margin: 20px 0;
    }

    .projectCard img {
      margin: 0 0 20px 0;
    }

    .projectCard h6 {
      font-size: 1.3em;
    }

    footer {
      background-color: #1f1f1f;
      color: #fff;
      margin: 10px 0 0 0;
      padding: 10px 0 20px 0;
      text-align: center;
    }

    footer div:first-child {
      margin: 8px 0;
      font-weight: bold;
      font-size: 1.1em;
    }
</style>
