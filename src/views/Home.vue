<template>
  <div class="home">
    <div class="top-intro">
      <img class="intrologo" alt="Vue logo" src="../assets/dadlogo.png" />
      <h1 class="display-3">Helping Fathers In Need</h1>
      <a href="#" class="btn btn-dark btn-lg">MORE INFO</a>
    </div>
    <br /><br /><br />
    <HelloWorld msg="Welcome to Your Supportive Community of Fatherhood" />
    <br /><br />
    <div class="container mt-3 text-center">
      <h1>Subscribe To Fathers & Coffee</h1>
      <form style="width: 90%; margin-left: auto; margin-right: auto">
        <!-- Name input -->
        <div class="form-outline mb-4">
          <input type="text" id="form5Example1" class="form-control" />
          <label class="form-label" for="form5Example1">Name</label>
        </div>

        <!-- Email input -->
        <div class="form-outline mb-4">
          <input type="email" id="form5Example2" class="form-control" />
          <label class="form-label" for="form5Example2">Email address</label>
        </div>

        <!-- Checkbox -->
        <div class="form-check d-flex justify-content-center mb-4">
          <input
            class="form-check-input me-2"
            type="checkbox"
            value=""
            id="form5Example3"
            unchecked
          />
          <label class="form-check-label" for="form5Example3">
            I have read and agree to the terms
          </label>
        </div>

        <!-- Submit button -->
        <button type="submit" class="btn btn-dark btn-block mb-4">
          Subscribe
        </button>
      </form>
    </div>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
import HelloWorld from "@/components/HelloWorld.vue"; // @ is an alias to /src

@Options({
  components: {
    HelloWorld,
  },
})
export default class Home extends Vue {}
</script>

<style lang="scss">
.home {
  margin-top: 40px;
}
input {
  border: 1px solid black !important;
}
</style>
