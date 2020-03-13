# Condigionals

```html
<!DOCTYPE html>
<html>

<head>
  <title>Andrea Harris learn vue.js 02 Conditionals</title>
  <script src="https://cdn.jsdelivr.net/npm/vue@2.6.11"></script>
</head>

<body>
  <div id="app">
    <span v-if="seen">Now you see me</span>
    <span v-if="hidden">I hidden now</span>
  </div>
  <script>
    var app = new Vue({
      el: '#app',
      data: {
        seen: true,
        hidden: false
      }
    })
  </script>
</body>

</html>
```