# Input Text

```html
<!DOCTYPE html>
<html>

<head>
  <title>Andrea Harris learn vue.js 04 Button click</title>
  <script src="https://cdn.jsdelivr.net/npm/vue@2.6.11"></script>
</head>

<body>
  <div id="app">
    <p>{{ message }}</p>
    <input v-model="message">
  </div>
  <script>
    var app = new Vue({
      el: '#app',
      data: {
        message: 'I\'m Andrea Harris!!'
      }
    })
  </script>
</body>

</html>
```