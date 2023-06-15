<script>
  import { page } from '$app/stores'
</script>

<nav>
  <a href="letter" class:current-page={$page.url.pathname.includes('letter')}>Letter of Interest</a>
  <a href="paintings" class:current-page={$page.url.pathname.includes('paintings')}>Paintings</a>
  <a href="drawings" class:current-page={$page.url.pathname.includes('drawings')}>Drawings</a>
  <a href="digital-media" class:current-page={$page.url.pathname.includes('digital-media')}>Digital Media</a>
</nav>

<style>
  nav {
    background-color: rgba(56, 56, 56, 0.4);
    display: flex;
    justify-content: space-between;
    padding-left: 2%;
    padding-right: 2%;
    padding-top: 1%;
    padding-bottom: 1%;
    width: 100%;
  }

  a {
    font-size: 110%;
    color: rgba(255, 255, 255, 1);
    font-family: 'Noto Sans JP', sans-serif;
  }
  a:hover {
    border-bottom: 1px solid rgb(255, 255, 255, 1);
    color: white;
  }

  .current-page {
    color: rgb(0, 0, 0);
    border-bottom: 1px solid rgb(255, 255, 255, 1);
  }

  @media only screen and (max-width: 600px) {
    nav {
      flex-direction: column;
    }
  }
</style>
