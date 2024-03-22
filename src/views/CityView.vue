<template>
    <div>
        <!-- 利用vue 內建 Suspense tag 加載中狀態 -->
        <!-- 有两個插槽：#default 和 #fallback -->
        <Suspense>
            <AsyncCityView />
            <template #fallback>
                <CityViewSkeleton />
            </template>
        </Suspense>
    </div>
</template>

<script setup>
import AsyncCityView from '@/components/AsyncCityView.vue';
import CityViewSkeleton from '@/components/CityViewSkeleton.vue';

</script>
