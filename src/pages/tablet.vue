<template>
  <div class="wrapper">
    <div class="hero">
      <header>
        <span class="menu-and-title">
          <q-btn
            flat
            dense
            round
            icon="menu"
            aria-label="Menu"
            @click="leftDrawerOpen = !leftDrawerOpen"
          />
          <span class="brand-name">Crypto.</span>
        </span>
        <button class="get-started">Get Started</button>
      </header>
      <main>
        <img src="~assets/clip-payment1.svg" alt="User payment">
        <div class="hero-title-wrapper">
          <div class="hero-title1">
            Trusted by
          </div>
          <div class="hero-title2">
            over 1 million
          </div>
          <div class="hero-title3">
            users
          </div>
          <div class="hero-description">
            <p>
              Manage your cryptocurrency with ease — our rates are the lowest in the industry to buy, sell and manage all in 1 place. The easiest platform to convert crypto holdings to cash.
            </p>
          </div>
        </div>
      </main>
    </div>
    <div class="video-demo--block">
      <div class="title">As powerful or as simple as you need it be</div>
      <p class="description">Customise your mobile and desktop apps to show as much data as <br> you need to make the best fininacial <br> investments. Ease of use has been baked in from day 1.</p>
      <div class="img">
        <img src="~assets/screen-demo.svg" alt="Demo video" class="video-demo">
      </div>
    </div>
    <hr>
    <div class="testimonial">
      <img src="~assets/rick-image.svg" alt="A guy called Rick" class="rick-image">
      <div class="testimony-wrapper">
        <div class="title">How Rick used <span class="brand-name">Crypto</span> to <br> manage and grow his <br> portofolio by 1200%</div>
        <div class="subtitle">Ricks Story</div>
        <div class="rick-story">
          <p>Rick is a lead developer at startup Shackle. Adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
          <p>Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
          <p>Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
        </div>
      </div>
    </div>
    <div class="holdings-performance">
      <div class="title">
        <h4>Ricks top 3 holdings - Daily performance</h4>
        <hr>
      </div>
      <div class="crypto-currencies-wrapper">
        <div class="bitcoin crypto-currency">
          <div class="name">Bitcoin <span class="percentage positive">+8.5</span></div>
          <div class="value">$20,603</div>
        </div>
        <div class="ethereum crypto-currency">
          <div class="name">Ethereum <span class="percentage positive">+2.5</span></div>
          <div class="value">$5,300</div>
        </div>
        <div class="litecoin crypto-currency">
          <div class="name">Litecoin <span class="percentage negative">-.5</span></div>
          <div class="value">$730</div>
        </div>
      </div>
    </div>
    <div class="privacy-and-security">
      <div class="img">
        <img src="~assets/clip-sign-up1.svg" alt="security">
      </div>
      <div class="pas">
        <div class="title">Privacy and security prioritised in from the beginning.</div>
        <p class="description">Our technology is built on top of Cloud7 propriertary - the most trusted platform when it comes to cyber security. NASA, the FBI and Amazon use this very platform so you are in safe hands.</p>
        <div class="final-text">Trusted by 1,000,000+ users</div>
      </div>
    </div>
    <div class="call-to-action">
      <div class="img">
        <img src="~assets/clip-uploading1.svg" alt="Start">
      </div>
      <div class="cta-wrapper">
        <h2>Start building your <br> crypto holdings today!</h2>
        <button>I’m ready to get started</button>
      </div>
    </div>
    <hr>
    <div class="footer">
      <div class="subscription-wrapper">
        <h4>Crypto.</h4>
        <div class="description paragraph">
          Get insider investing and crypto resources straight to your inbox every week.
        </div>
        <div class="subscribe">
          <input type="text" name="" id="" placeholder="Your email here">
          <button>Join</button>
        </div>
      </div>
      <div class="links-wrapper">
        <div class="links">
          <div class="title">Our Products</div>
          <div class="link paragraph">Wallet</div>
          <div class="link paragraph">Investor Booster</div>
          <div class="link paragraph">Referral Earn</div>
          <div class="link paragraph">Venture Fund</div>
          <div class="link paragraph">ETF Merger</div>
        </div>
        <div class="links">
          <div class="title">Why choose Crypo?</div>
          <div class="link paragraph">Crypto vs. Coinbase</div>
          <div class="link paragraph">How we’re different</div>
          <div class="link paragraph">Our Philosophy</div>
          <div class="link paragraph">Critical financial reviews</div>
          <div class="link paragraph">What our customers say</div>
        </div>
        <div class="links">
          <div class="title">Social</div>
          <div class="link paragraph">Twitter</div>
          <div class="link paragraph">Facebook</div>
          <div class="link paragraph">Instagram</div>
          <div class="link paragraph">Facebook</div>
        </div>
      </div>
      <h6>Crypto ©  All rights reserved 2020.</h6>
    </div>
  </div>
</template>

<script>
export default {
  name: 'PageIndex'
}
</script>
<style lang="scss" scoped>
// $brand-blue: #0032E3;
// $blue-shade: #7C93E5;
// $text-black: #000000;
// $paragraph: #6D6D6D;
.paragraph {
  color: $paragraph;
  font-size: 16px;
  line-height: 24px;
  letter-spacing: -2%;
}

.footer {
  margin: 0 25px 0 25px;

  .subscription-wrapper {
    width: 60%;
    h4 {
      margin-top: 48px;
      margin-bottom: 12px;
      font-size: 24px;
      font-weight: bolder;
      line-height: auto;
      letter-spacing: -2%;
    }
    .subscribe {
      margin-top: 30px;
      input {
        height: 61px;
        margin-left: 2px;
        width:90%;
        margin-right: -90px;
        color: #000000;
        font-size: 18px;
        line-height: auto;
        letter-spacing: -2%;
      }
      input::placeholder {
        color: #000000;
        font-size: 18px;
        line-height: auto;
        letter-spacing: -2%;
      }
      button {
        border: none;
        padding-top: 3px;
        padding-bottom: 3px;
        width: 94px;
        height: 61px;
        border-radius: 10px;
        background-color: $brand-blue;
        color: #FFFFFF;
        font-size: 18px;
        line-height: auto;
        letter-spacing: -2%;
      }
    }
  }
  .links-wrapper {
    display: flex;
    justify-content: space-between;
    .links {
      margin-top: 47px;
      .title {
        color: #000000;
        font-weight: bolder;
        font-size: 16px;
        line-height: 222%;
        letter-spacing: -2%;
      }
    }
  }

  h6 {
    font-size: 14px;
    line-height: 132.6%;
    letter-spacing: -2%;
    margin-bottom: 30px;
  }
}
.call-to-action {
  display: grid;
  grid-template-columns: 50% 50%;
  margin: 0 25px 30px 25px;
  .img {
    text-align: center;
  }
  h2 {
    text-align: left;
    font-weight: bolder;
    font-size: 24px;
    line-height: 125%;
    letter-spacing: -2%;
    margin-top: 61px;
    margin-bottom: 0;
  }
  button {
    margin-top: 37px;
    width: 100%;
    height: 61px;
    background-color: $brand-blue;
    border-radius: 10px;
    color: #FFFFFF;
    border: 1px #FFFFFF solid;
    font-weight: bold;
    font-size: 18px;
  }
}
.privacy-and-security {
  display: grid;
  grid-template-columns: 50% 50%;
  background-color: #E8EEF8;
  padding-right: 25px;
  padding-left: 25px;

  .img {
    padding-top: 10px;
    text-align: center;
  }
  .pas {
    display:flex;
    flex-direction: column;
    justify-content: center;
    .title {
      font-size: 20px;
      line-height: 27px;
      letter-spacing: -2%;
      font-weight: bolder;
    }
    .description {
      margin-top: 15px;
      color: $paragraph;
      font-size: 16px;
      line-height: 24px;
      letter-spacing: -2%;
    }
    .final-text {
      font-weight: bold;
      line-height: 114.6%;
      letter-spacing: -2%;
      font-size: 15px;
    }
  }
}
.holdings-performance {
  margin: 0 25px 0 25px;
  .crypto-currencies-wrapper {
    display: flex;
    justify-content: space-evenly;
  }
  .title {
    h4 {
      font-size: 15px;
      font-weight: bold;
      text-align: left;
      line-height: auto;
      letter-spacing: -2%;
      margin-bottom: 1px;
      padding-bottom: 1px;
    }
    hr {
      margin-top: 0;
      margin-bottom: 50px;
    }
  }
  .crypto-currency {
    .name {
      color: #000000;
      font-size: 25px;
      letter-spacing: -2%;
      line-height: auto;
      font-weight: bolder;
      .percentage {
        text-align: center;
        padding-left: 3px;
        padding-right: 3px;
        font-size: 14px;
        letter-spacing: -2%;
        line-height: auto;
        border-radius: 2px;
      }
      .negative {
        border: 1px #E5442E solid;
        color: #E5442E;
      }
      .positive {
        color: #6FA52B;
        border: 1px #6FA52B solid;
      }
    }
    .value {
      color: $paragraph;
      font-size: 21px;
      line-height: 148%;
      letter-spacing: -2%;
      margin-bottom: 54px;
    }
  }
}
hr {
  border: 1px solid #E0DADA ;
}
.testimonial {
  display: grid;
  grid-template-columns: 50% 50%;
  text-align: left;
  margin:46px 25px 0 25px;
  img {
    margin: 0 0 34px -6px;
  }
  .testimony-wrapper {
    .title {
      font-weight: bolder;
      font-size: 24px;
      line-height: 125%;
      letter-spacing: -2%;

      .brand-name {
        color: #3159E8;
      }
    }
    .subtitle {
      font-size: 21px;
      line-height: 132.6%;
      letter-spacing: -2%;
      margin: 32px 0 10px 0 ;
    }
    .rick-story {
      color: $paragraph;
      font-size: 16px;
      letter-spacing: -2%;
      line-height: 24px;
    }
  }
}
.video-demo--block {
  display: flex;
  flex-direction: column;
  text-align: center;

  .title {
    font-size: 24px;
    font-weight: bolder;
    margin: 50px 0 20px 0;
  }
  .description {
    color: $paragraph;
    text-align: center;
    font-size: 16px;
    line-height: 24px;
    letter-spacing: -2%;
    margin: 0 0 55px 0;
  }
  .img {
    text-align: center;
    img {
      width: 80%;
    }
  }
}
.hero {
  background-color: $brand-blue;
  color: #FFFFFF;

  header {
    margin: 0 20px 0 20px;
    padding: 20px 0 0 0;
    display: flex;
    align-items: center;
    justify-content: space-between;
    .menu-and-title {
      display: flex;
      .brand-name {
        font-size: 28px;
        margin: 0;
        padding: 0;
        font-weight: bold;
      }
    }
    .get-started {
      position: absolute;
      right: 25px;
      border-radius: 10px;
      background-color: unset;
      color: #FFFFFF;
      border: 1px solid #FFFFFF;
      width: 106px;
      height: 45px;
      font-size: 14px;
    }
  }

  main {
    display: grid;
    grid-template-columns: 45% 55%;
    margin-top: 20px;

    img {
      order: 2;
      width: 100%;
      margin: -10px 0 -20px 0;
    }
    .hero-title-wrapper {

      display: flex;
      flex-direction: column;
    }
    .hero-title1, .hero-title2, .hero-title3 {
      text-align: left;
      font-size: 47px;
      font-weight: bold;
      margin: -10px 0 -10px 25px;
    }

    .hero-description{
      margin: 30px 25px 0 25px;
      font-size: 16px;
      line-height: 24px;
      letter-spacing: -2%;
    }
  }
}
</style>
