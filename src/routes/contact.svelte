<script lang="ts">
  import salon from "./adam-winger-ZsUbK9zSgMo-unsplash.jpg";
</script>

<section>
  <h2 class="text-divider">BOOKING</h2>
  <div class="content">
    <img alt="salon" src={salon} />
    <div>
      <p class="description">
        For more information about our salon and services, or if you would like
        to book an appointment or a consultation, please get in touch.
      </p>

      <h3>Details</h3>
      <p>
        8 Meadowbank<br />Eastfield<br />BN11 1EG
      </p>
      <p>01903 216388</p>

      <h3>Opening Hours</h3>
      <p>Tuesday-Sunday: 8am-6pm</p>
    </div>
  </div>
</section>

<style>
  section {
    padding-bottom: 50px;
  }
  p {
    max-width: 500px;
    text-align: center;
  }
  .description {
    text-align: left;
  }
  .content {
    display: flex;
    justify-content: space-between;
    align-items: center;
    justify-content: center;
  }
  img {
    height: 300px;
    padding-right: 30px;
  }
  h2 {
    text-align: center;
  }
  h3 {
    text-align: center;
  }

  .text-divider {
    display: flex;
    align-items: center;
  }

  .text-divider::before,
  .text-divider::after {
    content: "";
    height: 1px;
    background-color: black;
    flex-grow: 1;
  }

  @media screen and (max-width: 500px) {
    .content {
      display: flex;
      flex-direction: column;
    }

    img {
      max-width: 80vw;
      height: auto;
      padding: 0;
    }

    p {
      max-width: 80vw;
      text-align: center;
    }

    .description {
      text-align: center;
    }
  }
</style>
