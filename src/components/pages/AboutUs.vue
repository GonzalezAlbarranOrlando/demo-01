<template>
    <div style="background-color: peru;">
        <h1>About us</h1>
        <p>{{message}}</p>
    </div>
</template>

<script>
    export default {
        name: 'AboutUsView',
        data(){
            return{
                message: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.'
            }
        }
    }
</script>