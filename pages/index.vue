<template>
  <main class="main-content">
    <header>
      <section class="navbar">
        <a href="#">Lan<span>D</span>ier</a>

        <nav>
          <ul>
            <li>
              <a href="#"><i class="bx bx-home"></i></a>
            </li>
            <li><a href="#">Pricing</a></li>
            <li><a href="#">Features</a></li>
            <li><a href="#">Services</a></li>
            <li><a href="#" class="btn">Signup</a></li>
          </ul>
        </nav>
      </section>

      <section class="hero">
        <h1>Brave is the new awesome</h1>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempore aut
          omnis porro, sit doloribus autem numquam adipisci aliquam non dolorem
          exercitationem, animi necessitatibus, mollitia odit tempora odio
          sapiente!
        </p>
        <a href="#">Get Started <i class="bx bx-right-arrow-alt"></i></a>
      </section>
    </header>
  </main>
</template>

<script>
export default {
  name: 'IndexPage',
};
</script>

<style scoped>
main {
  position: relative;
  width: 100vw;
  max-width: 100vw;
  height: 100vh;
  max-height: 100vh;
  /* background: linear-gradient(rgba(0, 0, 0, 0.9), rgba(0, 0, 0, 0.7)),
    url('~assets/images/tunnel-bg.jpg'); */
  background-position: center;
  background-repeat: no-repeat;
}
header {
  position: relative;
  width: 100vw;
  max-width: 100vw;
  height: 100vh;
  max-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
.navbar {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 15px 30px;
}

.navbar > a {
  font-size: 1.8rem;
  font-weight: 800;
  color: #090948;
  text-transform: uppercase;
}
.navbar a span {
  font-weight: 800;
  color: #ffb0be;
}

.navbar nav ul {
  list-style-type: none;
  display: flex;
}

.navbar nav ul li {
  margin: 0 10px;
}
.navbar nav ul li a {
  padding: 12px 20px;
  color: #090948;
  font-weight: 500;
}
.navbar nav ul li a.btn {
  background: #090948;
  color: #fff;
  border-radius: 4px;
}
.navbar nav ul li a:hover {
  cursor: pointer;
}

.hero {
  width: 50%;
  /* border: 1px solid red; */
  text-align: center;
}
.hero h1 {
  font-size: 2.6rem;
  margin-bottom: 5px;
  text-transform: uppercase;
  color: #090948;
  font-weight: 800;
}
.hero p {
  line-height: 1.5;
  font-weight: 400;
  color: #090948;
  margin-bottom: 20px;
}
.hero a {
  display: inline-block;
  background: #090948;
  color: #fff;
  padding: 15px 35px;
  border-radius: 4px;
  transition: background 0.15s ease;
}
.hero a:hover {
  background: #000027;
}
</style>
