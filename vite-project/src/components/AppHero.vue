<script>
export default {
  data() {
    return {
      message: `Titolo centrale`,
    }
  }

}
</script>

<template>
    <div class="container">
        <h2 class="col sub-title">
            {{ message }}
        </h2>
    </div>
</template>

<style>

.container{
    height: 100%;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    align-content: center;
    background-image: url(/public/jumbo.png);
}

.sub-title{
 font-size: 48px;
 color: white;
}

</style>