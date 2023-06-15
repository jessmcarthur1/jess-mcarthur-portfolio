<script>
  import Header from '$lib/Header.svelte'
  import Footer from '$lib/Footer.svelte'
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
        <img src="media6.png" alt="A mood board." />
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
    background-image: url('/background.jpg');
    background-repeat: no-repeat;
    background-attachment: fixed;
  }

  main {
    background-color: black;
    padding: 3em 4em;
  }

  h2 {
    color: white;
    font-size: 3em;
    text-align: center;
  }

  h3 {
    color: white;
    font-size: 1.5em;
    text-align: center;
    width: 60%;
    margin: 0 auto;
    margin-bottom: 3em;
  }

  h4 {
    color: white;
    font-size: 2em;
    text-align: center;
    margin-bottom: 1em;
  }

  p {
    color: white;
    width: 60%;
    margin-bottom: 1em;
  }

  .columns {
    margin-bottom: 3em;
  }

  .column {
    border-style: solid;
    border-color: white;
    border-width: 1px;
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  @media only screen and (max-width: 600px) {
    main {
      padding: 3em 2em;
    }

    h3 {
      width: 100%;
    }
  }
</style>
