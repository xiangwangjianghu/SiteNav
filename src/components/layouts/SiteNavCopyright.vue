<template>
  <div class="footer-copyright hidden-content">
    &copy;{{ year }} &nbsp; <strong>AI人导航</strong>&nbsp;
  </div>
</template>

<style>
  .footer-copyright {
    height: 100%;
    display: flex;
    flex-direction: row;
    flex-wrap: nowrap;
    align-content: center;
    justify-content: center;
    align-items: center;
  }

  @media only screen and (max-width: 768px) {
    .hidden-content {
      display: none;
    }
  }
</style>

<script lang="ts" setup>
  const year = new Date().getUTCFullYear();
</script>