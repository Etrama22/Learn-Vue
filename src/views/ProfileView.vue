<template>
  <div class="profile">
    <div class="container">
      <div class="row">
        <div class="col-12 d-flex justify-content-center">
          <div class="d-flex align-items-center">
            <div class="flex-shrink-0">
              <img
                class="user-pic rounded-circle"
                src="../assets/profile.jpeg"
                alt="..."
              />
            </div>
            <div class="flex-grow-1 ms-3 text-start">
              <h5 class="mt-0">Muhammad Azis Etrama</h5>
              This is some content from a media component. You can replace this
              with any content and adjust it as needed.
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import "bootstrap/dist/css/bootstrap.css";
// @ is an alias to /src

export default {
  name: "HomeView",
  components: {},
};
</script>

<style scoped>
.user-pic {
  width: 80px;
  height: 80px;
}
</style>
