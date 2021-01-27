<template>
  <div class="profile">
    <!-- <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-lg-6">
                <div class="media text-left">
                  <img src="../assets/user.png" class="user-pic mr-3" >
                  <div class="media-body">
                    <h5 class="mt-0">{{ firstName }} {{ lastName }}</h5>
                    <p>{{ biodata }}</p>
                  </div>
                </div>
            </div>
        </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
// Import Film Bootstrap.css
import 'bootstrap/dist/css/bootstrap.css'

export default {
  name: 'Profile',
  data : function() {
    return {
      firstName : 'Rizki',
      lastName : 'Wahyudi',
      biodata : 'Will you do the same for me? It\'s time to face the music I\'m no longer your muse.'
    }
  },
  components: {
    // HelloWorld
  }
}
</script>

<style scoped>
.user-pic {
  border-radius: 200%;
  height: 80px;
  width: 80px;
}
</style>