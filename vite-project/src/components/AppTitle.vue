<script>
export default {
  data() {
    return {
      message: `La mia prima app con Vite!`,
    }
  }

}
</script>

<template>
    <h1 class="title">
       {{ message }} 
    </h1>
</template>

<style>

*{
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

#app{
  height: 100vh;
}

.title{
  color: orange;
  font-size: 50px;
  flex-shrink: 0;
  padding: 24px;
  background-color: rgb(37, 94, 233);
}

.d-flex{
  display: flex;
  flex-direction: column;
  height: 100%;
}

</style>
