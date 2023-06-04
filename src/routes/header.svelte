<nav>
  <h2 class="logo">Sammi.</h2>
  <h2>HOME</h2>
  <h2><a href="#about">ABOUT</a></h2>
  <h2><a href="#services">SERVICES</a></h2>
  <h2><a href="#team">OUR TEAM</a></h2>
  <h2><a href="#prices">PRICES</a></h2>
  <h2><a href="#contact">CONTACT</a></h2>
</nav>

<style>
  a {
    text-decoration: none;
    color: black;
  }
  nav {
    display: flex;
    flex-direction: row;
    width: 100%;
    justify-content: space-around;
    align-items: center;
    height: 4rem;
  }
  h2 {
    font-family: "Roboto Mono", monospace;
    font-size: medium;
  }
  .logo {
    align-self: centre;
    font-family: "Sacramento", cursive;
    font-size: xx-large;
    padding-left: 5rem;
    padding-right: 5rem;
  }

  @media screen and (max-width: 500px) {
    nav {
      max-width: 100vw;
    }

    h2 {
      font-size: xx-small;
    }
    .logo {
      padding: 0;
    }
  }

  @media screen and (max-width: 950px) {
    nav {
      max-width: 100vw;
    }

    h2 {
      font-size: small;
    }
    .logo {
      padding: 0;
    }
  }
</style>
