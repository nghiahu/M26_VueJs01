<template>
  <div class="border">
    <div class="img">Image</div>
    <div class="title">
        <div class="tia">Title</div>
        <button class="btn">App to cart</button>
    </div>
  </div>
</template>

<script>

</script>

<style scope>
.border{
    border: 1px solid black;
    width: 220px;
    height: 270px;
    border-radius: 5%;
}
.img{
    background-color: gray;
    height: 50%;
    border-top-left-radius: 5%;
    border-top-right-radius: 5%;
    display: grid;
    place-content: center;
}
.title{
    display: flex;
    flex-direction: column;
    justify-content: center;
    padding-top: 10px;
    gap: 50px;
}
.tia{
    display: flex;
    justify-content:center;
}
.btn{
    margin: 10px;
    height: 30px;
}
</style>