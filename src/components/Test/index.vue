<template>
    <div class="test"></div>
</template>
<script lang="ts" setup>

const props = withDefaults(
    defineProps<{
        visible: boolean;
    }>(),
    {}
);
const emits = defineEmits<{
    change: [id: number];
}>();
emits('change', 1);
</script>
