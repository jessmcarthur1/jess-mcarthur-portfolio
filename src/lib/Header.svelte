<script>
  import Nav from "$lib/Nav.svelte"
</script>

<header class="columns">
  <h1 class="column noBorder is-narrow-tablet-mobile">
    <a href="/">Jess McArthur</a>
  </h1>
  <div class="column noBorder">
    <Nav />
  </div>
</header>

<style>
  .columns {
    padding-top: 3%;
  }
  h1 {
    margin: 0 100px;
  }

  h1 a {
    color: white;
    font-size: 180%;
    display: flex;
  }

  .noBorder {
    border-style: none;
  }

  .column {
    display: flex;
    align-content: center;
    justify-content: center;
  }
</style>
