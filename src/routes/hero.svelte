<script>
  // import heroImg from "./hero.jpg";
  import hero from "./petr-sidorov-LM3pUMAwqMU-unsplash.jpg";
</script>

<div>
  <img alt="woman with multi-colour hair" src={hero} />
  <div class="text">
    <h1>HAIR DESIGN <br /> BY SAMMI</h1>
    <br />
    <p>WE ALL DESERVE TO HAVE BEAUTIFUL HAIR</p>
    <p class="hours">TUES - SUN : 8:00AM - 6:00pm</p>
  </div>
</div>

<style>
  div {
    /* height: 500px; */
    display: flex;
    flex-direction: column;
    position: relative;
    justify-content: center;
    width: 100%;
  }
  img {
    /* padding-top: 5%; */
    height: full;
    width: full;
  }
  h1 {
    color: white;
    padding-left: 50px;
    font-size: 90px;
    font-weight: lighter;
    font-family: "Roboto Mono", monospace;
  }
  p {
    color: white;
    padding-left: 50px;
    font-family: "Roboto Mono", monospace;
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
</style>
