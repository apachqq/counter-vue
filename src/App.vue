<template>
    <div class="container pt-5" id="app" v-cloak>
        <div class="card center">
            <h1>{{ title }}: {{ counter }}</h1>
            <div>
                <button class="btn primary" v-on:click="counter++">Добавить</button>
                <button class="btn danger" v-on:click="counter--">Вычесть</button>
            </div>
        </div>
    </div>
</template>

<script>
    import AppMixin from '@/mixins/AppMixin'

    export default {
        mixins: [AppMixin]
    }
</script>

<style>
</style>
