<script>
  import Header from "$lib/Header.svelte"
  import Footer from "$lib/Footer.svelte"
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
</style>
