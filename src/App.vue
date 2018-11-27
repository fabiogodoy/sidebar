<template>
  <div id="app">
    <div class="wrapper">
        <sidebar></sidebar>
        <div id="content">
            <router-view/>
        </div>
    </div>
  </div>
</template>

<script>
import sidebar from './components/Sidebar.vue'

export default {
  name: 'App',
  components: {sidebar}
}
</script>

<style>

</style>
