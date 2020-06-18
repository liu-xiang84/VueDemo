<template>
<div>
<div>Login</div>
<button type="button" @click="reg()">新闻列表</button>
<button type="button">登录</button>
</div>
</template>

<script>
export default {
  name: 'Login',
  methods: {
    reg () {
      this.$router.push('/home/list')
    }
  }
}
</script>
