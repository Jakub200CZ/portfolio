<template>
  <div class="bgG text-lg">
    <profile />

    <buttons />

    <work />

    <aboutme />

    <newsletter />

    <contact />

    <bottom />
  </div>
</template>



<script>
import buttons from "./components/buttons.vue";
import profile from "./components/profile.vue";
import work from "./components/work.vue";
import aboutme from "./components/aboutme.vue";
import contact from "./components/contact.vue";
import bottom from "./components/bottom.vue";
import newsletter from "./components/newsletter.vue";

export default {
  name: "App",
  components: {
    buttons,
    profile,
    work,
    aboutme,
    contact,
    bottom,
    newsletter,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Nunito:ital,wght@0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap");

* {
  font-family: "Nunito", sans-serif;
  color: #fff;
  scroll-behavior: smooth;
}
.bgG {
  background-color: #000000;
  background-image: linear-gradient(to right, #611f9b, #2f018b);
}

hr.style-two {
  border: 0;
  height: 1px;
  background-image: linear-gradient(
    to right,
    rgba(255, 255, 255, 0),
    rgba(255, 255, 255, 0.374),
    rgba(255, 255, 255, 0)
  );
}

hr.style-one {
  border: 0;
  height: 1px;
  background-image: linear-gradient(
    to right,
    rgba(255, 255, 255, 0.374),
    rgba(255, 255, 255, 0.374),
    rgba(255, 255, 255, 0)
  );
}

hr.style-three {
  border: 0;
  height: 1px;
  background-image: linear-gradient(
    to right,
    rgba(255, 255, 255, 0),
    rgba(255, 255, 255, 0.374),
    rgba(255, 255, 255, 0.374)
  );
}

.right {
  position: absolute;
  right: 7rem;
  width: 300px;
  padding: 0.75rem;
}
</style>