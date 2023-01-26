<template>
  <div>
    <button type="button" class="btn btn-info">Info</button>
    <form>
      <div class="progress">
        <div class="progress-bar"></div>
      </div>
      <div>
        <div class="form-group">
          <label>name</label>
          <input type="text" class="form-control" />
        </div>
      </div>
      <button class="btn btn-primary">Send Data</button>
    </form>
    <div>
      <table class="table table-bordered">
        <tr>
          <td></td>
          <td></td>
        </tr>
      </table>
    </div>
  </div>
</template>

<script>
import "bootstrap-vue/dist/bootstrap-vue.css";
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
