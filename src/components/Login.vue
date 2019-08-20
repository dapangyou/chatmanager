<template>
      <div class="login">
        <div class="content">
          请你吃辣条,告诉我你的名字
        </div>
        <div>
          <input class="inputName"/>
        </div>
      </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style scoped>
  .login {
    background-color: pink;
    width: 100%;
    height: 680px;
    display: flex;
    top: 0;
    justify-content: center;
    margin: 0;
    padding: 0;
  }
  .inputName {
    justify-content: center;
    display: flex;
    width: 200px;
    height: 30px;
    outline: none;
  }
  .content {
    font-size: 50px;
    align-content: center;
    line-height: 680px;
    color: white;
  }

</style>
