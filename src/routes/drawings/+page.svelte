<script>
  import Footer from '$lib/Footer.svelte'
  import Header from '$lib/Header.svelte'
</script>

<svelte:head>
  <title>Drawings | Portfolio</title>
</svelte:head>
<div class="background">
  <Header />
  <main>
    <h2>Drawings</h2>
    <h3>Showcased below is a series of my drawings produced in Visual Art throughout the past two years of NCEA.</h3>

    <div class="columns">
      <div class="column">
        <h4>Line Pencil Drawing</h4>
        <p>This is one of my line pencil drawings from Visual Art level 2 with the theme of farming New Zealand.</p>
      </div>
      <div class="column">
        <img src="drawing1.png" alt="A perspective drawing of farm paddock fenceline in pencil. " />
      </div>
    </div>

    <div class="columns">
      <div class="column">
        <img src="drawing2.png" alt="A pencil drawing of a farmer standing astride a quadbike looking across a paddock." />
      </div>
      <div class="column">
        <h4>Line Pencil Drawing</h4>
        <p>This is my second line pencil drawing from Visual Art level 2 with the theme of farming New Zealand.</p>
      </div>
    </div>

    <div class="columns">
      <div class="column">
        <h4>Pencil Drawing</h4>
        <p>This is my pencil drawing from Visual Art level 3 with the theme of Twizel Township.</p>
      </div>
      <div class="column">
        <img src="drawing3.png" alt="A pencil drawing of the Twizel bakery." />
      </div>
    </div>

    <div class="columns">
      <div class="column">
        <img src="drawing4.png" alt="A charcoal drawing of bridge, with a spiky, bare tree in the foreground." />
      </div>
      <div class="column">
        <h4>Charcoal Drawing</h4>
        <p>Here is my charcoal drawing from Visual Art level 3 with the theme of Twizel Township.</p>
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
