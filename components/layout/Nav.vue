<template>
  <nav class="nav-bar">
      <ul>
          <li >Home</li>
          <li>Settings</li>
      </ul>
  </nav>
</template>

<style lang="scss">
    .nav-bar {
        
        ul {
          list-style: none;
          display: flex;
          justify-content: space-between;

          li {
            
            &:first-of-type {
              margin-left: 0;
            }

            margin: 14px;
            display: inline-block;
          }
        }
    }
</style>

<script>
export default {
  name: 'NavBar'
}
</script>
