<script>
  // import heroImg from "./hero.jpg";
  import hero from "./edit-petr-sidorov-LM3pUMAwqMU-unsplash.jpg";
</script>

<div>
  <img alt="woman with multi-colour hair" src={hero} />
  <div class="text">
    <h1>Hair design<br /> By Sammi</h1>
    <br />
    <p>We all deserve to have beautiful hair</p>
    <p class="hours">TUES - SUN : 8:00AM - 6:00pm</p>
  </div>
</div>

<style>
  div {
    display: flex;
    flex-direction: column;
    position: relative;
    justify-content: center;
    width: 100%;
  }
  img {
    max-width: 100%;
    height: auto;
  }
  h1 {
    color: white;
    padding-left: 50px;
    font-size: 90px;
    font-weight: lighter;
    font-family: "Roboto Mono", monospace;
    text-shadow: 1px 1px rgb(76, 76, 76);
    text-transform: uppercase;
  }
  p {
    color: white;
    padding-left: 50px;
    font-family: "Roboto Mono", monospace;
    text-shadow: 1px 1px rgb(76, 76, 76);
    text-transform: uppercase;
  }
  .text {
    position: absolute;
  }
  .hours {
    position: absolute;
    transform: rotate(90deg);
    right: 0;
    font-size: large;
    height: 70%;
  }
  @media screen and (max-width: 500px) {
    div {
      width: 100%;
      height: auto;
    }
    img {
      /* width: 100vh; */
      height: auto;
    }

    .hours {
      transform: none;
      color: rgb(255, 255, 255);
      position: static;
    }
    .text {
      max-width: 100vw;
    }

    h1 {
      font-size: xx-large;
      padding: 0;
    }
    p {
      padding: 0;
      font-size: small;
    }
  }

  @media screen and (max-width: 950px) {
    div {
      width: 100%;
      height: auto;
    }
    img {
      /* width: 100vh; */
      height: auto;
    }

    .hours {
      transform: none;
      color: rgb(255, 255, 255);
      position: static;
    }
    .text {
      max-width: 100vw;
    }

    h1 {
      font-size: xx-large;
      padding: 0;
    }
    p {
      padding: 0;
      font-size: small;
    }
  }
</style>
