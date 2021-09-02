<template>
  <div class="contact">
    <div class="container">
      <h1 class="display-2">Contact Us</h1>
      <form>
        <!-- Name input -->
        <div class="form-outline mb-4">
          <input type="text" id="form4Example1" class="form-control" />
          <label class="form-label" for="form4Example1">Name</label>
        </div>

        <!-- Email input -->
        <div class="form-outline mb-4">
          <input type="email" id="form4Example2" class="form-control" />
          <label class="form-label" for="form4Example2">Email address</label>
        </div>

        <!-- Message input -->
        <div class="form-outline mb-4">
          <textarea class="form-control" id="form4Example3" rows="4"></textarea>
          <label class="form-label" for="form4Example3">Message</label>
        </div>

        <!-- Submit button -->
        <button type="submit" class="btn btn-dark btn-block mb-4">Send</button>
      </form>
    </div>
  </div>
</template>

<style lang="scss">
.contact {
  margin-top: 130px;
  margin-bottom: 60px;
}

textarea {
  border: 1px solid black !important;
}
</style>
