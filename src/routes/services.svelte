<script lang="ts">
  import ServiceImages from "./serviceImages.svelte";
  import Blowdry from "./adam-winger-FkAZqQJTbXM-unsplash.jpg";
  import Extensions from "./adam-winger-2lrUavqMcVs-unsplash.jpg";
  import Dye from "./adam-winger-R0aIHC3SSUU-unsplash.jpg";
</script>

<section>
  <h2 class="text-divider">SERVICES</h2>
  <div class="images">
    <ServiceImages
      photo={Blowdry}
      altTag="Cutting"
      title="Cutting"
      description="We provide professional cutting services after a thorough consultation. "
    />
    <ServiceImages
      photo={Extensions}
      altTag="Colouring"
      title="Colouring"
      description="We offer a variety of colouring services to suit you while keeping your hair happy and healthy. "
    />
    <ServiceImages
      photo={Dye}
      altTag="Styling"
      title="Styling"
      description="We offer a range of styling services including extensions, party, and wedding services. "
    />
  </div>
</section>

<style>
  section {
    background-color: rgb(253, 250, 252);
    padding-top: 20px;
  }
  div {
    padding-bottom: 20px;
  }
  h2 {
    text-align: center;
  }
  .images {
    display: flex;
    width: 100%;
    justify-content: space-around;
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
    .images {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
    }
  }
  @media screen and (max-width: 1200px) {
    .images {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
    }
  }
</style>
