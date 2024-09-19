<template>
  <div>
    <h2>Danh sách kết quả</h2>
    <ul>
        <li>{{x}} + {{y}} = {{sum}}</li>
        <li>{{x}} - {{y}} = {{sub}}</li>
        <li>{{x}} * {{y}} = {{mul}}</li>
        <li>{{x}} / {{y}} = {{div}}</li>
    </ul>
  </div>
</template>

<script setup>
    const x = 10;
    const y = 10;
    const sum = x + y
    const sub = x - y
    const mul = x * y
    const div = x/y
    console.log(sum);
    
</script>

<style>

</style>