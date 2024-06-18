<script>
    import Post from "./lib/post.svelte";
</script>


<main>

    <div class="full-width-section-black" id="d1">
        <h1 class="heading-1">Dmitriy Ivkov</h1>
        <div id="description-wrapper">
            <h3>🦀, Data, Pure Math, and Computer Science</h3>
        </div>
        <div id="link-wrapper">
            <a target ="_blank"  href="https://docs.google.com/document/d/1T9XzrENQ6zIA31F6u62IVUZ4Nv0bLxrnX-tp452k9Yw/edit?usp=sharing"><h3>Resume</h3></a>
            <a target ="_blank" href="https://www.linkedin.com/in/dmitriyivkov/"><h3>Linkedin</h3></a>
            <a target ="_blank" href="https://github.com/DIvkov575"><h3>Github</h3></a>
        </div>
        <div id="profile-picture-wrapper">
            <img src="/me1.jpg" alt="">
        </div>
    </div>




    <div class="clear-wrapper" id="d2">
        <div id="text-wrapper">
            <h3>Hi, I'm Dima 👋</h3>
            <h3>I'm a Software Engineer in the Boston Area and a rising Senior at Belmont High School.
                I have a passion for Pure-Math, Statistics, and Computer Science.
                I enjoy using my skills to write concurrent algorithms and to work with distributed compute systems.
                In my free time, I like studying Pure-Math, coding, and DH mountain biking.
            </h3>
            <br>
            <u><h3>I'm Currently</h3></u>
            <h3>Learning: Information Theory</h3>
            <h3>Building: SIEM and security Data-lake (on GCP in Rust)</h3>
            <h3>Grinding: College Applications</h3>
            <h3>Reading: "Information Retrieval" by Grossman, Frieder (Springer)</h3>
            <br>
            <u><h3>My Setup</h3></u>
            <h3>Language: Rust</h3>
            <h3>Cloud Provider: Google-Cloud-Provider</h3>
            <h3>Operating Systems: Macos / Debian</h3>
        </div>
    </div>

    <div class="clear-wrapper">
        <h2 style="margin: -1rem 0 1rem 1.5rem">Things I've learned & made</h2>
        <Post title='"Infonomics" by Douglas B. Laney' content="Great Read - Would Recommend. Infonomics suggests that information should be viewed as an asset (which many companies underutilize). Infonomics also covered issues such as information ownership, legality, measurement, and managment." imageUrl="/posts/infonomics.jpg"/>
        <Post title="Kolmogorov-Complexity" content="The minimum size program necessary to generate a certain output.
         Can be used to determine how complex a string/output is, because if longer program is necessary to generate the output -> less patterns in desired output. Upper bound can be estimated with Limpel-Ziv Compression. If (K(z) > len(z)) => string z can be considered random."/>
    </div>

</main>
