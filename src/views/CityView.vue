<template>
    <div>
        <Suspense>
            <AsyncCityView></AsyncCityView>
        </Suspense>
    </div>
</template>

<script setup>
import AsyncCityView from '../components/AsyncCityView.vue';

</script>