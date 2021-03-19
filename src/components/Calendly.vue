<template>
    <div class="calendly-inline-widget" data-url="https://calendly.com/test-rima/acara-percobaan" style="height:600px;"></div>
</template>

<script>
    export default {
        mounted () {
            const recaptchaScript = document.createElement('script')
            recaptchaScript.setAttribute('src', 'https://assets.calendly.com/assets/external/widget.js')
            document.head.appendChild(recaptchaScript)
        }
    }
</script>