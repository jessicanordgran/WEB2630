<template>
    <div class="container">
        <!--<div class="row">-->
            <!--<div class="col-xs-12">-->
                <!--<header>-->
                    <!--<h1>Server Status</h1>-->
                <!--</header>-->
            <!--</div>-->
        <!--</div>-->
        <app-header></app-header>
        <hr>

        <!--<div class="row">-->
            <!--<div class="col-xs-12 col-sm-6">-->
                <!--<ul class="list-group">-->
                    <!--<li-->
                            <!--class="list-group-item"-->
                            <!--v-for="index in 5">-->
                        <!--Server #{{ index }}-->
                    <!--</li>-->
                <!--</ul>-->
            <!--</div>-->
            <!--<div class="col-xs-12 col-sm-6">-->
                <!--<p>Server Details are currently not updated</p>-->
            <!--</div>-->
        <!--</div>-->
        <server></server>
        <app-server-details></app-server-details>
        <hr>
        <!--<div class="row">-->
            <!--<div class="col-xs-12">-->
                <!--<footer>-->
                    <!--<p>All Servers are managed here</p>-->
                <!--</footer>-->
            <!--</div>-->
        <!--</div>-->

    </div>
</template>

<script>
    import Header from './Shared/Header.vue';
    import Footer from './Shared/Footer.vue';
    import Server from './Server/Server.vue';
    import ServerDetails from './Server/ServerDetails.vue';

    export default {
        components: {
            appHeader: Header,
                'app-footer': Footer,
        Server,
                'app-server-details': ServerDetails
        }
    }

</script>

<style>

</style>
