<script>
  import About from "./about.svelte";
  import Contact from "./contact.svelte";
  import Footer from "./footer.svelte";
  import Hero from "./hero.svelte";
  import Prices from "./prices.svelte";
  import Services from "./services.svelte";
  import Team from "./team.svelte";
</script>

<Hero />
<div id="about">
  <About />
</div>
<div id="services">
  <Services />
</div>
<div id="team">
  <Team />
</div>
<div id="prices">
  <Prices />
</div>
<div id="contact">
  <Contact />
</div>
<Footer />
