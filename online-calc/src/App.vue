<script>
 let firstNumber = 1;
 let message = 'Hello';

function getFirstNumber() {
  this.firstNumber = document.getElementById("firstN").value;
  console.log(this.firstNumber);
}


</script>

<template>
  <head>
    <h1 id="title">Online Calculator</h1>
    
  </head>

  <p>{{ message }}</p>

  <div></div>

  <div class="firstN">
    <label>Type in another number <input type="firstNumber" id="n2" value="5"></label>    
  </div>

  <div></div>

  <div class="secondN">
    <label>Type in another number <input type="numbers" id="n2"></label>
  </div>

  <div></div>

  <div class="formal">
    <button onclick="getFirstNumber()">Get First Number</button>
  </div>

  <p>{{ firstNumber }}</p>
</template>

<style>
#title {
  margin: auto;
  width: 100%;
  padding: 10px;
}

label {
  display: flex;
  flex-direction: row;
  justify-content: flex-end;
  text-align: right;
  width: 400px;
  line-height: 26px;
  margin-bottom: 10px;
}

input {
  height: 20px;
  flex: 0 0 200px;
  margin-left: 10px;
}
</style>
