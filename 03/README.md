# Loops

```html
<!DOCTYPE html>
<html>

<head>
	<title>Andrea Harris learn vue.js 03 Loops</title>
	<script src="https://cdn.jsdelivr.net/npm/vue@2.6.11"></script>
</head>

<body>
	<div id="app">
		<ol>
			<li v-for="todo in todos">
				{{ todo.text }}
			</li>
		</ol>
	</div>
	<script>
		var app = new Vue({
			el: '#app',
			data: {
				todos: [
					{ text: 'Learn JavaScript' },
					{ text: 'Learn Vue' },
					{ text: 'Build something awesome' }
				]
			}
		})
	</script>
</body>

</html>
```