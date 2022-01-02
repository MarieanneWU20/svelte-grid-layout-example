<script>
    import { Grid, Row, Column } from "svelte-grid-layout";
</script>

<main>
    <Grid>
        <Row>
            <Column height="1" width="5"><h1 class="line">Svelte Grid Layout</h1></Column>
        </Row>
        <Row>
            <Column height="7" width="3">
                <header>
                    <h2>Description</h2>
                </header>
                <hr />
                <p>
                    <span class="bold">Svelte Grid Layout</span> is a tool that make
                    it easier to create a page template for applications built with
                    Svelte
                </p>
                <p>
                    The page templates specify the layout of the page through a
                    set of predetermined rules of how the components of the page
                    should be laid out.
                </p>
                <header>
                    <h3>Why?</h3>
                </header>
                <p class="margin-top">
                    All the nitty gritty details, such as responsive sizing and
                    styling, has already been taken care of by <span
                        class="bold">Svelte Grid Layout</span
                    >, and will be automagically generated as long as you
                    provide data for the starting point.
                </p>
                <p>
                    Therefore, you can focus entirely on the content part of
                    your app, without having to worry about the layout. Once you
                    have the layout that you want, it's easy to reuse and apply
                    the same one to multiple pages.
                </p>
                <hr class="bolder-hr" />
                <header>
                    <h3>Installation</h3>
                </header>
                <p class="code-example">npm install svelte-grid-layout</p>
                <hr class="bolder-hr" />
                <header>
                    <h3>Dependencies</h3>
                </header>
                <p class="text-link">
                    <a
                        class="link"
                        href="https://www.npmjs.com/package/svelte"
                        target="_blank"
                        rel="noopener noreferrer">svelte ^3.44.2</a
                    >
                </p>
                <hr class="bolder-hr" />
                <header>
                    <h3>Import & Use component</h3>
                </header>
                <div class="code-example-div">
                    <p>&lt;script&gt;</p>
                    <p>
                        &nbsp;import &#123; Grid, Row, Column &#125; from
                        "svelte-grid-layout";
                    </p>
                    <p>&lt;/script&gt;</p>

                    <p class="code-tag-top">&lt;Grid&gt;</p>
                    <p>&nbsp;&lt;Row&gt;</p>
                    <p>&nbsp;&nbsp;&lt;Column height="1" width="4"&gt;</p>
                    <p>&nbsp;&nbsp;&nbsp;&#123; your content &#125;</p>
                    <p>&nbsp;&nbsp;&lt;/Column&gt;</p>
                    <p>&nbsp;&lt;/Row&gt;</p>
                    <p>&lt;/Grid&gt;</p>

                    <hr class="bolder-hr" />
                </div>
                <header>
                    <h3>Props</h3>
                </header>
                <hr />
                <table>
                    <tr>
                        <th>Prop</th>
                        <th>Type</th>
                        <th>Description</th>
                    </tr>
                    <tr />
                    <tr>
                        <td>width</td>
                        <td>number</td>
                        <td>Cell (column) width</td>
                    </tr>
                    <tr>
                        <td>height</td>
                        <td>number</td>
                        <td>Cell (row) height</td>
                    </tr>
                </table>
                <hr class="bolder-hr" />
                <header>
                    <h3>GitHub</h3>
                </header>
                <hr />
                <p class="text-link">
                    <a
                        class="link"
                        href="https://github.com/MarieanneWU20/svelte-grid-layout"
                        target="_blank"
                        rel="noopener noreferrer">Svelte grid layout</a
                    >
                </p>
                <hr class="bolder-hr" />
                <header>
                    <h3>Future development</h3>
                </header>
                <hr />
                <p>
                    The goal for Svelte Grid Layout is a tool that gives the
                    user a graphical interface to create a page template for
                    applications built with Svelte. This will be possiblethrough
                    arrow-buttons that lets the user add rows or columns and
                    resize individual columns. Other possible upcomming features
                    are: drag and drop, change the spacing between columns and
                    animation for smooth transitions.
                </p>
            </Column>
            <Column height="7" width="2">
                <header>
                    <h2>About us</h2>
                </header>
                <hr />
                <header>
                    <h3>Marie Eriksson</h3>
                </header>
                <p class="margin-top">
                    I read my first course in web design at Medborgarskolan in
                    the spring of 2009. It quickly became an interest and I
                    continued to read various courses at colleges and
                    universities. Finally, I realized that this was something I
                    want to immerse myself more in and be able to work with in
                    the future.
                </p>
                <hr class="bolder-hr" />
                <header>
                    <h3 class="link-heading">
                        <a
                            href="https://www.linkedin.com/in/wivianne-grapenholt"
                            target="_blank"
                            rel="noopener noreferrer">Wivianne Grapenholt</a
                        >
                    </h3>
                </header>
                <p class="margin-top">
                    An ambitious junior developer with a senior's soft skills.
                </p>
                <p>
                    At the age of 45, I started my retraining journey by
                    studying Programming 1. I immediately felt that I had found
                    my calling!
                </p>
                <header>
                    <h3>MarieanneWU20</h3>
                </header>
                <p class="margin-top">
                    The name of the organization is our first names combined and
                    WU20 is the name of our class on Campus Värnamo.
                </p>
                <hr class="bolder-hr" />
                <header>
                    <h2 class="heading">Our internship project</h2>
                </header>
                <hr />
                <p>
                    This project has been developed as a part of the course
                    "Lärande i arbete 1" at <a
                        class="link-text"
                        href="https://campus.varnamo.se/campusvarnamo/utbildning/utbildningsarkiv/webbutvecklarenet.5.f0c3e6e174960600f056fb.html"
                        target="_blank"
                        rel="noopener noreferrer"
                        >Web Development .NET, Campus Värnamo</a
                    >
                </p>
                <p>
                    The purpose of the course is for the student to participate
                    in projects at the LIA workplace that include work with
                    programming and web development.
                </p>
                <p>
                    Knowledge from courses on programming and system and web
                    development is trained and applied.
                </p>
                <p>
                    We had the opportunity to carry out the course as open
                    source developers with Viktor Lyresten from <a
                        class="link-text"
                        href="https://www.hiveandfive.se/"
                        target="_blank"
                        rel="noopener noreferrer">Hive and Five</a
                    > as a consultant / supervisor.
                </p>
                <p>
                    We created the organization <a
                        class="link-text"
                        href="https://github.com/MarieanneWU20"
                        target="_blank"
                        rel="noopener noreferrer">MarieanneWU20</a
                    > to be able to share ownership of the source code.
                </p>
                <p>
                    Through the project, we have received support and help from
                    our head teacher Andréas Boozon.
                </p>
                <p>
                    The goal has been to publish the project as an npm package,
                    which we have obviously achieved!
                </p>
                <p>
                    We would like to take this opportunity to say thank you to:
                </p>
                <ul>
                    <li>Campus Värnamo for giving us this opportunity.</li>
                    <li>
                        Andréas for all the help with the administrative and
                        encouraging word.
                    </li>
                    <li>
                        And last but not least, Viktor for your support, help
                        and advice.
                    </li>
                </ul>
            </Column>
        </Row>
        <Row>
            <Column height="1" width="5"
                ><h4 class="footer">&copy; MarieanneWU20</h4>
                <h4>Marie Eriksson & Wivianne Grapenholt</h4></Column
            >
        </Row>
        <Row height="1" width="5"></Row>
    </Grid>
</main>

<style>
    h1,
    h2,
    h3,
    h4 {
        font-family: "Yanone Kaffeesatz", sans-serif;
        color: #99773d;
    }
    h1 {
        font-size: 4rem;
        font-weight: 600;
        line-height: 1.5em;
        text-align: center;
        margin: 50px 0 0 0;
        padding: 0;
        text-transform: uppercase;  
        text-decoration-line: underline;
        text-decoration-style: wavy;
    }
    h2 {
        font-size: 2rem;
        text-align: center;
        font-weight: 600;
        line-height: 2.2rem;
        margin: 10px 0 0 0;
    }
    h3 {
        font-size: 1.5rem;
        text-align: left;
        font-weight: 600;
        line-height: 1.3rem;
        margin: 25px 0 0 0;
    }
    h4 {
        font-size: 1.5rem;
        text-align: center;
        font-weight: 600;
        line-height: 1.3rem;
        margin: 25px 0 0 0;
    }
    p {
        font-size: 0.9rem;
        line-height: 1.4rem;
        font-family: "Faustina", serif;
        text-align: left;
        font-weight: 600;
    }
    main {
        color: #3d5f99;
        width: 100%;
        margin: 0 auto;
    }
    .bold {
        color: #99773d;
        font-weight: 800;
    }
    .margin-top {
        margin-top: 0;
    }
    hr {
        border: 1px solid #edf1f7;
    }
    .bolder-hr {
        border: 2px solid #edf1f7;
    }
    .code-example {
        background-color: #edf1f7;
        color: #3d5f99;
        font-family: "Courier New", Courier, monospace;
        padding: 10px;
    }
    div.code-example-div {
        color: #3d5f99;
        margin-top: 15px;
        background-color: #edf1f7;
        padding: 10px 0 0 15px;
    }
    div.code-example-div > p {
        margin: 0;
        font-family: "Courier New", Courier, monospace;
    }
    .code-tag-top {
        font-family: "Courier New", Courier, monospace;
        margin: 10px 0 0 0;
    }
    a.link {
        color: #993d8d;
        cursor: pointer;
        font-size: 1.1rem;
    }
    a.link-text {
        color: #993d8d;
        cursor: pointer;
        font-size: 0.9rem;
    }
    h3.link-heading a {
        color: #993d8d;
        cursor: pointer;
    }
    a:focus,
    a:hover,
    a:visited,
    h3.link-heading a:hover,
    h3.link-heading a:visited {
        color: #3d9949;
    }
    a:active,
    h3.link-heading a:active {
        color: #99773d;
    }
    table {
        margin: 20px 0;
    }
    table,
    th,
    td {
        border: 1px solid #3d5f99;
        border-collapse: collapse;
        width: 60%;
    }
    th,
    td {
        width: 33%;
        text-align: center;
        vertical-align: middle;
        padding: 10px;
    }
    th {
        height: 50px;
        font-family: "Yanone Kaffeesatz", sans-serif;
        font-size: 1.4rem;
        font-weight: 600;
    }
    td {
        height: 45px;
        font-size: 0.8rem;
        line-height: 1.3rem;
        font-weight: normal;
        font-family: "Franklin Gothic Medium", "Arial Narrow", Arial, sans-serif;
    }
    .heading {
        padding-top: 20px;
    }
    ul li {
        font-size: 0.9rem;
        line-height: 1.4rem;
        font-family: "Faustina", serif;
        text-align: left;
        font-weight: 600;
    }
    .footer {
        margin-top: 50px;
    }
    @media screen and (min-width: 768px) {
        h1 {
            font-size: 5rem;
            line-height: 1.8em;
            margin: 10px 0 0 0;
        }
        h2 {
            font-size: 2.5rem;
            line-height: 2.8rem;
            margin: 10px 0 0 0;
        }
        h3 {
            font-size: 1.7rem;
            line-height: 1.9rem;
            margin: 30px 0 0 0;
        }
        main {
            margin: 0 auto 50px auto;
        }
        p,
        td,
        ul li {
            font-size: 1rem;
            line-height: 1.5rem;
        }
        th {
            font-size: 1.4rem;
            line-height: 1.4rem;
        }
        a.link-text {
            font-size: 1rem;
            line-height: 1.5rem;
        }
    }
    @media screen and (min-width: 1200px) {
        h1 {
            font-size: 7rem;
        }
        h2 {
            font-size: 2.7rem;
            line-height: 3rem;
            margin: 10px 0 0 0;
        }
        h3 {
            font-size: 2rem;
            line-height: 2.1rem;
            margin: 35px 0 0 0;
        }
        h4 {
            font-size: 1.8rem;
            line-height: 2.1rem;
        }
         main {
            max-width: 1200px;
            margin: 0 auto 70px auto;
        }
        p,
        td,
        ul li {
            font-size: 1.1rem;
            line-height: 1.6rem;
        }
        th {
            font-size: 1.7rem;
        }
        a.link-text {
            font-size: 1.1rem;
            line-height: 1.6rem;
        }   
    }
</style>
