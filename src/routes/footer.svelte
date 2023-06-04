<footer>
  <h2 class="logo">Sammi.</h2>
  <p>
    8 Meadowbank<br />Eastfield<br />BN11 1EG
  </p>
  <p>01903 216388</p>
  <div class="credits">
    <p>
      Website by
      <a href="https://github.com/soph-em">Sophie Earl</a>
    </p>

    <p>
      Header photo by <a
        href="https://unsplash.com/de/@m_malkovich?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText"
        >petr sidorov</a
      >
      on
      <a
        href="https://unsplash.com/@m_malkovich?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText"
        >Unsplash</a
      >
    </p>
    <p>
      Other photos by <a
        href="https://unsplash.com/ko/@awcreativeut?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText"
        >Adam Winger</a
      >
      on
      <a
        href="https://unsplash.com/photos/fI-TKWjKYls?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText"
        >Unsplash</a
      >
    </p>
  </div>
</footer>

<style>
  .credits {
    align-items: right;
    padding-right: 100px;
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
  footer {
    height: 120px;
    background-color: gainsboro;
    display: flex;
    justify-content: space-between;
  }
  p {
    color: darkgray;
    margin: 5px;
    padding-top: 5px;
  }

  a {
    color: darkgray;
    margin: 0;
  }

  @media screen and (max-width: 500px) {
    .credits {
      padding: 0;
      align-items: center;
      padding-top: 10px;
    }
    footer {
      height: fit-content;
      display: flex;
      flex-direction: column;
      justify-content: center;
    }
    .logo {
      font-size: 60px;
      padding: 0;
      text-align: center;
    }
    p {
      margin: 0;
      padding: 0;
      align-self: center;
      text-align: center;
    }
  }
</style>
