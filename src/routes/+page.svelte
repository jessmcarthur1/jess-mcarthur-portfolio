<script>
  import Header from "$lib/Header.svelte";
  import Footer from "$lib/Footer.svelte";
</script>

<svelte:head>
  <title>Jess McArthur | Home</title>
</svelte:head>

<div class="background">
  <main>
    <Header />

    <div class="columns">
      <div class="column">
        <div class="section">
          <h1 class="title">Jess McArthur</h1>
          <h2>Portfolio</h2>
        </div>
      </div>
      <div class="column">
        <img src="profile.png" alt="Jess McArthur Headshot" />
      </div>
    </div>
  </main>
  <Footer />
</div>

<style>
  .background {
    background-image: url("/background.webp");
    background-repeat: no-repeat;
    background-attachment: fixed;
    width: 100%;
  }

  main {
    margin-bottom: 5em;
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
    color: rgb(6, 6, 6);
    font-size: 400%;
    font-weight: normal;
  }

  h2 {
    color: rgb(6, 6, 6);
    font-size: 150%;
    text-transform: uppercase;
    font-family: "Noto Sans JP", sans-serif;
  }

  @media only screen and (max-width: 600px) {
    .section {
      padding-top: 2%;
      padding-left: 2%;
    }

    img {
      padding-top: 2%;
      margin-left: 16%;
    }
    .columns {
      align-content: center;
    }

    h1,
    h2 {
      text-align: center;
    }
  }
</style>
