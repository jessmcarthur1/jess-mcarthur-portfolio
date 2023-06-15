<script>
  import Header from '$lib/Header.svelte'
  import Footer from '$lib/Footer.svelte'
</script>

<svelte:head>
  <title>Paintings | Portfolio</title>
</svelte:head>
<div class="background">
  <Header />

  <main>
    <h2>Paintings</h2>
    <h3>Showcased below is a series of paintings produced in Visual Art from the past two years of NCEA.</h3>

    <div class="columns">
      <div class="column">
        <p>Here is a painting produced in level two with the theme of farming New Zealand, and painting techniques from artist Joshua Field.</p>
      </div>
      <div class="column">
        <img src="painting1.png" alt="A painting of a cow and a native bird aganist a grey abstract background." />
      </div>
    </div>

    <div class="columns">
      <div class="column">
        <img src="painting2.png" alt="A painting of a cow against a grey abstract background with pink elements and some barbwire." />
      </div>
      <div class="column">
        <p>This is a painting produced in level two with the theme of farming New Zealand, and painting techniques from Michael Cutlip.</p>
      </div>
    </div>

    <div class="columns">
      <div class="column">
        <p>This is a painting from level three with the theme of Twizel Township, and painting techniques from David Hockney.</p>
      </div>
      <div class="column">
        <img src="painting3.png" alt="A painting of a Four Square supermarket set against a landscpae." />
      </div>
    </div>

    <div class="columns">
      <div class="column">
        <img src="painting4.png" alt="A painting of sunset over a mountain range using strong red, orange, yellow, and black." />
      </div>
      <div class="column">
        <p>Here is a painting from level three with the theme of Twizel Township, and painting techniques from Peter James Smith.</p>
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
