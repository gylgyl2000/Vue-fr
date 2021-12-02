<script>
export default {
    name: 'MenuItem',
    props: ['url', 'text']
}
</script>

<template>
    <img
        class="menu-item__image"
        :src="item.image.source"
        :alt="item.image.alt"
    />
</template>