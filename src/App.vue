<template>
    <div class="container">
        <app-header></app-header>
        <hr>
        <div class="row">
            <app-servers></app-servers>
            <app-server-details></app-server-details>
        </div>
        <hr>
        <footer></footer> 
    </div>
</template>

<script>
import Header from './Header.vue';
import Servers from './Servers.vue';
import ServerDetails from './ServerDetails.vue';
import Footer from './Footer.vue';

export default {
    components: {
        'app-header': Header,
        'app-servers': Servers,
        'app-server-details': ServerDetails,
        'app-footer': Footer
    }
}
</script>


<style>

</style>
