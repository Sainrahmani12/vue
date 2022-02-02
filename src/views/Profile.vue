<template>
  <div class="profile">
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-lg-8">
          <div class="d-flex">
            <div class="flex-shrink-0">
              <img src="../assets/earth.webp" class="user-pic mr-3"/>
            </div>
            <div class="flex-grow-1 ms-3">
              <h5>{{ lastname }} {{ firstname }} {{ tmbhn }} </h5>
              {{ isi }}
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import "bootstrap/dist/css/bootstrap.css";

export default {
  name: "profile",
  data: function() {
    return {
      firstname: "Husain",
      lastname: "Rahmani",
      tmbhn: "El-Hamidy",
      isi : "Barakallahu lakuma , wajama'a baynakuma bilkhair."
    }
  },
  components: {},
};
</script>

<style scoped>
.user-pic{
  border-radius: 200%;
  height: 120px;
  width: 120px;
}
</style>
