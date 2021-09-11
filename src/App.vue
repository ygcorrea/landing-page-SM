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
    <section class="fourth-section">
      <div class="fourth-section-container">
        <div class="fourth-section-title">
          <h2>O programa de mentoria</h2>
        </div>
        <div class="program-section">
          <div class="program-first-column">
            <div class="pos-rel">
              <div class="box1-top"></div>
              <h4>Treinamento Completo</h4>
              <h3>Smart Money</h3>
              <p>
                3 módulos completos para você aprender a criar, recriar, escalar
                e captar investimento.
              </p>
            </div>
            <div class="pos-rel">
              <div class="box1-bottom"></div>
              <h4>Smart</h4>
              <h3>Black Book</h3>
              <p>
                O livro negro para fazer dinheiro inteligente entregue na sua
                casa.
              </p>
            </div>
          </div>
          <div class="program-second-column">
            <div class="pos-rel">
              <div class="box2-top"></div>
              <h4>51 anos em</h4>
              <h3>51 dias</h3>
              <p>
                7 semanas de mentoria com 2 encontros semanais, sendo 1 encontro
                com João Kepler e 1 encontro com um mentor convidado.
              </p>
              <div class="box2-bottom"></div>
            </div>
          </div>
          <div class="program-third-column">
            <div>
              <h4>Jk</h4>
              <h3>Canva</h3>
              <p>
                O material de uma única página para construir o seu negócio
                baseado nas 10 perguntas inteligentes.
              </p>
            </div>
            <div>
              <h4>Comunidade</h4>
              <h3>Smart Money</h3>
              <p>Grupo exclusivo para os mentorados Smart Money.</p>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="fifth-section">
      <div class="fifth-section-container">
        <div class="fifth-section-main-content">
          <div class="fifth-section-title">
            <h2>Bônus <font color="#00E1BE">exponenciais</font></h2>
          </div>
          <div>
            <div class="fifth-section-card-bonus">
              <div class="card-bonus1">
                <h3>Imersão bossa nova</h3>
                <p>
                  20 mentorados terão o privilé-<pre>gio de estar presencialmente</pre>
                  comigo em uma imersão.
                <pre><font color="#00E1BE">10 PRIMEIROS QUE COMPRAREM.</font></pre>
                <pre>10 escolhidos, se você adquirir</pre> a mentoria até <strong>23:59 do dia 12/11.</strong>
                </p>
              </div>
              <div class="card-bonus2">
                <h3>Livros autografados</h3>
                <p>
                  Eu vou te enviar um pacote ex-<pre>clusivo de livros autografados:</pre>
                 <font color="#00E1BE"><pre>100% presente do Joel Jota, Do</pre><pre>mil ao Milhão do Thiago Nigro.</pre>
                  </font>
                  e meu livro <font color="#00E1BE">Smart Money.</font> So-<pre>mente para quem adquirir a</pre>
                 mentoria até <strong>23:59 do dia 12/11.</strong>
                </p>
              </div>
              <div class="card-bonus3">
                <h3>
                  Palestra exclusiva
                  <pre>como investir em startup</pre>
                </h3>
                <p>
                  Metodologia para você além de<pre>se tornar um empreendedor lu-</pre>crativo,
                  <font color="#00E1BE">saber como investir</font>
                  em negócios exponenciais.
                </p>
              </div>
            </div>
            <div class="line-bottom"></div>
            <div class="fifth-section-card-bonus">
              <div class="card-bonus1">
                <h3>
                  Gravação
                  <pre>o negócio mais</pre>
                  lucrativo do mundo
                </h3>
                <p>
                 <pre> Todas as lives que fizemos du-</pre><pre>rante a imersão disponibiliza-</pre>das
                  para você
                  <font color="#00E1BE">assistir quando quiser.</font>
                </p>
              </div>
              <div class="card-bonus2">
                <h3>
                  Seminário como
                  <pre>tirar seu projeto</pre>
                  do papel por joel jota
                </h3>
                <p>
                  Seminário do meu amigo
                  <font color="#00E1BE"> Joel Jota </font>
                  para te ensinar o passo a passo para tirar seu projeto do
                  papel.
                </p>
              </div>
              <div class="card-bonus3">
                <h3>
                  Branding digital
                  <pre>by hyeser</pre>
                </h3>
                <p><pre>Como <font color="#00E1BE">se tornar autoridade</font> utili-</pre>zando
                  as redes sociais.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
     <section class="sixth-section">
        <div class="sixth-section-container pos-rel">
          <div class="sixth-section-title">
            <h2>Quanto vale tudo isso?</h2>
          </div>
            <div class="sixth-section-content">
              <h3>Quanto vale conquistar sua liberdade de escala e financeira?</h3>
              <p>
                Quanto vale sair do campo da ideia de uma vez por todas e construir um <pre>negócio lucrativo e exponencial?</pre>
              </p>
            </div>
            <div class="price-section">          
              <h5>De <font >R$ 2.500,00</font> por</h5>
              <div class="value">
              <div>R$</div> 
              <img src="./assets/Value.png" alt="">
              <span>a vista</span> 
              </div>
              <p>ou 12 X R$ 197,00</p>
           </div>
          <button type="submit" class="absolute">Fazer Inscrição</button>
        </div>
    </section>
     <section class="seventh-section">
        <div class="seventh-section-container" >
            <h2>7 dias de garantia</h2>
            <p>Adquirindo o nosso programa de mentoria SMART MONEY e percebendo que
              <pre>você ainda não está pronto para conquistar sua liberdade de escala e financei-</pre>ra,
                basta nos enviar um e-mail e iremos reembolsar o valor imediatamente.
                <pre>Sem perguntas, nem pedidos de justificativas.</pre>
                <pre>Simples assim. Esse é o reflexo de confiança que temos na qualidade do conhe-</pre> cimento que você está
                prestes a adquirir.
            </p>
        </div>
    </section>
     <section class="eighth-section">
        <div class="eighth-section-container">
            <img src="./assets/KeplerRounded.png" />
            <div class="eight-section-main-content">
              <div class="eighth-section-title">
                  <h2>João Kepler</h2>
                  <h3>O maior investidor do <pre>Brasil vai ser seu mentor</pre></h3>
              </div>
              <div class="eighth-section-text">
                  <h4><pre>Empreendedor que investe desde 2008, reconhecido como um dos conferencistas mais sintonizados</pre>
                  com inovação e convergência digital do Brasil,é especialista em empreendedorismo,
                  <pre>
                    startups, marketing e vendas.
                  </pre>
                  </h4>
                  <p>Participa em +400 StartUps: Lead Partner da Bossa Nova Investimentos; Premiado como melhor Investidor Anjo do Brasil pelo <pre>
                    Startup Awards: Diretor na FIESP e na ASSESPRO; Conselheiro na ACE, ANPROTEC e ACSP; Colunista de diversos Portais do Brasil;</pre> 
                    Palestrante internacional; Escritor e autor e coautor devários Livros, entre les o (O vendedor na Era Digital), (Eduvando Filhos
                    <pre> para Empreender), (Smart Money) e (Gestão Ágil); Premiado por anos consecutivos como um dos maiores Incentivadores do Ecos-</pre> 
                    sistema Empreendedor Brasileiro; Espalhador de Ideias Digitais e Melhores Práticas em Negócios.
                  </p>
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
  height: 880px;
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
  color: #fcf7f7;
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
  color: #fcf7f7;
  padding: 20px;
  border-left: 2px solid #00e1be;
}
.third-section-content p:first-child {
  border: none;
}

.third-section-mentoring h3 {
  font-size: 45px;
  font-weight: 400;
  color: #fcf7f7;
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
  color: #fcf7f7;
  text-transform: uppercase;
}

.third-section-instructors {
  display: flex;
  justify-content: space-between;
  height: 300px;
}
/* Fourth Section */
.fourth-section {
  width: 100%;
  height: 620px;
  background: #e0e0e0;
}

.fourth-section-container {
  width: 1040px;
  height: 100%;
  margin: 0 auto;
  align-items: center;
  justify-content: center;
}

.fourth-section-title h2 {
  width: 100%;
  height: 130px;
  font-size: 50px;
  font-family: "Roboto", sans-serif;
  color: #001e1f;
  text-transform: uppercase;
  display: flex;
  justify-content: flex-end;
  align-items: center;
  letter-spacing: 3.5px;
}

.program-section {
  display: flex;
  align-items: center;
  justify-content: space-between;
  height: 400px;
  width: 1000px;
}
.program-first-column {
  justify-content: center;
  flex-direction: column;
  gap: 50px;
}

.program-third-column {
  flex-direction: column;
  justify-content: center;
  gap: 50px;
}

.program-first-column h4,
.program-second-column h4,
.program-third-column h4 {
  font-size: 22px;
  font-weight: 600;
  color: #011c1c;
  text-transform: uppercase;
}

.program-first-column h3,
.program-second-column h3,
.program-third-column h3 {
  font-size: 45px;
  font-weight: 600;
  color: #00aa89;
  text-transform: uppercase;
}

.program-first-column p,
.program-second-column p,
.program-third-column p {
  font-size: 19px;
  font-weight: 400;
  color: #00211b;
  letter-spacing: 1.2px;
}
.program-first-column,
.program-second-column,
.program-third-column {
  width: 295px;
  height: 100%;
  display: flex;
  align-items: center;
}
.box1-top {
  border-top: 3px solid #00aa89;
  border-right: 3px solid #00aa89;
  position: absolute;
  left: 246px;
  width: 113px;
  height: 50px;
  top: 10px;
}
.box1-bottom {
  border-bottom: 3px solid #00aa89;
  border-right: 3px solid #00aa89;
  position: absolute;
  left: 278px;
  width: 80px;
  height: 120px;
  top: 60px;
}
.box1-bottom:after {
  content: "";
  width: 57px;
  transform: rotate(90deg);
  background-color: #00aa89;
  position: absolute;
  right: 50px;
  top: 90px;
  border-top: 3px solid #00aa89;
}
.box2-top {
  border-top: 3px solid #00aa89;
  border-left: 3px solid #00aa89;
  position: absolute;
  left: 208px;
  width: 144px;
  height: 150px;
  bottom: 116px;
}
.box2-bottom {
  border-bottom: 3px solid #00aa89;
  border-left: 3px solid #00aa89;
  position: absolute;
  left: 208px;
  width: 151px;
  height: 144px;
  top: 170px;
}
.box2-bottom:after {
  content: "";
  width: 45px;
  transform: rotate(90deg);
  background-color: #00aa89;
  position: absolute;
  top: 120px;
  left: 125px;
  border-top: 3px solid #00aa89;
}

/* Fifth section */
.fifth-section {
  width: 100%;
  height: 800px;
  background: url(./assets/Graphic.png);
  background-repeat: no-repeat;
  background-size: cover;
}

.fifth-section-container {
  width: 100%;
  height: 100%;
  background: #021a1bab;
  display: flex;
  align-items: center;
  justify-content: center;
}
.fifth-section-main-content {
  display: flex;
  flex-direction: column;
  justify-content: center;
  width: 1050px;
  align-items: center;
}

.fifth-section-title {
  text-align: center;
  margin-bottom: 60px;
}

.fifth-section-title h2 {
  font-size: 80px;
  font-weight: 700;
  color: #fcf7f7;
  text-transform: uppercase;
}

.fifth-section-card-bonus {
  width: 100%;
  display: flex;
}

.card-bonus1,
.card-bonus2,
.card-bonus3 {
  width: 315px;
  height: 255px;
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  padding: 0px 0px 0px 20px;
}

.card-bonus2 {
  border-left: 2px solid #00aa89;
  border-right: 2px solid #00aa89;
}

.card-bonus1 p,
.card-bonus2 p,
.card-bonus3 p {
  width: 257px;
  font-size: 20px;
  letter-spacing: 0px;
  color: #fcf7f7;
  padding: 10px 0px 0px 10px;
}

.card-bonus1 h3,
.card-bonus2 h3,
.card-bonus3 h3 {
  font-size: 24px;
  font-weight: 700;
  color: #fcf7f7;
  text-transform: uppercase;
  padding: 10px 0px 0px 10px;
}

.line-bottom {
  width: 100%;
  border-bottom: 2px solid #00aa89;
}

/* Sixth section */

.sixth-section {
  width: 100%;
  height: 650px;
  background: #e0e0e0;
  display: flex;
  justify-content: center;
}

.sixth-section-container {
  width: 1040px;
  height: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  gap: 50px;
  margin-top: 40px;
}

.sixth-section-container p {
  font-size: 25px;
  color: #000000;
}
.sixth-section-container h2 {
  font-size: 60px;
  font-weight: 700;
  color: #001e1f;
  text-transform: uppercase;
  height: 55px;
}

.sixth-section-container h3 {
  font-size: 30px;
  font-weight: 700;
  color: #000000;
  text-transform: uppercase;
}
.sixth-section-container h4 {
  font-size: 70px;
  font-weight: 700;
  color: #001e1f;
  text-transform: uppercase;
}
.sixth-section-container h5 {
  font-size: 50px;
  color: #001e1f;
  text-transform: uppercase;
  font-weight: 400;
  margin-bottom: 10px;
  margin-right: 15px;
  letter-spacing: 0px;
}
.sixth-section-title {
  border-bottom: 2px solid;
  height: 87px;
  width: 830px;
}
.sixth-section-content {
  text-align: center;
}
.price-section .value {
  display: flex;
  font-size: 40px;
  font-weight: 600;
}
.price-section .value span {
  margin-left: 10px;
  align-self: flex-end;
  text-transform: uppercase;
  font-size: 40px;
}
.price-section .value div {
  margin-right: 10px;
  padding-left: 70px;
  font-size: 50px;
}
.price-section .value img {
  width: 407.36px;
  height: 128.19px;
}
.price-section p {
  font-size: 40px;
}
.price-section font {
  text-decoration: line-through;
  color: #7a7a7a;
  text-decoration-color: #001e1f;
}
.sixth-section-container .absolute {
  width: 362px;
  position: absolute;
  color: #011913;
  font-size: 35px;
  top: 580px;
  height: 60px;
  cursor: pointer;
  background: #00e1be;
  border-radius: 20px;
  text-transform: uppercase;
  font-weight: bold;
}
/* Seventh section */
.seventh-section {
  width: 100%;
  height: 637px;
  background: #001e1f;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

.seventh-section-container {
  width: 1040px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  text-align: center;
  height: 100%;
  gap: 10px;
  margin-bottom: 100px;
}

.seventh-section-container h2 {
  font-size: 45px;
  font-weight: 700;
  color: #00e1be;
  text-transform: uppercase;
}

.seventh-section-container p {
  width: 900px;
  font-size: 25px;
  line-height: 40px;
  font-weight: 400;
  color: #ffffff;
  letter-spacing: 1px;
}
/* Eighth section */
.eighth-section {
  width: 100%;
  height: 100%;
  background: #e0e0e0;
  display: flex;
  justify-content: center;
  align-items: center;
  position: relative;
}

.eighth-section-container {
  height: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: flex-start;
  text-align: center;
  margin-top: 120px;
}

.eighth-section-container img {
  width: 166px;
  height: auto;
  position: absolute;
  top: -70px;
}

.eighth-section-title {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 100%;
  gap: 20px;
}

.eighth-section-title h2 {
  font-size: 70px;
  margin-left: 75px;
  font-weight: 700;
  color: #00e1be;
  text-transform: uppercase;
}

.eighth-section-title h3 {
  width: 500px;
  font-size: 35px;
  line-height: 35px;
  font-weight: 700;
  color: #1a1a1a;
  text-transform: uppercase;
  text-align: left;
}

.eighth-section-text h4 {
  font-size: 20px;
  line-height: 25px;
  font-weight: 700;
  color: #000000;
  text-transform: uppercase;
  padding: 40px 0 0 0;
}

.eighth-section-text p {
  width: 900px;
  font-size: 17px;
  line-height: 20px;
  font-weight: 600;
  color: #474747;
  line-height: 28px;
}
.eight-section-main-content{
  margin-bottom: 100px;
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
.pos-rel {
  position: relative;
}
</style>
