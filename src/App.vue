<template>
  <div class="first-container">
    <div class="header-bar"></div>
    <section class="main-section">
      <div class="text-section">
        <h3>Mentoria</h3>
        <span class="title-text">
          <h1>S<font color="#00E1BE">m</font>art</h1>
          <h1>M<font color="#00E1BE">oney</font></h1>
        </span>
        <div class="subtitle-container">
          <p>
            Aprenda a <font color="#00E1BE">metodologia de bilionários</font> e
            grandes investidores para fazer
          </p>
          <span> dinheiro de forma inteligente </span>
          <span>e construir sua liberdade de escala e financeira.</span>
        </div>
        <button type="submit">Fazer Inscrição</button>
      </div>
      <section class="img-section">
        <img src="./assets/Kepler.png" alt="" />
      </section>
    </section>
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Roboto+Condensed&display=swap");
* {
  padding: 0;
  border: 0;
  margin: 0;
  box-sizing: border-box;
  font-family: "Roboto Condensed", sans-serif;
}
.first-container {
  width: 100%;
  height: 945px;
  background: #011913;
  /* background: tomato; */
  display: flex;
  justify-content: center;
}
.main-section {
  width: 60%;
  margin: 125px auto 0px;
  display: flex;
}
.text-section {
  display: flex;
  flex-direction: column;
}
.text-section h3 {
  line-height: 90px;
  color: #fcf7f7;
  font-size: 65px;
  text-transform: uppercase;
  letter-spacing: 25px;
  font-weight: 400;
  z-index: 3;
  margin-left: 5px;
}
.text-section h1 {
  color: #fcf7f7;
  font-size: 100px;
  line-height: 125px;
  text-transform: uppercase;
  font-size: 150px;
}
.subtitle-container p {
  color: #fcf7f7;
  width: 324px;
  font-size: 30px;
  margin-top: 35px;
  letter-spacing: 1px;
}
.subtitle-container {
  color: #fcf7f7;
  width: 481px;
  font-size: 30px;
  letter-spacing: 2px;
  line-height: 48px;
}
.title-text > :first-child {
  letter-spacing: 11px;
}
.title-text {
  letter-spacing: 0em;
}
.img-section {
  width: 580px;
  position: relative;
  z-index: 1;
}
.img-section img {
  position: absolute;
  bottom: 0px;
  z-index: 2;
  height: 950px;
}
.text-section button {
  width: 362px;
  height: 70px;
  cursor: pointer;
  background: #00e1be;
  border-radius: 20px;
  color: #011913;
  font-size: 38px;
  text-transform: uppercase;
  font-weight: bold;
  margin-top: 50px;
}
.header-bar {
  width: 100%;
  height: 170px;
  position: absolute;
  top: 125px;
  background: rgba(0, 225, 190, 0.67);
  height: 79px;
  z-index: 0;
}

/* 


.first-container_text {
  margin-top: 234px;
}

.first-container_text h1 {
  color: white;
  font-size: 100px;
  line-height: 80px;
  font-family: "Roboto", sans-serif;
  text-transform: uppercase;
  font-weight: 700;
}

.first-container_text p {
  width: 290px;
  color: white;
  font-size: 25px;
  line-height: 30px;
  font-family: "Roboto", sans-serif;
  font-weight: 400;
  margin-top: 35px;
}

.first-container_text button {
  width: 362px;
  height: 70px;
  background: #00e1be;
  border-radius: 20px;
  color: #011913;
  font-family: "Roboto", sans-serif;
  font-size: 30px;
  text-transform: uppercase;
  margin-top: 40px;
  cursor: pointer;
}

.first-container_text button:hover {
  opacity: 0.8;
}

.first-container_image img {
  width: 630px;
  height: auto;
  position: relative;
} */
</style>
