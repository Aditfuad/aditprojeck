<!DOCTYPE html>
<html>
<head>
	<title>Landing Page</title>
	<style>
		body {
			margin: 0;
			padding: 0;
			font-family: Arial, sans-serif;
			background-color: #f2f2f2;
		}
		
		header {
			background-color: #333;
			color: #fff;
			text-align: center;
			padding: 20px;
		}
		
		h1 {
			margin: 0;
			font-size: 36px;
			text-transform: uppercase;
		}
		
		.container {
			width: 80%;
			margin: auto;
			padding-top: 50px;
			padding-bottom: 50px;
		}
		
		.row {
			display: flex;
			flex-wrap: wrap;
			justify-content: center;
		}
		
		.col {
			flex-basis: 30%;
			margin: 10px;
			background-color: #fff;
			border-radius: 5px;
			padding: 20px;
			text-align: center;
			box-shadow: 0px 0px 10px #ccc;
		}
		
		h2 {
			margin: 0;
			font-size: 24px;
			text-transform: uppercase;
			margin-bottom: 20px;
		}
		
		p {
			margin: 0;
			font-size: 16px;
			line-height: 1.5;
		}
		
		button {
			background-color: #333;
			color: #fff;
			border: none;
			border-radius: 5px;
			padding: 10px 20px;
			margin-top: 20px;
			cursor: pointer;
			transition: background-color 0.3s;
		}
		
		button:hover {
			background-color: #444;
		}
		
		footer {
			background-color: #333;
			color: #fff;
			text-align: center;
			padding: 20px;
		}
		
	</style>
</head>
<body>
	<header>
		<h1>Landing Page</h1>
	</header>
	<div class="container">
		<div class="row">
			<div class="col">
				<h2>Product 1</h2>
				<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. In pharetra quam velit, ut tincidunt lacus interdum sit amet.</p>
				<button>Learn More</button>
			</div>
			<div class="col">
				<h2>Product 2</h2>
				<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. In pharetra quam velit, ut tincidunt lacus interdum sit amet.</p>
				<button>Learn More</button>
			</div>
			<div class="col">
				<h2>Product 3</h2>
				<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. In pharetra quam velit, ut tincidunt lacus interdum sit amet.</p>
				<button>Learn More</button>
			</div>
		</div>
	</div>
	<footer>
		<p>&copy; 2023 Landing Page</p>
	</footer>
</body>
</html>
