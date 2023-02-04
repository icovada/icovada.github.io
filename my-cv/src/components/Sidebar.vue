<script setup lang="ts">
import ListSection from '../components/ListSection.vue'

const techskills = ["Is a penguin", "can imagine big penguins"]
</script>


<template>
  <div class="col-12 col-md-4 col-xl-3 col-xxl-2 d-flex flex-column flex-shrink-0 p-3 text-bg-dark sidebar">
    <img src="@/assets/me.png" alt="A picture of me" class="border border-white border-4 rounded-circle my-4">
    <h1 class="fs-2 text-center">Federico Tabbò</h1>
    <hr>
    <h2 class="fs-4 my-2">About me</h2>
    <span class="ms-2">Network engineer looking to move into the DevOps space</span>
    <hr>
    <h2 class="fs-4 my-2">Contacts</h2>
    <a class="contact-links" href="https://github.com/icovada/"><i class="bi bi-github mx-2"></i>GitHub</a>
    <a class="contact-links" href="https://www.linkedin.com/in/federico-tabb%C3%B2-330798ba/"><i
        class="bi bi-linkedin mx-2"></i>LinkedIn</a>
    <a class="contact-links" href="https://blog.tabbo.it"><i class="bi bi-wordpress mx-2"></i>Blog</a>
    <a class="contact-links" href="mailto:cv@tabbo.it"><i class="bi bi-envelope-at mx-2"></i>cv@tabbo.it</a>
    <hr>
    <ListSection title="Tech skills" list={{ techskills }}>
    </ListSection>
    <hr>
    <h2 class="fs-4 my-2">Hobbies</h2>
    <ul>
      <li>Woodworking</li>
      <li><a href="https://www.youtube.com/watch?v=IWhAjl318Aw">3D modeling in Blender</a></li>
      <li>Writing for my <a href="https://blog.tabbo.it">blog</a></li>
      <li>Home automation</li>
    </ul>
    <hr>

  </div>

</template>

<style scoped>
.sidebar {
  overflow-y: scroll;
}
</style>