<template>
  <v-container fluid>
    <v-layout row wrap align-center justify-center column fill-height>
    <v-flex>
      <div
        id="component-profile"
        class="d-flex flex-column justify-center align-center">
        <img src="~assets/img/me.jpeg" />
        <h1>{{ name }}</h1>
        <p>{{ description }}</p>
        <p>HP : {{ pheneNumber }}</p>
        <div class="d-flex icons-wrapper">
          <a
            href="https://github.com/kimbyungsoo"
            target="_blank"
            title="Github"
            ><i class="fab fa-github mx-2"></i
          ></a>
          <a
            href="https://www.instagram.com/zzzkbs/"
            target="_blank"
            title="Instagram"
            ><i class="fab fa-instagram mx-2"></i
          ></a>
          <a href="mailto:xfo5712@naver.com" target="_blank" title="mail"
            ><i class="far fa-envelope mx-2"></i
          ></a>
        </div>
      </div>
    </v-flex>
    </v-layout>
  </v-container>
</template>

<script>
export default {
  data() {
    return {
      name: "Kim Byung Soo",
      description: "Full stack web developer.",
      pheneNumber: "010-9639-5712",
    };
  },
};
</script>

<style scoped lang="scss">
#component-profile {
  margin-top: 50%;
  img {
    max-height: 200px;
    border-radius: 200px;
  }
  i {
    font-size: 44px;
    color: ivory;
  }
  p {
    margin-bottom: 0px;
  }
  .icons-wrapper {
    margin-top: 16px;
  }
}
</style>