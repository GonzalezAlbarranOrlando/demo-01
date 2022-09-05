<template>
    <div style="background-color: goldenrod;">
        <h1>Contact</h1>
        <p>{{message}}</p>
        <router-link to="/">Home</router-link>
    </div>
</template>

<script>
    export default {
        name: 'ContactView',
        data(){
            return{
                message: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.'
            }
        }
    }
</script>
