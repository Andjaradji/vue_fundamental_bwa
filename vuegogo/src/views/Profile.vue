<template>
  <div class="profile">
      <div class="container">
          <div class="row justify-content-center">
              <div class="col-lg-6">
                  <div class="d-flex text-start">
                    <div class="flex-shrink-0">
                        <img src="../assets/pp.jpeg" class="user-pic" >
                    </div>
                    <div class="flex-grow-1 ms-3">
                      <h3>{{firstName}} {{lastName}}</h3>  
                      This is some content from a media component. You can replace this with any content and adjust it as needed. Lorem ipsum bla
                      bla bla bla. Lorem ipsum lorem ipsum.
                    </div>
                </div>
              </div>
          </div>
      </div>
  </div>
</template>

<script>

import 'bootstrap/dist/css/bootstrap.css'

export default {
  name: 'Profile',
  data: function () {
      return {
          firstName: "Andjaradji ",
          lastName :"Rooseno"
      }
  } ,
  components: {}
}
</script>

<style scoped>
.user-pic{
    border-radius: 200%;
    width: 120px;
    height: 120px;
}
</style>