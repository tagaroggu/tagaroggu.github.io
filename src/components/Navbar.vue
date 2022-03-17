<script setup>
    const showing = ref(false);
</script>
<template>
    <nav class="navbar">
        <div class="navbar-brand">
            <a role="button" class="navbar-burger" :class="{ 'is-active': showing }" @click="showing = !showing">
                <span aria-hidden="true"></span>
                <span aria-hidden="true"></span>
                <span aria-hidden="true"></span>
            </a>
        </div>
        <div class="navbar-menu" :class="{ 'is-active': showing }">
            <div class="navbar-start">

            </div>
            <div class="navbar-end">

            </div>
        <div>
    </nav>
</template>