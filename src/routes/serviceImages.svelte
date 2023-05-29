<script lang="ts">
  export let photo: string;
  export let altTag: string;
  export let title: string;
  export let description: string;
</script>

<div>
  <div class="image">
    <img src={photo} alt={altTag} />
    <h4 class="text-divider">{title}</h4>
  </div>
  <p>{description}</p>
</div>

<style>
  .text-divider {
    display: flex;
    align-items: center;
  }

  .text-divider::before,
  .text-divider::after {
    content: "";
    height: 1px;
    background-color: white;
    flex-grow: 1;
  }
  div {
    max-width: 400px;
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  .image {
    display: flex;
    flex-direction: column;
    position: relative;
    justify-content: center;
    max-width: 350px;
    max-height: 350px;
  }
  img {
    max-height: 350px;
    max-width: 350px;
  }
  h4 {
    color: white;
    font-weight: 600;
    font-size: x-large;
    font-family: "Montserrat", sans-serif;
    position: absolute;
    bottom: 0;
    /* padding-bottom: 5px; */

    left: 0;
    right: 0;
    text-align: center;
  }

  p {
    text-align: center;
  }
</style>
