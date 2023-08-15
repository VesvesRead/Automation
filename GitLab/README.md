<style>
  .flex-container {
    display: flex;
  }

  .box {
    flex: 1;
    padding: 20px;
    transition: flex-grow 0.3s;
  }

  .box:hover {
    flex-grow: 2;
  }
</style>

# Gitlab
```html
<div class="flex-container">
  <div class="box">Introduction</div>
  <div class="box">Repos</div>
  <div class="box">Groups</div>
  <div class="box">Runners</div>
  <div class="box">Pipelines</div>
</div>
