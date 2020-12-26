<template>
  <Navigation />
  <Sidebar />
  <div class="content-wrapper">
    <router-view/>
  </div>
</template>

<script>
import Navigation from './components/Navigation';
import Sidebar from './components/Sidebar';
export default {
  components: {Navigation, Sidebar}
}
</script>