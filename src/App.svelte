<script>
    import { Grid, Row, Column } from "svelte-grid-layout";
</script>

<main>
    <Grid>
        <Row>
            <Column height="1" width="4"><h1>Svelte Grid Layout - Example</h1></Column>
        </Row>
        <Row>
            <Column height="5" width="1">
                <h2>About us</h2>
                <h3>Marie Eriksson</h3>
                <p>* Short presentation *</p>
                <a href="www.linkedin.com/in/wivianne-grapenholt" target=":_blank"><h3>Wivianne Grapenholt</h3></a>
                <p>An ambitious junior developer with a senior's soft skills.</p>
                <p>At the age of 45, I started my retraining journey by studying  Programming 1. I immediately felt that I had found my calling!</p>
                
                <h4>MarieanneWU20</h4>
                <p>The name of the organization is our first names combined and WU20 is the name of our class on Campus Värnamo.</p>
            </Column>
            <Column height="5" width="3">
                <h2>Our internship project</h2>
                <p>This project has been developed as a part of the course "Lärande i arbete 1" at <a href="https://campus.varnamo.se/campusvarnamo/utbildning/utbildningsarkiv/webbutvecklarenet.5.f0c3e6e174960600f056fb.html" target=":_blank">Web Development .NET, Campus Värnamo</a></p> 
                <p>The purpose of the course is for the student to participate in projects at the LIA workplace that include work with programming and web development.</p>
                <p>Knowledge from courses on programming and system and web development is trained and applied.</p>
                <p>We had the opportunity to carry out the course as open source developers with Viktor Lyresten from <a href="https://www.hiveandfive.se/" target=":_blank">Hive and Five</a> as a consultant / supervisor.</p>
                <p>We created the organization <a href="https://github.com/MarieanneWU20" target=":_blank">MarieanneWU20</a> to be able to share ownership of the source code.</p>
                <p>Through the project, we have received support and help from our head teacher Andréas Boozon.</p>
                <p>The goal has been to publish the project as an npm package, which we have obviously achieved!</p>
                <p>We would like to take this opportunity to say thank you to:</p>
                    <ul>
                        <li>Campus Värnamo for giving us this opportunity.</li>
                        <li>Andréas for all the help with the administrative and encouraging word.</li>
                        <li>And last but not least, Viktor for your support, help and advice.</li>
                    </ul>

            </Column>
        </Row>
        <Row>
            <Column height="1" width="4">
                <p>&copy; MarieanneWU20</p>
                <p>Marie Eriksson & Wivianne Grapenholt</p>
            </Column>
        </Row>
    </Grid>
</main>

<style>
    main {
        width: 100%;
        text-align: center;
        margin: 0 auto;
    }
    @media (min-width: 640px) {
        main {
            max-width: none;
        }
    }
</style>
