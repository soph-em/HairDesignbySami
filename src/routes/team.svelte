<script lang="ts">
  import team from "./adam-winger-fI-TKWjKYls-unsplash.jpg";
</script>

<section>
  <h2 class="text-divider">OUR TEAM</h2>
  <div class="images">
    <img alt="our team" src={team} />
    <p>
      Our team is made up of Sammi our creative director & salon director, Emma
      our senior stylist, and Michelle our graduate stylist.
      <br />
      <br />
      At Sammi's, we all love what we do and who we do it for. We offer a friendly
      and relaxed salon and offer a friendly and thorough consult to ensure you leave
      the salon with hair you love.
    </p>
  </div>
</section>

<style>
  section {
    padding-top: 5px;
    background-color: rgb(244, 250, 250);
    height: 450px;
  }
  h2 {
    text-align: center;
  }

  img {
    height: 300px;
    padding-top: 150px;
    padding-right: 100px;
  }

  p {
    width: 400px;
    font-size: large;
    padding-top: 100px;
  }
  .images {
    display: flex;
    /* width: 80%; */
    justify-content: space-between;
    /* justify-self: center; */
    /* align-items: center; */
    /* flex-direction: row; */
    align-items: center;
    justify-content: center;
    height: 200px;
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
</style>
