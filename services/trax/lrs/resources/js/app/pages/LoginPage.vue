<template>
    <centered brand links>
        <login-card redirect-route-name="home"></login-card>
    </centered>
</template>

<script>
    import Centered from '../layout/parts/Centered'
    import LoginCard from '../components/Auth/LoginCard'

    export default {

        components: {
            Centered, LoginCard
        }
    }
</script>
