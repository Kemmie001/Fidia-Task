<template>
  <div class="">
    <div class="main_container">
      <div class="flex justify-between">
        <div class="right-asset">
        </div>
        <div class="">
          <div class="stripe-logo">
            <svg width="58" height="24" viewBox="0 0 58 24" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path fill-rule="evenodd" clip-rule="evenodd"
                d="M57.6 12.384C57.6 12.768 57.568 13.6 57.568 13.808H49.744C49.92 15.696 51.296 16.24 52.848 16.24C54.432 16.24 55.68 15.904 56.768 15.36V18.56C55.68 19.168 54.24 19.6 52.336 19.6C48.432 19.6 45.712 17.168 45.712 12.352C45.712 8.288 48.016 5.056 51.824 5.056C55.616 5.056 57.6 8.288 57.6 12.384ZM49.696 10.864H53.824C53.824 9.056 52.784 8.304 51.808 8.304C50.8 8.304 49.696 9.056 49.696 10.864ZM39.536 5.056C42.336 5.056 44.976 7.584 44.992 12.224C44.992 17.296 42.384 19.6 39.52 19.6C38.112 19.6 37.264 19.008 36.688 18.592L36.672 23.12L32.672 23.968V5.312H36.192L36.4 6.304C36.96 5.792 37.968 5.056 39.536 5.056ZM38.576 16.08C40.048 16.08 41.04 14.48 41.04 12.336C41.04 10.24 40.032 8.608 38.576 8.608C37.664 8.608 37.088 8.928 36.672 9.392L36.688 15.328C37.072 15.744 37.632 16.08 38.576 16.08ZM27.168 4.112V0.848L31.184 0V3.248L27.168 4.112ZM27.168 5.328H31.184V19.328H27.168V5.328ZM22.864 6.512C23.808 4.784 25.68 5.136 26.192 5.328V9.008C25.696 8.832 24.096 8.608 23.152 9.84V19.328H19.152V5.328H22.608L22.864 6.512ZM14.864 1.856L14.848 5.328H17.888V8.736H14.848V14.416C14.848 16.784 17.376 16.048 17.888 15.84V19.088C17.36 19.376 16.4 19.616 15.088 19.616C12.72 19.616 10.944 17.872 10.944 15.504L10.96 2.688L14.864 1.856ZM4.048 9.392C4.048 11.184 10.144 10.336 10.16 15.104C10.16 17.968 7.872 19.616 4.544 19.616C3.168 19.616 1.664 19.344 0.176 18.704V14.896C1.52 15.632 3.216 16.176 4.544 16.176C5.44 16.176 6.08 15.936 6.08 15.2C6.08 13.296 0 14 0 9.584C0 6.752 2.16 5.056 5.408 5.056C6.736 5.056 8.048 5.264 9.376 5.792V9.552C8.16 8.896 6.624 8.528 5.408 8.528C4.56 8.528 4.048 8.768 4.048 9.392Z"
                fill="black" />
            </svg>
          </div>
          <main class="form-card">
            <h1 class="form-title">Sign in to your account</h1>
            <form action="" class="">
              <label for="email" class="my-4">Email</label><br>
              <input type="email" placeholder="jane.doe@gmail.com" class="form-input"><br>
              <span class="flex justify-between pt-6">
                <h1 class="">Password</h1>
                <a class="colored-link">Forgot your password?</a>
              </span>
              <input type="password" class="form-input py-4"><br>
              <div class="pt-4">
                <input type="checkbox" class="checkbox-input" name="" id="">
                Stay signed in for a week
              </div>
              <button class="form_button">
                Continue
              </button>
              <div class="text-center">
                <a href="#" class="colored-link">Use single sign on (SSO) instead</a>
              </div>
            </form>
          </main>

          <div class="stripe-logo">
            Don’t have an account? <a href="#" class="colored-link text-sm">Sign up</a>
            <ul class="flex pt-4">
              <li class="">© Stripe</li>
              <li class="px-2">. &nbsp; Contact</li>
              <li class="">. Privacy & terms</li>
            </ul>
          </div>
        </div>
        <div class="left-asset">
        </div>
      </div>
      <div class="side-line right-line">
      </div>
      <div class="side-line left-line">
      </div>
    </div>
  </div>
</template>

<script>
  export default {}
</script>

<style>
  .main_container {
    height: 100vh;
    width: 100%;
    position: relative;
    overflow: hidden;
    background: linear-gradient(172deg, #F7FAFC 50%, #ffffff 50%);
    font-family: "SF Pro Regular";
  }

  .left-asset {
    background: linear-gradient(172deg, #F7FAFC 35%, #0c00fa80 5% 40%, #ffffff 40%);
    width: 314px;
    height: 100vh;
  }


  .right-asset {
    background: linear-gradient(172deg, #F7FAFC 60%, #0c00fa80 5% 65%, #ffffff 65%);
    width: 314px;
    height: 100vh;
    z-index: 3;
    position: relative;
  }

  .right-asset::after {
    background: linear-gradient(172deg, #F7FAFC 60%, #81E9FF 5% 65%, #ffffff 65%);
    width: 214px;
    height: 100vh;
    opacity: 0.4;
    z-index: 10;
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
  }

  .side-line {
    position: fixed;
    right: 0;
    top: 0%;
    bottom: 0%;
    opacity: 0.7;
    border: 1px solid #E3E8EE;
  }

  .left-line {
    left: 87.5%;
  }

  .right-line {
    left: 12.5%;
  }

  .stripe-logo {
    margin: 2.5rem;
  }

  .form-card {
    background: #FFFFFF;
    box-shadow: 0px 5px 15px rgba(0, 0, 0, 0.12), 0px 15px 35px rgba(60, 66, 87, 0.08);
    border-radius: 4px;
    margin: 0 auto;
    position: static;
    width: 542px;
    height: 537px;
    padding: 48px 68px 72px;
    color: #3C4257;
    z-index: 5;
  }


  @media screen and (max-width: 765px) {
    .form-card {
      background: #FFFFFF;
      box-shadow: 0px 5px 15px rgba(0, 0, 0, 0.12), 0px 15px 35px rgba(60, 66, 87, 0.08);
      border-radius: 4px;
      margin: 0 auto;
      position: static;
      width: 90%;
      height: 537px;
      padding: 18px 38px 42px;
      color: #3C4257;
      z-index: 5;
    }
  }

  .colored-link {
    color: #635CFF;
    font-size: 14px;
  }

  .form-title {
    font-size: 24px;
    font-weight: 600;
    margin-bottom: 1rem;
  }

  .form-input {
    border: 1px solid #F7FAFC;
    padding: 4px 10px;
    margin-top: 0.5rem;
    border-radius: 5px;
    width: 100%;
  }

  .form-input::placeholder {
    color: #3C4257;
  }

  .checkbox-input {
    border: 1px solid #F7FAFC;
  }

  .form_button {
    background-color: #635CFF;
    border-radius: 5px;
    padding: 13.5px 0;
    text-align: center;
    color: #FFFFFF;
    width: 100%;
    margin-top: 28px;
    margin-bottom: 28px;
  }
</style>