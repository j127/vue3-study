<template>
    <nav>{{ siteName }}</nav>
</template>

<script>
export default {
    name: "Navbar",
    props: {
        siteName: { type: String, required: true },
    },
};
</script>
