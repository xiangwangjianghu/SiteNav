<script lang="ts" setup>
  import { toggleDark } from "~/composables";
</script>

<template>
  <div>
    <div class="toolbar">
      <div>
        <button @click="toggleDark()" class="border-none w-full bg-transparent cursor-pointer"
          style="height: var(--ep-menu-item-height)">
          <i inline-flex i="dark:ep-moon ep-sunny" />
        </button>
      </div>
    </div>
  </div>
</template>
<style scoped>
  .margin-lr {
    margin: 0 10px;
  }

  .toolbar {
    display: flex;
    align-items: center;
    flex-direction: row;
    flex-wrap: nowrap;
    align-content: center;
    justify-content: flex-end;
  }
</style>