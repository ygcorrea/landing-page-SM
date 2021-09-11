<template>
  <div>
    <section class="first-container">
      <div class="header-bar"></div>
      <div class="main-section">
        <div class="text-section">
          <h3>Mentoria</h3>
          <span class="first-title">
            <h1>S<font color="#00E1BE">m</font>art</h1>
            <h1>M<font color="#00E1BE">oney</font></h1>
          </span>
          <div class="subtitle-container">
            <p>
              Aprenda a
              <font color="#00E1BE">metodologia de bilionários</font> e grandes
              investidores para fazer
            </p>
            <span> dinheiro de forma inteligente </span>
            <span>e construir sua liberdade de escala e financeira.</span>
          </div>
          <button class="subscribe-button" type="submit">
            Fazer Inscrição
          </button>
        </div>
        <div class="img-section">
          <img src="./assets/Kepler.png" alt="" />
        </div>
      </div>
    </section>
    <section class="second-container">
      <div class="second-title">
        <h2>
          Eu vou revelar <font color="#00E1BE">tudo que fiz e faço</font> a
          frente de 400 <span> STARTUPs </span> e que você precisa fazer para
          <font color="#00E1BE">conquistar</font> sua liberdade.
        </h2>
      </div>
      <div class="second-list">
        <h2>Mesmo que:</h2>
        <ul>
          <li>
            Você só tenha uma ideia, eu vou te ensinar como tirar seu projeto do
            papel;
          </li>
          <li>
            Você esteja começando, eu vou te mostrar como validar seu negócio
            rápido e barato;
          </li>
          <li>
            Você se sinta no platô, eu vou te entregar a metodologia para
            escalar seu negócio;
          </li>
          <li>
            Você não saiba como expandir seu negócio, eu vou te treinar para
            captar investimento.
          </li>
        </ul>
      </div>
      <div class="second-container-mid">
        <p>
          Independente do que esteja te travando atualmente,<br />
          eu vou te entregar o
          <font class="steps" color="#001E1F">passo a passo</font>
          para você ir do zero ao nível máximo da escala e conquistar sua
          liberdade.
        </p>
      </div>
      <div class="second-container-bottom">
        <h3>A verdade é que:</h3>
        <p>
          Ou você domina como criar um negócio baseado em<br />
          equity ou vira escravo da sua empresa.
        </p>
        <button class="subscribe-button" type="submit">Fazer Inscrição</button>
      </div>
    </section>

    <section class="third-section">
      <div>
        <div class="third-section-title">
          <div class="subtitle">
            <p>Tudo o</p>
            <p>que você vai</p>
            <span>aprender</span>
            <span>:</span>
          </div>
          <div class="third-section-mentoring">
            <h3>Mentoria</h3>
            <div class="third-section-smart-money">
              <h2>S<font color="#00E1BE">m</font>art</h2>
              <h2>M<font color="#00E1BE">oney</font></h2>
            </div>
          </div>
        </div>
        <div class="third-section-content">
          <p v-for="item in howTo" :key="item">{{ item }}</p>
        </div>
        <div class="third-section-instructors">
          <div class="third-section-instructors-title">
            <h3>7 Mentores <font color="#00E1BE">especialistas</font></h3>
          </div>
          <div>
            <img src="./assets/Instructors.png" />
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      howTo: [
        "Como criar um negócio lucrativo e exponencial, antes de investir tempo e dinheiro.",
        "Como se destacar no mercado na era competitiva.",
        "Como criar uma gestão eficaz e processos escaláveis.",
        "Como driblar os erros mais comuns dos empreendedores.",
        "Como dominar o nível máximo da escala de um negócio.",
      ],
    };
  },
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
/* First section */
.first-container {
  width: 100%;
  height: 945px;
  background: #011913;
  display: flex;
  justify-content: center;
}
.main-section {
  width: 55%;
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
  letter-spacing: 23px;
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
.first-title > :first-child {
  letter-spacing: 11px;
}
.first-title {
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

.header-bar {
  width: 100%;
  height: 170px;
  position: absolute;
  top: 125px;
  background: rgba(0, 225, 190, 0.67);
  height: 79px;
  z-index: 0;
}
/* Second section */
.second-container {
  width: 100%;
  background: #001e1f;
  color: #fcf7f7;
}

.second-title {
  text-align: center;
  display: flex;
  justify-content: center;
  align-items: center;
}
.second-title span {
  text-transform: none;
}

.second-title h2 {
  color: #fcf7f7;
  font-size: 37px;
  font-weight: 400;
  padding: 84px 0 0 0;
  width: 1023px;
  text-transform: uppercase;
}

.second-list {
  width: 100%;
  height: 375px;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  flex-direction: column;
  gap: 50px;
}

.second-list h2 {
  width: 288px;
  height: 74px;
  background: #00e1be;
  font-size: 45px;
  font-weight: 700;
  text-transform: uppercase;
  align-items: center;
  display: flex;
  justify-content: center;
  text-align: center;
  color: #011913;
}

.second-list li {
  list-style-type: none;
  color: #fcf7f7;
  font-size: 18px;
  font-weight: 400;
  line-height: 40px;
  letter-spacing: 2px;
  display: flex;
  align-items: center;
  justify-content: center;
}

.second-list li::before {
  content: "•";
  display: inline-block;
  color: #00e1be;
  font-size: 30px;
  margin-right: 3px;
}

.second-container-mid {
  width: 100%;
  height: 206px;
  background: #036060;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
}

.second-container-mid font {
  font-weight: 600;
}

.second-container-mid p {
  width: 715px;
  position: relative;
  color: #fcf7f7;
  font-size: 22px;
  line-height: 50px;
  font-weight: 600;
  align-items: center;
  text-transform: uppercase;
}

.second-container-bottom {
  width: 100%;
  height: 420px;
  text-align: center;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
}

.second-container-bottom h3 {
  font-size: 30px;
  color: #00e1be;
  text-transform: uppercase;
  margin-bottom: 30px;
}

.second-container-bottom p {
  font-size: 30px;
  line-height: 40px;
  color: #fcf7f7;
}

/*  */
/* Third section */
.third-section {
  width: 100%;
  height: 1080px;
  background: #001e1f;
  display: flex;
  justify-content: center;
}

.third-section-title {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 36px;
}
.third-section-title .subtitle {
  font-size: 45px;
  color: #fcf7f7;
  text-transform: uppercase;
}
.third-section-title .subtitle span:first-of-type {
  color: #00e1be;
}
.third-section-title p:first-child {
  width: 150px;
  border: 2px solid #001e1f;
}
.third-section-title p {
  width: 280px;
  font-size: 45px;
  line-height: 50px;
  background: #00e1be;
  color: #001e1f;
  text-transform: uppercase;
  font-weight: 600;
  border: 2px solid #001e1f;
}

.third-section-smart-money {
  display: flex;
  flex-direction: column;
}

.third-section-smart-money h2 {
  width: 220px;
  font-size: 100px;
  line-height: 85px;
  color: white;
  text-transform: uppercase;
}
.third-section-smart-money h2:first-child {
  letter-spacing: 7px;
}

.third-section-content {
  width: 1025px;
  height: 180px;
  display: flex;
  align-items: stretch;
  justify-content: center;
  margin-top: 40px;
}

.third-section-content p {
  width: 180px;
  font-size: 20px;
  line-height: 25px;
  display: flex;
  justify-content: center;
  align-items: baseline;
  color: white;
  padding: 20px;
  border-left: 2px solid #00e1be;
}
.third-section-content p:first-child {
  border: none;
}

.third-section-mentoring h3 {
  font-size: 45px;
  font-weight: 400;
  color: white;
  text-transform: uppercase;
  letter-spacing: 15px;
  margin-left: 5px;
  line-height: 60px;
}

.third-section-instructors {
  width: 1020px;
  display: flex;
  flex-direction: column;
  align-items: center;
  margin-top: 60px;
  gap: 50px;
}
.third-section-instructors img {
  width: 900px;
}
.third-section-instructors-title {
  font-size: 30px;
  font-weight: 700;
  color: #fcf7f7;
  text-transform: uppercase;
}

.third-section-instructors {
  display: flex;
}

/*  */
.subscribe-button {
  width: 362px;
  height: 60px;
  cursor: pointer;
  background: #00e1be;
  border-radius: 20px;
  color: #011913;
  font-size: 35px;
  text-transform: uppercase;
  font-weight: bold;
  margin-top: 50px;
}
.subscribe-button:hover {
  opacity: 0.8;
}
.subtitle:nth-child(3) {
  color: #fcf7f7;
}
</style>
