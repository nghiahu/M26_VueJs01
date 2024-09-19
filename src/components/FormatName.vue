<template>
  <div>
    Họ và tên: {{formatName(userInfo)}}
  </div>
</template>

<script setup>
        function formatName(user){
            return user.firstName + " " + user.lastName
        }
    const userInfo= {
        firstName: "Ngô",
        lastName: "Nghĩa"
    }
    
</script>

<style>

</style>