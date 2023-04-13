<template>
  <div class="login-content">
    <div>
      <h1>Log in to your account</h1>
    </div>
    <div class="login-form">
      <div class="login-form-email">
        <input class="email" type="text" placeholder="Email address">
        <img class="email-icon" src='@/assets/email.svg' alt="">
      </div>
      <div class="login-form-password">
        <input class="password" type="password" placeholder="Password">
        <img class="password-icon" src="@/assets/email.svg" alt="">
      </div>
      <div>
        <button>Login</button>
      </div>
      <div class="sign-up-text">
        <p>Don't have account? <a href="">Sign up</a></p>
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: "view-login"
}

</script>

<style>
.login-content {
  margin-left: auto;
  margin-right: auto;
  width: 794px;
  height: 506px;
  top: 131px;

  background: #FFFFFF;
  box-shadow: 0px 4px 45px rgba(0, 0, 0, 0.12);
  border-radius: 10px;

  display: flex;
  align-items: center;
  flex-direction: column;
}

.login-content h1 {
  padding: 50, 206;
  font-family: 'Montserrat';
  font-style: normal;
  font-weight: 600;
  font-size: 33px;
  line-height: 40px;
}

.login-form {
  margin-top: 22px;
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 30px;
}

.login-form input {
  width: 496px;
  height: 45px;
  opacity: 0.5;
  border: 1px solid #000000;
  border-radius: 10px;
  font-family: 'Montserrat';
  font-style: normal;
  font-weight: 600;
  font-size: 16px;
  line-height: 20px;
  color: #2A1E17;
  opacity: 0.5;
  outline: none;
  padding-left: 47px;
}

.login-form button {
  width: 543px;
  height: 45px;
  background: #FF4C4A;
  border-radius: 100px;
  color: #FFFFFF;
  font-family: 'Montserrat';
  font-style: normal;
  font-weight: 600;
  font-size: 16px;
  line-height: 20px;
  border: none;
  cursor: pointer;
}

.login-form-email {
  position: relative;
}

.email-icon {
  position: absolute;
  top: 17px;
  left: 24px;
}

.login-form-password {
  position: relative;
}

.password-icon {
  position: absolute;
  top: 17px;
  left: 24px;
}

.sign-up-text > p > a {
  text-decoration: none;
  color: #FF4C4A;
}
</style>