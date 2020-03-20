# IsEmpty

```html
<!DOCTYPE html>
<html>

<head>
  <title>Andrea Harris learn vue.js 01 Declarative Rendering</title>
  <script src="https://cdn.jsdelivr.net/npm/vue@2.6.11"></script>
  <script src="https://cdn.jsdelivr.net/npm/lodash@4.17.15/lodash.min.js" integrity="sha256-VeNaFBVDhoX3H+gJ37DpT/nTuZTdjYro9yBruHjVmoQ=" crossorigin="anonymous"></script>
</head>

<body>
<div id="app">
  <h1 v-if="isEmpty(showOne)">
    {{ message }}
  </h1>

  <h1 v-if="isEmpty(hideOne)">
    {{ message }}
  </h1>

</div>
<script>
  var app = new Vue({
    el: '#app',
    data: {
      showOne: 'test',
      hideOne: {},
      message: 'Show Me!!!',
      isEmpty: _.isEmpty
    }
  })
</script>
</body>

</html>
```