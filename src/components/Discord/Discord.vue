<template>
<iframe src="https://discord.com/widget?id=1119401118313758720&amp;theme=dark" 
        height="500" 
        allowtransparency="true" 
        frameborder="0" 
        sandbox="allow-popups allow-popups-to-escape-sandbox allow-same-origin allow-scripts"
        class="w-full rounded-lg shadow-md">
</iframe>
</template>

<script setup>
    import { onMounted } from 'vue'
    onMounted(() => {
        const iframe = document.querySelector('iframe')
        iframe.setAttribute('allow', 'geolocation; microphone; camera;')
    })
</script>
