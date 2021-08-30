<template>
<div id="app">
<navbar></navbar>
<head-body></head-body>
<content-body></content-body>
</div>
</template>

<script>
import navbar from './components/Navbar.vue';
import head from './components/Head.vue';
import content from './components/Content.vue';

export default{
  components: {
    'navbar': navbar,
    'head-body': head,
    'content-body': content,
  }
}

</script>

<style>

</style>
