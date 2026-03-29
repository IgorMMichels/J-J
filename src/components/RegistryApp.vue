<script setup></script>

<template>
  <section class="registry">
    <div>
      <h2>Registry</h2>
      <h3>
        Your presence is the most cherished gift. Should you wish to contribute, we’ve created a
        honeymoon registry to help us embark on a memorable adventure to the Amalfi Coast.
      </h3>
      <button>GO TO REGISTRY</button>
    </div>
  </section>
</template>

<style scoped>
h2 {
  font-family: 'Aboreto';
  font-size: 3vw;
  text-align: center;
  color: white;
}

section {
  margin: 0 0 2vw 0;
}

section div {
  background-image: url(img/greenBanner.png);
  background-size: cover;
  padding: 10vw;
}

.registry h3 {
  color: white;
  font-size: 2vw;
  text-align: center;
  margin: 1vw 21.2vw;
  font-family: serif;
}

button {
  text-align: center;
  display: block;
  margin: 0 auto;
  font-size: 1.3vw;
  padding: 18px 170px;
  border-radius: 35px;
  background-color: #76705c;
  color: #c6c2ae;
}

@media screen and (max-width: 650px) {
  button {
    text-align: center;
    display: block;
    margin: 0 auto;
    font-size: 3vw;
    padding: 8px 50px;
    border-radius: 35px;
    background-color: #76705c;
    color: #c6c2ae;
  }

  .registry h3 {
    color: white;
    font-size: 2.8vw;
    text-align: center;
    margin: 2vw 6vw;
    font-family: serif;
  }
  section div {
    background-image: url(img/greenBanner.png);
    background-size: cover;
    padding: 15vw;
  }
}
</style>
