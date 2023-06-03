<script lang="ts">
  import ServiceImages from "./serviceImages.svelte";
  import Blowdry from "./adam-winger-FkAZqQJTbXM-unsplash.jpg";
  import Extensions from "./adam-winger-2lrUavqMcVs-unsplash.jpg";
  import Dye from "./adam-winger-R0aIHC3SSUU-unsplash.jpg";
</script>

<h2>SERVICES</h2>
<div class="images">
  <ServiceImages
    photo={Blowdry}
    altTag="Blow-dry"
    title="Blow-dry"
    description="We offer a blow-dry subscription service including... ... and .... Our expertly trained staff ............. "
  />
  <ServiceImages
    photo={Extensions}
    altTag="Hair Extensions"
    title="Hair Extensions"
    description="We offer a variety of extensions including... ... and .... Our expertly trained staff ............. "
  />
  <ServiceImages
    photo={Dye}
    altTag="Hair Dye"
    title="Professional Styling"
    description="We offer a range of cutting and dyeing services ... ... and .... Our expertly trained staff ............. "
  />
</div>

<style>
  h2 {
    text-align: center;
  }
  .images {
    display: flex;
    width: 100%;
    justify-content: space-around;
  }
</style>
