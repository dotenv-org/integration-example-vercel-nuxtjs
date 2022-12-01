<template>
  <div>
    <NuxtWelcome />
  </div>
</template>
<script>
import dotenv from 'dotenv-vault-core'
dotenv.config()
console.log(process.env)
</script>
