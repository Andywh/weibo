<template>
  <div class="login-wrapper">
    <login-logo></login-logo>
    <login-input></login-input>
    <login-button></login-button>
    <login-account></login-account>
    <login-footer></login-footer>
  </div>
</template>

<script>
import LoginInput from './components/Input'
import LoginLogo from './components/Logo'
import LoginButton from './components/Button'
import LoginAccount from './components/Account'
import LoginFooter from './components/Footer'

export default {
  name: 'Home',
  components: {
    LoginInput,
    LoginLogo,
    LoginButton,
    LoginAccount,
    LoginFooter
  }
}
</script>

<style lang="stylus" scoped>
  .login-wrapper
    /* background: #f6f6f6 */
    /* background-color: blue */
</style>
