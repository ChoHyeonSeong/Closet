<script setup lang="ts">
import BaseLayout from '@/layouts/BaseLayout.vue'
</script>

<template>
  <BaseLayout>
    <template #header>
      <div>
        <div class="flex justify-between">
          <div class="flex">
            <div>계정</div>
            <div>재화</div>
          </div>
          <div>메인 네비</div>
        </div>
      </div>
    </template>

    <template #main>
      <div>
        <div class="flex justify-between">
          <div>이벤트</div>
          <div class="flex">
            <div>캐릭터</div>
            <div>캐릭터 정보</div>
          </div>
          <div>서브 네비</div>
        </div>
      </div>
    </template>

    <template #footer>
      <div>
        <div class="flex"></div>
      </div>
    </template>
  </BaseLayout>
</template>

<style scoped></style>
