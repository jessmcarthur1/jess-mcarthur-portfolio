<script>
  import Nav from "$lib/Nav.svelte"
  import Footer from "$lib/Footer.svelte"
</script>

<svelte:head>
  <title>Drawings | Portfolio</title>
</svelte:head>
<div class="background">
  <div class="columns">
    <div class="column noBorder"><a href="/">Jess McArthur</a></div>
    <div class="column noBorder">
      <Nav />
    </div>
  </div>

  <main>
    <h2>Drawings</h2>
    <h3>Showcased below is a series of my drawings produced in Visual Art throughout the past two years of NCEA.</h3>

    <div class="columns">
      <div class="column">
        <p>Here is one of my line pencil drawings from Visual Art level 2 with the theme of farming New Zealand.</p>
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
        <p>Here is my second line pencil drawing from Visual Art level 2 with the theme of farming New Zealand.</p>
      </div>
    </div>

    <div class="columns">
      <div class="column">
        <p>Here is my charcoal drawing from Visual Art level 2 with the theme of farming New Zealand.</p>
      </div>
      <div class="column">
        <img src="drawing3.png" alt="A charcoal drawing of a small group of sheep behind a fence." />
      </div>
    </div>

    <div class="columns">
      <div class="column">
        <img src="drawing4.png" alt="A charcoal drawing of bridge, with a spiky, bare tree in the foreground." />
      </div>
      <div class="column">
        <p>Here is my charcoal drawing from Visual Art level 3 with the theme of Twizel Township.</p>
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
  a {
    color: white;
    font-size: 180%;
    padding-left: 2%;
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
    width: 40%;
    text-align: center;
    margin-left: 30%;
  }
  p {
    color: white;
    font-size: 100%;
    padding-bottom: 3%;
    width: 60%;
    text-align: center;
    margin-left: 20%;
    margin-top: 30%;
  }

  .column {
    border-style: solid;
    border-color: white;
    border-width: 0.5px;
  }
  .noBorder {
    border-style: none;
  }
</style>
