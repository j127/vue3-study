<template>
    <Navbar :siteName="siteName" />
</template>

<script>
import { siteName } from "./config";
import Navbar from "./components/Navbar.vue";

console.log("siteName", siteName);
export default {
    name: "App",
    components: {
        Navbar,
    },
    data() {
        return {
            siteName,
        };
    },
};
</script>
