<script>
  import { page } from "$app/stores"
</script>

<nav class="tabs">
  <a href="letter" class:current-page={$page.url.pathname.includes("letter")}>Letter of Interest</a>
  <a href="paintings" class:current-page={$page.url.pathname.includes("paintings")}>Paintings</a>
  <a href="drawings" class:current-page={$page.url.pathname.includes("drawings")}>Drawings</a>
  <a href="digital-media" class:current-page={$page.url.pathname.includes("digital-media")}>Digital Media</a>
</nav>

<style>
  nav {
    background-color: rgba(56, 56, 56, 0.4);
    /* margin-bottom: 2%; */
    display: flex;
    justify-content: space-between;
    /* width: 80%; */
    padding-left: 2%;
    padding-right: 2%;
    padding-top: 1%;
    padding-bottom: 1%;
    /* margin-top: 5%; */
  }

  a {
    font-size: 110%;
    color: white;
    font-family: "Noto Sans JP", sans-serif;
  }
  a:hover {
    border-bottom: 1px solid rgb(0, 0, 0);
    color: black;
  }

  .current-page {
    color: rgb(0, 0, 0);
    border-bottom: 1px solid rgb(0, 0, 0);
  }
</style>
