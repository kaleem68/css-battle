### Css Battle: #2 Carrom
#### Problem Link
  https://cssbattle.dev/play/2
 #### Output 
Left one `OUTPUT` is my solution **86.3%** and right one `TARGET` is expected.
 ![Carrom output](Screenshot%202022-07-17%20at%203.33.11%20AM.png)
#### Solution

```Html
<div class="container">
	<div class="container-items">
		<div class="row">
			<div class="square"></div>
			<div class="square"></div>
		</div>
		<div class="row">
			<div class="square"></div>
			<div class="square"></div>
		</div>
	</div>
</div>

<style>
.container {
	background: #62374e;
	width: 400px;
	height: 300px;
}

.container-items {
	display: flex;
	flex-direction: column;
	gap: 70px;
}

.row {
	display: flex;
	justify-content: space-around;
	margin-top: 35px;
}

.square {
	width: 50px;
	height: 50px;
	background: #fdc57b;
}
</style>
```
