<script setup>
import { ref } from "vue"

</script>

<template>
  <header class="header">
    <div class="container">
      <!-- --=-=--=-=-=-=-=- Nav Start =--=--==--=-=-=-=-= -->
      <nav class="nav">
        <div class="nav_logo">
          <img src="../src/assets/img/Mask group.svg" alt="" class="nav_logo-img">
        </div>
        <ul class="nav_list">
          <li class="nav_item">
            <a href="#!" class="nav_link">Home</a>
          </li>
          <li class="nav_item">
            <a href="#!" class="nav_link">About me</a>
          </li>
          <li class="nav_item">
            <a href="#!" class="nav_link">Portfolio</a>
          </li>
          <li class="nav_item">
            <a href="#!" class="nav_link">Contact</a>
          </li>
        </ul>
      </nav>
      <!-- -=-=-=-= Header Content start -==-=--=--==--=-=-=-=-=-=-= -->
      <div class="header__content">
        <div class="header__left">
          <div class="header__title">
            <span>Hello</span> <br>
            I’m Aminov <br>
            Muhammadali
          </div>
          <div class="header__text">
            I've been engaged in web design, previous development for a year. Do you need a website design, or a
            website? Then contact me
          </div>
          <button class="header__btn">
            Contact me
          </button>
        </div>
        <div class="header__right">
          <span class="span-first">
            <img src="assets/img/doira.png" alt="">
          </span>
          <span class="span">JS</span>
          <span class="span last">UX</span>
          <span class="span ps">PS</span>
        </div>
      </div>
    </div>
  </header>
  <main>
    <section class="card__section">
      <div class="container">
        <div class="cards">
          <div class="card">
            <img class="card__icon" src="../src/assets/img/Group (13).svg" alt="">
            <div class="card__txt">Frontend</div>
          </div>
          <div class="card">
            <img class="card__icon" src="../src/assets/img/Group (13).svg" alt="">
            <div class="card__txt">Frontend</div>
          </div>
          <div class="card">
            <img class="card__icon" src="../src/assets/img/Group (13).svg" alt="">
            <div class="card__txt">Frontend</div>
          </div>
          <div class="card">
            <img class="card__icon" src="../src/assets/img/Group (13).svg" alt="">
            <div class="card__txt">Frontend</div>
          </div>
        </div>
        <div class="cards__last">
          <div class="card">
            <img class="card__icon" src="../src/assets/img/Group (13).svg" alt="">
            <div class="card__txt">Frontend</div>
          </div>
          <div class="card">
            <img class="card__icon" src="../src/assets/img/Group (13).svg" alt="">
            <div class="card__txt">Frontend</div>
          </div>
          <div class="card">
            <img class="card__icon" src="../src/assets/img/Group (13).svg" alt="">
            <div class="card__txt">Frontend</div>
          </div>
        </div>
      </div>
    </section>
    <section class="about">
      <div class="about__cards">
        <div class="about__card">
          <p class="about__txt">
            Hello again everyone! So, you already know that my name is Gleb. A little about myself: student, 18 y.o.,
            athlete-football player, I love creativity since childhood, I live in Donetsk, Ukraine. Why programming?
            Everything is elementary - I like it, the profession of the future, thanks to which I can provide myself and
            fulfill my dream - travel, at the moment I specialize in web design, front-end and back-end development,
            turnkey websites. Why should you choose me? I approach each order with great responsibility and love, as I
            want to make a name for myself, exclude plagiarism and negligence, fully study the project, the client and its
            target audience, work for quality, trying to make an order as quickly and uniquely as possible, taking into
            account all the edits and wishes.
            By trusting me, you will get the maximum return for your project, save your nerves and time.
            If you are interested in me , you want to know something more or use my services, then I will provide all my
            contacts below.
          </p>
        </div>
        <div class="about__card"></div>
      </div>
    </section>
  </main>
</template>

<style scoped>
.header {
  background: var(--card_background);
  color: var(--text_color);
}

.header__content {
  display: flex;
  margin-top: 200px;
}

.cards {
  display: flex;
  column-gap: 2.7em;
  padding-top: 113px;
}

.card__section {
  background: linear-gradient(130.68deg, #414141 0%, #2D2D2D 100.52%);
  padding-bottom: 120px;
}

.card {
  background: #2A2A2A;
  box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.47);
  border-radius: 29px;
  width: 270px;
  height: 270px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

.cards__last {
  display: flex;
  justify-content: center;
  column-gap: 2.7em;
  padding: 2.5em 0 4em 0;

}

.card__icon {
  margin-bottom: 73px;
}

.card__txt {
  font-family: 'ArodoraPro_Light';
  font-weight: 300;
  font-size: 24px;
  color: var(--text_color);
}

.span-first {
  border: 67px solid #00C4F0;
  filter: drop-shadow(0px 0px 152px rgba(0, 196, 240, 0.42));
  border-radius: 50%;
  position: absolute;
  width: 575px;
  height: 575px;
  left: 100px;
  top: -62px;
}

.span {
  width: 90px;
  height: 90px;
  background: linear-gradient(130.68deg, #414141 0%, #2D2D2D 100.52%);
  position: absolute;
  border-radius: 50%;
  top: 123px;
  left: 37px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-weight: 700;
  font-size: 40px;
  color: #00C4F0;
  font-family: 'NEXTART_Bold';
}

.ps {
  left: 660px;
}

.header__title {
  font-family: 'NEXTART_Bold';
  font-weight: 700;
  font-size: 72px;
}

.last {
  top: 396px;
  left: 100px;
}

.header__btn {
  font-family: 'NEXTART_Bold';
  background: linear-gradient(87.32deg, #E2A300 4.47%, #E29500 95.53%);
  box-shadow: 0px 2px 13px rgba(226, 158, 0, 0.48);
  padding: 14px 38px;
  transition: 500ms;
  border-radius: 6px;
  font-weight: 700;
  font-size: 18px;
  color: black;
  margin-bottom: 142px;
  border: none;
}

.header__btn:hover {
  color: #fff;
  transform: translate(7px, 5%);
  transition: 500ms;
}

.header__right {
  position: relative;
}

.header__text {
  font-family: 'ArodoraPro_Light';
  font-weight: 300;
  font-size: 18px;
  width: 400px;
  margin: 1em 0 3em 0;
}

.header__title span {
  font-weight: 600;
  font-size: 48px;
}

.about__card {
  background: #2C2C2C;
  border-radius: 14px;
}

.about__txt {
  width: 370px;
  text-align: center;
  padding: 63px;
}

/* --=-=--=-=-=-=-=- Nav Start =--=--==--=-=-=-=-= */

.nav {
  display: flex;
  justify-content: space-between;
  font-family: 'ArodoraPro_Light';
}

.nav_logo {
  position: relative;
  background: #fff;
}

.nav_logo-img {
  width: 100%;
  position: absolute;
  height: 100%;
}

.nav_list {
  display: flex;
  column-gap: 145px;
  margin-top: 40px;
  transition: 100ms;
  position: relative;
}

.nav_item {
  display: flex;
  justify-content: center;
  position: relative;
}

.nav_item:hover::after {
  width: 100%;
}

.nav_item::after {
  content: '';
  position: absolute;
  width: 0;
  height: 2px;
  background: orange;
  transition: 500ms;
  bottom: 0;
}
</style>
