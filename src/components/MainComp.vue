<template>
  <main>
      <div class="container">
          Content Goes Here!
      </div>
  </main>
</template>

<script>
export default {
    name: 'MainComp',

}
</script>

<style lang="scss" scoped>

    main{
        background-color: #1C1C1C;
        height: 100px; // HERE TO CHANGE MAIN DIMENSIONS
        width: 100%;
        div{
            color: white;
            line-height: 100px; // WHILE CHANGING MAIN DIMENSIONS DISCARD THIS LINE
            font-size: 2rem;
        }
    }

</style>