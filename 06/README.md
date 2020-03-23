# Component

```html
<!DOCTYPE html>
<html>

<head>
  <title>Andrea Harris learn vue.js 06 Component</title>
  <script src="https://cdn.jsdelivr.net/npm/vue@2.6.11"></script>
</head>

<body>
<div id="app">
  <ol>
    <todo-item></todo-item>
  </ol>
</div>
<script>
  Vue.component('todo-item', {
    template: '<li>My content in component.</li>'
  });

  var app = new Vue({
    el: '#app'
  })
</script>
</body>

</html>
```