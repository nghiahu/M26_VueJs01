<template>
  <div>
    <h2>Thông tin cá nhân</h2>
    <ul>
        <li>Họ tên: {{user.name}}</li>
        <li>Giới tính: {{user.gender}}</li>
        <li>Ngày sinh: {{user.birthday}}</li>
        <li>Email: {{user.email}}</li>
        <li>Địa chỉ: {{user.address}}</li>
    </ul>
  </div>
</template>

<script setup>
    const user={
        name:"Ngô Hữu nghĩa",
        gender:"Nam",
        birthday:"12/04/2005",
        email:"naf@gmail.com",
        address:"Hải Phòng"
    }
</script>

<style>

</style>