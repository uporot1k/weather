<template lang="pug">
  #app
    header.header
      header-menu
      search
    aside.sidebar
    .workspace


</template>
<style lang="stylus">

#app
  width 100%
  height 100vh
  display grid 
  grid-template-columns: 150px 1fr
  grid-template-rows: 150px 1fr
  grid-template-areas: 'header header' 'aside workspace';

.header
  grid-area: header 
.sidebar
  grid-area: aside
.workspace
  grid-area: workspace       
</style>
