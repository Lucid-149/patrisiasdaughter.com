<template>
  <div class="container">
    <div>
      <img src="~/assets/img/Fashion.jpg" alt="" />
      <li v-for="post of posts" :key="post.slug">
        <NuxtLink :to="post.slug">{{ post.title }}</NuxtLink>
      </li>
    </div>
  </div>
</template>
<script></script>
