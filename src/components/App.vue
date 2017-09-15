<template>
<div id="app" class="docs scotchified">
    <nav class="main">
        <div class="container">

            <router-link :to="'/list'" class="brand">
                无名博客 Lite</router-link>
        </div>
    </nav>
    <section class="section" id="top">
        <router-view>
        </router-view>
    </section>
    <footer class="main">
        <p>This is A simple blog light style.</p>
        <p class="less-significant">say thanks to <a href="https://github.com/wuming2018">Github</a></p>
    </footer>
</div>
</template>
<script>
import * as css from '../style/main.css'
export default {
    name: 'app',
    data: function() {
        return {
            subtitle: '无名博客 Lite',
        }
    }
}
</script>
