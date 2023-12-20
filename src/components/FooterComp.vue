<template>
    <div class="container-fluid bg-black">
        <div class="row">
            <p class="lead">
                Jodie's example Portfolio &copy;
                <span>{{ currYear }}</span>
            </p>
        </div>
    </div>
</template>

<script>
    export default {
        name:'FooterComp',
    data() {
            return {
                currYear: new Date().getFullYear()
            }
        }
    }
</script>

<style scoped>
.container-fluid {
    position: fixed;
    bottom: 0;
}
</style>