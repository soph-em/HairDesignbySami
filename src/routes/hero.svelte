<script>
  import heroImg from "./hero.jpg";
</script>

<div>
  <img alt="woman with multi-colour hair" src={heroImg} />
  <div class="text">
    <h1>SAMMI <br /> HAIR DESIGN</h1>
    <br />
    <p>WE ALL DESERVE TO HAVE BEAUTIFUL HAIR</p>
  </div>
</div>

<style>
  div {
    /* height: 500px; */
    display: flex;
    flex-direction: column;
    position: relative;
    justify-content: center;
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
  }
  p {
    color: white;
    padding-left: 50px;
  }
  .text {
    position: absolute;
  }
</style>
