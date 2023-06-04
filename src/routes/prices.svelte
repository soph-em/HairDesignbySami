<script lang="ts">
  import salon from "./adam-winger-AyesubMzQ64-unsplash.jpg";
</script>

<section>
  <h2 class="text-divider">OUR PRICES</h2>
  <div class="images">
    <img alt="our salon" src={salon} />

    <div class="table">
      <div class="table-row">
        <div class="table-cell1 top">Service</div>
        <div class="table-cell top">Creative Director</div>
        <div class="table-cell top">Senior Stylist</div>
        <div class="table-cell top">Graduate Stylist</div>
      </div>
      <div class="table-row">
        <div class="table-cell1">Cut and Blow Dry</div>
        <div class="table-cell">£48</div>
        <div class="table-cell">£43</div>
        <div class="table-cell">£38</div>
      </div>
      <div class="table-row">
        <div class="table-cell1">Blow Dry</div>
        <div class="table-cell">£30</div>
        <div class="table-cell">£30</div>
        <div class="table-cell">£25</div>
      </div>
      <div class="table-row">
        <div class="table-cell1">Highlights</div>
        <div class="table-cell">£65</div>
        <div class="table-cell">£60</div>
        <div class="table-cell">£55</div>
      </div>
      <div class="table-row">
        <div class="table-cell1">Balyage</div>
        <div class="table-cell">£120</div>
        <div class="table-cell">£110</div>
        <div class="table-cell">£90</div>
      </div>
      <div class="table-row">
        <div class="table-cell1">Full Head Colour</div>
        <div class="table-cell">£60</div>
        <div class="table-cell">£55</div>
        <div class="table-cell">£50</div>
      </div>
      <p>Other services available on consultation.</p>
    </div>
  </div>
</section>

<style>
  .top {
    font-weight: bold;
  }
  div {
    font-family: "Montserrat", sans-serif;
  }
  .table {
    padding-top: 150px;
  }
  .table-row {
    display: flex;
    max-width: fit-content;
  }

  .table-cell {
    padding: 1em;
    /* border: 1px solid black; */
    width: 150px;
  }

  .table-cell1 {
    padding: 1em;
    /* border: 1px solid black; */
    width: 150px;
  }

  .table-row:nth-child(even) {
    background: lightblue;
  }

  section {
    padding-top: 5px;
    background-color: rgb(248, 253, 250);
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
  }
  .images {
    display: flex;
    justify-content: space-between;
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

  @media screen and (max-width: 500px) {
    section {
      height: fit-content;
      max-width: 100vw;
    }
    .images {
      display: flex;
      flex-direction: column;
      justify-content: center;
      height: fit-content;
      max-width: 100vw;
    }
    img {
      max-width: 80vw;
      height: auto;
      padding: 0;
    }
    .table {
      padding: 0;
    }
    .table-cell {
      width: 50px;
    }
    .table-cell1 {
      width: 50px;
    }

    p {
      max-width: 70vw;
      text-align: center;
    }

    div {
      font-size: small;
    }
  }
</style>
