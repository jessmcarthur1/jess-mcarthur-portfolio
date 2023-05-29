<script>
  import Nav from "$lib/Nav.svelte"
  import Footer from "$lib/Footer.svelte"
</script>

<svelte:head>
  <title>Jess McArthur | Home</title>
</svelte:head>

<div class="background">
  <main>
    <a href="/">Jess McArthur</a>
    <div class="columns">
      <div class="column">
        <div class="section">
          <h1 class="title">Jess McArthur</h1>
          <h2>Portfolio</h2>
        </div>
      </div>
      <div class="column">
        <Nav />
        <img src="profile.png" alt="Jess McArthur Headshot" />
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

  img {
    width: 70%;
    margin-left: 5%;
    padding-top: 5%;
  }
  .section {
    padding-top: 40%;
    padding-left: 18%;
  }
  h1 {
    color: white;
    font-size: 400%;
    font-weight: normal;
  }

  h2 {
    color: white;
    font-size: 150%;
    text-transform: uppercase;
    font-family: "Noto Sans JP", sans-serif;
  }

  a {
    color: white;
    font-size: 180%;
    padding-left: 2%;
  }
</style>
