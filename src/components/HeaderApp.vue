<script setup></script>

<template>
  <header>
    <nav>
      <div class="logo">
        <h1>J&J</h1>
        <p>june 23rd, 2025</p>
      </div>

      <div class="index">
        <ul>
          <li><a href="#home">HOME</a></li>
          <li><a href="#cards">OUR STORY</a></li>
          <li><a href="#details">DETAILS</a></li>
          <li><a href="#RSPV">RSPV</a></li>
        </ul>
      </div>
    </nav>
  </header>
</template>

<style scoped>
header {
    background-color: #696766;
  margin: 0px 50px;
}
nav {
  display: flex;
  justify-content: space-between;
}

.logo h1 {
  font-family: 'Instrument Serif', serif;
  font-size: 2.5rem;
  margin: 0 24px 0 0;
}

.logo {
  display: flex;
  margin: 0 12px;
  align-items: center;
  justify-content: space-between;
}

.logo p {
  font-size: .9rem;
}

.index ul li {
  margin: 0 12px;
  font-size: 1.1rem;
  color: black;
}

.index ul {
  display: flex;
  margin: 24px 12px;
  align-items: center;
  justify-content: space-between;
}
</style>
