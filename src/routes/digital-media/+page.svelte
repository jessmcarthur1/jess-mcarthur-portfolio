<script>
  import Header from "$lib/Header.svelte"
  import Footer from "$lib/Footer.svelte"
</script>

<svelte:head>
  <title>Digital Media | Portfolio</title>
</svelte:head>
<div class="background">
  <Header />

  <main>
    <h2>Digital Media</h2>
    <h3>Below is a series of digital media that I have produced in NCEA subjects such as Digital Technologies and Media Studies and some in my own time.</h3>

    <div class="columns">
      <div class="column">
        <h4>Website</h4>
        <p>This is a website that I designed for my employer at the Jolly Potter Restaurant using Wix</p>
      </div>
      <div class="column">
        <img src="media1.png" alt="The homepage of a restaurant website." />
      </div>
      <div class="column">
        <img src="media2.png" alt="A website page showcasing a menu." />
      </div>
    </div>

    <div class="columns">
      <div class="column">
        <img src="media3.png" alt="A website page displaying a breakfast menu." />
      </div>
      <div class="column">
        <h4>Website</h4>
        <p>Here is a website that I created in level two for my digital technologies assessment on a restaurant using svelte and bulma.</p>
      </div>
    </div>
    <div class="columns">
      <div class="column is-half">
        <h4>Prototype</h4>
        <p>Here is a prototype for my current web app design for children's learning at home 'Tiny Learners'.</p>
      </div>
      <div class="column">
        <img src="media4.png" alt="The colorful display of a children's learning app." />
      </div>
      <div class="column">
        <img src="media5.png" alt="The colorful display of a children's learning app." />
      </div>
    </div>

    <div class="columns">
      <div class="column">
        <img src="media3.png" alt="A website page displaying a breakfast menu." />
      </div>
      <div class="column">
        <h4>Mood Board</h4>
        <p>Here is a mood board that I created when doing work experience at a marketing agency in Christchurch. It was the design idea for an At Home Gin brand</p>
      </div>
    </div>
  </main>
  <Footer />
</div>

<style>
  .background {
    background-image: url("/background.jpg");
    background-repeat: no-repeat;
    background-attachment: fixed;
  }

  main {
    background-color: black;
    padding-left: 5%;
    padding-right: 5%;
    padding-top: 5%;
  }

  h2 {
    color: white;
    font-size: 300%;
    text-align: center;
    padding-bottom: 3%;
  }

  h3 {
    color: white;
    font-size: 100%;
    padding-bottom: 5%;
    width: 45%;
    text-align: center;
    margin-left: 30%;
  }

  h4 {
    color: white;
    font-size: 220%;
    text-align: center;
    padding-bottom: 3%;
  }

  p {
    color: white;
    font-size: 100%;
    padding-bottom: 3%;
    width: 60%;
    text-align: center;
    margin-left: 20%;
    margin-top: 20%;
  }

  .column {
    border-style: solid;
    border-color: white;
    border-width: 0.5px;
  }
</style>
