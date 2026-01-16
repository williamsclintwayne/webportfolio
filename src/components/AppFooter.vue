<script setup lang="ts">
const scrollToTop = () => {
    window.scrollTo({ top: 0, behavior: 'smooth' })
}
</script>

<template>
    <footer>
        <p>
            Coded in
            <a href="https://code.visualstudio.com/" target="_blank" class="anchor-text">
                Visual Studio Code
            </a>
            <br />
            Built with Vue & TypeScript.
        </p>

        <button class="scroll-to-top" @click="scrollToTop">
            <i class="fa fa-arrow-up"></i>
        </button>
    </footer>
</template>
