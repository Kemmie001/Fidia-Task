<template>
  <div class="">
    <div class="main_container">

      <div class="grid grid-cols-4 gap-x-10">
        <div class="col-span-1 w-3/4">
          <div class="right-asset flex justify-center">
            <div class="side-line">
            </div>
          </div>

        </div>

        <div class="col-span-2 lg:w-3/4 mx-auto">
          <div class=" stripe-logo">
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
              <div class="relative">
                <input type="password" class="form-input py-4">
                <svg class="password-eye" width="16" height="17" viewBox="0 0 16 17" fill="none"
                  xmlns="http://www.w3.org/2000/svg">
                  <path fill-rule="evenodd" clip-rule="evenodd"
                    d="M8 14.968C3.582 14.968 0 10.282 0 8.96802C0 7.65402 3.582 2.96802 8 2.96802C12.418 2.96802 16 7.65402 16 8.96802C16 10.282 12.418 14.968 8 14.968ZM8 12.968C9.06087 12.968 10.0783 12.5466 10.8284 11.7964C11.5786 11.0463 12 10.0289 12 8.96802C12 7.90715 11.5786 6.88974 10.8284 6.13959C10.0783 5.38944 9.06087 4.96802 8 4.96802C6.93913 4.96802 5.92172 5.38944 5.17157 6.13959C4.42143 6.88974 4 7.90715 4 8.96802C4 10.0289 4.42143 11.0463 5.17157 11.7964C5.92172 12.5466 6.93913 12.968 8 12.968ZM8 10.968C7.46957 10.968 6.96086 10.7573 6.58579 10.3822C6.21071 10.0072 6 9.49845 6 8.96802C6 8.43758 6.21071 7.92888 6.58579 7.5538C6.96086 7.17873 7.46957 6.96802 8 6.96802C8.53043 6.96802 9.03914 7.17873 9.41421 7.5538C9.78929 7.92888 10 8.43758 10 8.96802C10 9.49845 9.78929 10.0072 9.41421 10.3822C9.03914 10.7573 8.53043 10.968 8 10.968Z"
                    fill="#A3ACB9" />
                </svg>
              </div>


              <br>
              <div class="pt-4">
                <input type="checkbox" class="checkbox-input" name="" id="">
                Stay signed in for a week
              </div>
              <nuxtLink to="/dashboard">
                <button class="form_button">
                  Continue
                </button>
              </nuxtLink>
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

        <div class="col-span-1 w-3/4 ml-auto">
          <div class="left-asset flex justify-center">
            <div class="side-line">
            </div>
          </div>
        </div>

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
    height: 100vh;
  }


  .right-asset {
    background: linear-gradient(172deg, #F7FAFC 60%, #0c00fa80 5% 65%, #ffffff 65%);
    height: 100vh;
  }


  .side-line {
    opacity: 0.7;
    width: 1px;
    height: 100vh;
    background-color: #E3E8EE;
  }

  .stripe-logo {
    margin: 2.5rem;
  }

  .form-card {
    background: #FFFFFF;
    box-shadow: 0px 5px 15px rgba(0, 0, 0, 0.12), 0px 15px 35px rgba(60, 66, 87, 0.08);
    border-radius: 4px;
    margin: 0 auto;
    height: 537px;
    padding: 42px 68px 72px;
    color: #3C4257;
  }


  @media screen and (max-width: 765px) {
    .form-card {
      background: #FFFFFF;
      box-shadow: 0px 5px 15px rgba(0, 0, 0, 0.12), 0px 15px 35px rgba(60, 66, 87, 0.08);
      border-radius: 4px;
      margin: 0 auto;
      width: 100%;
      height: 537px;
      padding: 18px 38px 42px;
      color: #3C4257;
    }
  }

  .colored-link {
    color: #635CFF;
    font-size: 14px;
    cursor: s;
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
    outline: none;
  }

  .form-input::placeholder {
    color: #3C4257;
  }

  .password-eye {
    position: absolute;
    top: 35%;
    left: 90%;
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