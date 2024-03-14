<script setup lang="ts"></script>

<template>
  <main>
    <div role="article" class="image-container">
      <img src="/src/assets/images/avatar-jessica.jpeg" alt="profile image" />
    </div>
    <div role="article" class="profile-info-container">
      <h1>Jessica Randall</h1>
      <p>London, United Kingdom</p>
    </div>
    <div role="article" class="profile-social-container">
      <span>"Front-end developer and avid reader."</span>
      <div class="social-icon-container">
        <a class="social-media-card"> GitHub </a>
        <a class="social-media-card"> Frontend Mentor </a>
        <a class="social-media-card"> LinkedIn </a>
        <a class="social-media-card"> Twitter </a>
        <a class="social-media-card"> Instagram </a>
      </div>
    </div>
  </main>
  <footer class="attribution">
      Challenge by
      <a href="https://www.frontendmentor.io?ref=challenge" target="_blank"
        >Frontend Mentor</a
      >. Coded by <a href="https://www.linkedin.com/in/mikiyas-kebede-b661aa225/">Mikiyas Kebede</a>.
    </footer>
</template>

<style scoped>
.attribution {
  display: flex;
  justify-content: center;
  margin-top: 20px;
  font-size: 11px;
  text-align: center;
}
.attribution a {
  color: hsl(228, 45%, 44%);
  font-size: 11px;

}
</style>
