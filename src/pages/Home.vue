<template>
  <div>
    <Navbar />
    <section class="home">
      <div class="image">
        <img src="https://scontent.fbkk12-2.fna.fbcdn.net/v/t1.6435-9/193367731_1217213642049291_6943240487402629998_n.jpg?_nc_cat=104&ccb=1-7&_nc_sid=09cbfe&_nc_ohc=6QJhRZxCOk4AX8wA0CI&_nc_ht=scontent.fbkk12-2.fna&oh=00_AT937o5Kgz5j8bbe2nwwf0rg8u9BOhhLsS0xBaa6Mt1xWg&oe=6368762A" alt="" />
      </div>
      <div class="content">
        <h3>hi, i am {{name}}</h3>
        <span>Belive the Impossible is Possible.</span>
        <p>
          {{motto}}
        </p>
        <p>{{content}}</p>
        <router-link to="/about" class="btn">
          about me <i class="fas fa-user"></i>
        </router-link>
      </div>
    </section>
  </div>
</template>

<script>
import Navbar from "../components/Navbar.vue";
export default {
  components: { Navbar },
  data() {
    return {
      name: "Borirak Dabchimplee",
      motto:"WTF",
      content:"GOT MY HART",
    };
  },
};
</script>

<style>
</style>