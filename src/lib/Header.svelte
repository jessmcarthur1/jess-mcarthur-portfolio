<script>
  import Nav from "$lib/Nav.svelte"
</script>

<header>
  <div class="columns">
    <div class="column noBorder"><a href="/">Jess McArthur</a></div>
    <div class="column noBorder">
      <Nav />
    </div>
  </div>
</header>

<style>
  a {
    color: white;
    font-size: 180%;
    padding-left: 2%;
  }
  .noBorder {
    border-style: none;
  }
</style>
