<template>
    <div id="app">
        <app-navbar />
        <app-calendly />
        <app-footer />
    </div>
</template>

<script>
import Navbar from './components/Navbar'
import Footer from './components/Footer'
import Calendly from './components/Calendly'

export default {
    name: 'App',
    components: {
        'app-navbar': Navbar,
        'app-calendly': Calendly,
        'app-footer': Footer, 
    },
}
</script>