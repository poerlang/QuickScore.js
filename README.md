# QuickScore.js

```js
<script src="quicksore.js"></script>
  <script>
    const qs = new QuickScore(["crm客服", "客服CRM", "GitHub", "hello, moketao"]);
    const results = qs.search("crm");
    console.log(results);
  </script>
```

output:


```js
[{
	"item": "crm客服",
	"score": 0.96,
	"matches": [
		[0, 3]
	],
	"_": "crm客服"
}, {
	"item": "客服CRM",
	"score": 0.9399999999999998,
	"matches": [
		[2, 5]
	],
	"_": "客服crm"
}]
```
