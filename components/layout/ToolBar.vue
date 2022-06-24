<template>
  <nav class="tool-bar">
      <ul>
          <li class="button">Create Universe</li>
          <li class="button">Reset View</li>
          <li class="button">Zoom In</li>
          <li class="button">Zoom Out</li>
      </ul>
  </nav>
</template>

<style lang="scss">
    .tool-bar {

        ul {
          display: flex;
          list-style: none;
          justify-content: end;


          .button {
            padding: 5px 11px;
            background-color: #c7493a;
            display: inline-block;
            margin: 14px;
            color: #ffffff;
          }
        }
    }
</style>

<script>
export default {
  name: 'ToolBar'
}
</script>
