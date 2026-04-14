<script setup>
const buildId = import.meta.env.VITE_BUILD_ID ?? 'local'
const today = new Date().toLocaleDateString('fr-FR')
</script>
<template>
<header>
<p>Nom : Bensafia Chahine</p>
<p>Date : {{ today }}</p>
<p>Build : {{ buildId }}</p>
<p>test modif</p>
<p>test2</p>
</header>
</template>