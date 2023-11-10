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
  color: #00001a;
  padding: 20px;
  height: 20vh;
}

.head-section{
  height: 100%;
  width: 100%;
}

.back{
  background-color: rgba(255, 255, 255, 0.5);
  height: 100%;
  width: 100%;
  border: 1px solid black;
  border-radius: 2vh;
  display: flex;
  align-items: center;
  justify-content: center;
}

nav {
  /* border : 1px solid black; */
  width: 50%;
  padding: 5px;
}

nav ul {
  list-style: none;
  display: flex;
  column-gap: 12vh;
  justify-content: center;
}

nav ul li {
  cursor: pointer;
  font-weight: bold;
  padding: 5px;
  font-size: 35px;
  transition: all 0.3s ease;
  border: 2px solid transparent;
}

nav ul li:hover {
  border-bottom: 2px solid white;
}
</style>
