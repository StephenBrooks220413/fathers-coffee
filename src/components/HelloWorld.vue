<template>
  <div class="container mt-5">
    <h1>{{ msg }}</h1>
    <p class="lead">
      For a guide and referrable coaches to help through life,<br />
      check out the
      <a href="#" target="_blank" rel="noopener">consumer documentation</a>.
    </p>
    <div class="row mt-5 mb-5">
      <div
        data-mdb-toggle="animation"
        data-mdb-animation-start="onScroll"
        data-mdb-animation-on-scroll="repeat"
        data-mdb-animation="slide-in-left"
        class="col-md mt-5"
      >
        <i class="fas icon fa-book-open"></i>
        <h2>Open Door Policy</h2>
      </div>
      <div
        data-mdb-toggle="animation"
        data-mdb-animation-start="onScroll"
        data-mdb-animation-on-scroll="repeat"
        data-mdb-animation="slide-in-left"
        class="col-md mt-5"
      >
        <i class="fas icon fa-mug-hot"></i>
        <h2>Quick Time-Out</h2>
      </div>
      <div
        data-mdb-toggle="animation"
        data-mdb-animation-start="onScroll"
        data-mdb-animation-on-scroll="repeat"
        data-mdb-animation="slide-in-left"
        class="col-md mt-5"
      >
        <i class="fas icon fa-comment"></i>
        <h2>Send A Comment</h2>
      </div>
    </div>
    <div class="row mt-3 mb-3">
      <div class="col-md mt-5">
        <img src="../assets/hands.png" class="img-fluid" alt="hands" />
      </div>
      <div class="col-md mt-5">
        <h1>All Hands In</h1>
        <hr />
        <p class="lead">
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquam,
          atque veritatis ipsa inventore ipsum doloribus sit aspernatur
          mollitia, maxime expedita id sapiente aut beatae blanditiis
          repudiandae sed totam molestias! Quis.
        </p>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";

@Options({
  props: {
    msg: String,
  },
})
export default class HelloWorld extends Vue {
  msg!: string;
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
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
