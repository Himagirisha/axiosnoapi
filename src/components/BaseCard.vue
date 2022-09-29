<template>
  <div class="mobileCard">
    <h2>{{mobileName}}</h2>
    <p>{{rating}}</p>
    <h3>RS:{{mobilePrice}}</h3>
  </div>
</template>

<script>
export default {
    props:["mobileName","rating","review","mobile"]
}
</script>

<style>
.mobileCard{
    display: flex;
    flex-direction: column;
    border: 1px solid grey;
    border-radius: 10px;
    color: white;
    background-color: blue;
}
</style>