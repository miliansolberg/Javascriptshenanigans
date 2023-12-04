
<script>
  import Testimonials from './lib/Testimonials.svelte';
  import Navbar from './liv/Navbar.svelte';

  function scrollTop() {
    window.scrollTo({
      top: 0,
      behavior: 'smooth'
    });
  }

  function scrollDown() {
    document.getElementById("get-started").scrollIntoView({
      behavior: "smooth",
      block: "start"
    });
  }

  function popOnScroll() {

  }

  function buttonDissapear() {

  }


</script>

<main>
  <Navbar />
  <h1>The ultimate experience <br> for the modern investor</h1>
  
  <p>Scroll for an adventure</p>
  <button on:click={scrollDown}>Check it out!</button>

  <h2>Designed to make you a <b>better</b> investor</h2>

  <Testimonials />

  <img src="https://www.freeiconspng.com/thumbs/laptop-png/mac-laptop-png-13.png" class="laptop" alt="laptop">

  <div id="get-started">How to get started</div>
  <div class="step1">Step 1: Download Ledger Nano X</div>

<img src="https://cdn.shopify.com/s/files/1/2974/4858/products/01_4f10d168-302a-47b3-b79f-e0a6b6da7a48_large.png?v=1644216184" class="nanox" alt="nanox" loading="lazy" />


  <div class="step2">Step 2: Choose a payment plan</div>
  <img src="https://treasure.lol/build/_assets/get-magic-3DRK4WHV.webp" class="stars" alt="stars" loading="lazy">

  <div class="step2">Step 3: Start trading!</div>
  <img src="https://treasure.lol/build/_assets/Card_Community-OB3IGX2D.webp" class="stars" alt="stars" loading="lazy">

  <h3>Streamline your operations with our advanced tooling!</h3>

<img src="https://nuxt.com/assets/home/dx-plug-and-play-dark.svg" class="website" alt="websiteimg" loading="lazy">


<div class="top" on:click={scrollTop}>Click to get back to top</div>

</main>

<style>

h1 {
  margin-top: 10vh;
  text-align: center;
  line-height: 4vh;
}

p {
  text-align: center;
}

button {
  display: flex;
  justify-content: center;
  margin: auto;
}

h2 {
  margin-top: 10vh;
  text-align: center;
}

h2 b {
  color: red;
}

.laptop {
  height: 40vw;
  display: flex;
  margin: auto;
  justify-content: center;
  padding-top: 20vh;
}

h3 {
  margin-top: 14vh;
  text-align: center;
}

#get-started {
  text-align: center;
  margin-top: 8vh;
  font-size: 36px;
  text-transform: uppercase;
  font-weight: bolder;
}


.step1 {
  margin-top: 2vh;
  text-align: center;
  justify-content: center;
  display: flex;
}

.nanox {
  display: flex;
  margin: auto;
  height: 20vh;
  margin-top: 20px;
  justify-content: center;
}

.step2 {
  margin-top: 2vh;
  text-align: center;
  justify-content: center;
  display: flex;
}

.stars {
  display: flex;
  margin: auto;
  height: 20vh;
  margin-top: 20px;
  justify-content: center;
}

.top {
  margin-top: 2vh;
  text-align: center;
  justify-content: center;
  display: flex;
  font-weight: bolder;
  cursor: pointer;
}

.website {
  display: flex;
  justify-content: center;
  margin: auto;
  height: 40vw;
  padding-top: 10vh;
}

</style>
