<template>
</template>

<script lang="ts" src="./GlobalSyncStatus.vue.ts"></script>

<style lang="less" scoped>
@import "../styles/index";

.global-sync-status {
  padding-right: 12px;

  &:before {
    content: '|';
    padding-right: 12px;
    opacity: .5;
    color: @grey;
  }
}

.icon-cloud-backup-2 {
  color: @grey;
}
</style>
