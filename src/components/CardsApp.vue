<script setup>

</script>

<template>
  <main>
    <section class="cards">
      <ul>
        <li class="um">
          <p>OUR STORY</p>
        </li>
        <li class="dois">
          <p>THE DETAILS</p>
        </li>
      </ul>
      <ul>
        <li class="tres">
          <p>RSVP</p>
        </li>
        <li class="quatro">
          <p>REGISTRY</p>
        </li>
      </ul>
    </section>
  </main>
</template>

<style scoped>

  section ul {
    display: flex;
    justify-content: center;
  }

  ul li {
    padding: 16vw 12vw;
    width: 30%;
    height: 0vw;
    border-radius: 15px;
    margin: 2vw;
    text-align: center;
  }

  ul li p {
    color: white;
    text-decoration: underline;
    font-size: 1.5vw;
  }

  ul li.um {
    background-image: url(img/cards01.png);
  }
  ul li.dois {
    background-image: url(img/cards02.png);
  }
  ul li.tres {
    background-image: url(img/cards03.png);
  }
  ul li.quatro {
    background-image: url(img/cards04.png);
  }
</style>
