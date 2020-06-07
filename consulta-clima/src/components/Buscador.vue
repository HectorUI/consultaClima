<template>
  <div>
    <div
      class="jumbotron"
      style="margin-bottom:0px; 
    color:white; background-color: #4aa1f3"
    >
      <h2 class="text-center" style="font-size:50px; font-weight:600;"
        >Get Current Weather</h2
      >
    </div>
    <div class="container">
      <div class="row" style="margin-bottom:20px;">
        <h3 class="text-center text-primary">Enter City Name</h3>
      </div>
      <div class="row form-group form-inline" id="rowDiv">
        <input
          type="text"
          name="city"
          id="city"
          class="form-control"
          placeholder="Ciudad Origen"
        />
        <button id="submitWeather" class="btn btn-primary">Search city</button>
      </div>
      <div id="show"></div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Buscador",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#rowDiv {
  margin: auto;
  text-align: center;
  width: 100%;
}
input[type="text"] {
  height: 40px;
  font-size: 20px;
}

#submitWeather {
  height: 40px;
  font-size: 20px;
  font-weight: bold;
}
</style>
