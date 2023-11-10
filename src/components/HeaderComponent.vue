<template>
  <header class="header">
    <section class="head-section">
      <div class="back">
        <nav>
          <ul>
            <li>
              <router-link to="/">Home</router-link>
            </li>
            <li>
              <router-link to="/about">Calculator</router-link>
            </li>
            <li>
              <router-link to="/table">Table</router-link>
            </li>
          </ul>
        </nav>
      </div>
    </section>
  </header>
</template>

<script>
export default {
  name: "HeaderComponent",
};
</script>

<style scoped>
.header {
  background: url("../assets/img/main.jpg") center/cover no-repeat;
  color: #ffffff;
  padding: 20px;
  height: 20vh;
}

.head-section{
  background-color: #ffffff;
  height: 100%;
  width: 100%;
  border: 1px solid black;
}

.header-content {
  background-color: rgba(
    0,
    123,
    255,
    0.6
  ); /* Add an overlay to make text more readable */
  padding: 10px;
}

nav ul {
  list-style: none;
  padding: 0;
  display: flex;
  justify-content: center;
}

nav ul li {
  margin: 0 20px;
  cursor: pointer;
  font-weight: bold;
  transition: all 0.3s ease;
}

nav ul li:hover {
  text-decoration: underline;
}
</style>
