<script>
  import Header from '$lib/Header.svelte'
  import Footer from '$lib/Footer.svelte'
</script>

<svelte:head>
  <title>Letter of Interest | Portfolio</title>
</svelte:head>
<div class="background">
  <Header />

  <main>
    <h2>Letter of Interest</h2>

    <p>I am Jess McArthur and I am currently completing NCEA level 3 at Craighead Diocesan School. This year I am taking the subjects of Visual Art, Media Studies, Digital Technologies, History, and Statistics. It is with great pleasure that I submit my portfolio, showcasing my passion in two main fields, the creative possibilities within art and intertwining that with technology.</p>

    <p>My artistic journey began in year 9 as I discovered my passion to paint and express myself amongst the art class. As I progressed through high school and on to Visual Art I discovered the topics that I am interested in and expressed this through my found style of surrealism. Additionally, my affinity for digital design since a young age has allowed me to venture into the realistic side, where I have created websites and web apps to benefit people in the community and have some understanding of user experience methodologies and design principles.</p>

    <p>Since being in high school I have immersed myself into a variety of team sports such as Rowing, Netball, and Hockey. These sports have taught me the value of effective communication and leadership which I would say have helped me when collaborating with digital users as you have to listen to their suggestions and implement them as you would in team sports in which you listen to your teammates' ideas and take them on board. Being a part of the technology committee for the past two years has helped expand my technical proficiency. Through active involvement in various technology related projects, I have had the opportunity to apply my creativity to real world scenarios, which ultimately enhance my skills.</p>

    <p>As I researched various tertiary institutions I was encouraged by my digital technologies teacher to look at the Media Design School. The Media Design School is a dream that has been ignited within me ever since I came up to Auckland in April and took a tour of the campus. The school's strong emphasis on hands-on learning and smaller lecture sizes stood out to me. Observing the students' work made me wish to create a product that is at that high level of quality. It would be an incredible pleasure to study in a setting that I enjoy alongside others who share my interests. Looking towards the future my goal is to graduate with a Bachelor of Media Design majoring in UX/UI which I intend to use in the field of website and interface design. Although my career may change between now and graduating I still aim to use my creative skills and technical abilities to help businesses and organisations through technology.</p>
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

  p {
    color: white;
    width: 60%;
    margin: 0 auto;
    padding: 1em 0;
  }

  h2 {
    color: white;
    font-size: 300%;
    text-align: center;
    padding-bottom: 5%;
  }

  @media only screen and (max-width: 600px) {
    main {
      padding: 3em 0;
    }

    p {
      width: 100%;
      padding: 1em 3em;
    }
  }
</style>
