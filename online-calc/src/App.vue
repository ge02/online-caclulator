<script>

</script>

<template>
<body>
  <h1 id="title">Online Calculator</h1>




</body>

  <div class="game-board">
    <div class="box">200px x 200px</div>
    <div class="box">200px x 200px</div>
    <div class="box">200px x 200px</div>
    <div class="box">200px x 200px</div>
    <div class="box">200px x 200px</div>
    <div class="box">200px x 200px</div>
    <div class="box">200px x 200px</div>
    <div class="box">200px x 200px</div>
    <div class="box">200px x 200px</div>
  </div>

</template>

<style>
#title {
  margin: auto;
  width: 40%;
  padding: 10px;
}

.game-board {
  display: grid;
  grid-template-rows: 200px 200px 200px;
  grid-template-columns: 200px 200px 200px;
}

// for some css stylings
body {
  display: flex;
  justify-content: center;
}
.box {
  background: #444;
  border: 1px solid #555;
  display: flex;
  align-items: center;
  justify-content: center;
  color: #AAA;
}
</style>
