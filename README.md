<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title></title>
</head>
<body>
	<div id="block">
		<h1>Guessing Game</h1>
		<form>
			<label>Your Guess (1~100)</label>
			<input type="number" id="num" name="guess">
		</form>
		<input type="button" id="guessBtn" value="play" name="play" onclick="guess()">
		<table id="table">
			<tr>
				<th>Result</th>
			</tr>
		</table>
	</div>

<script type="text/javascript">
	var random = Math.floor((Math.random() * 100) + 1);
	var min = 1;
	var max = 100;

	function guess() {
		input = document.getElementById("num").value;

		if (input == random) {
			alert("Bingoooo!!!!");
			location.reload();
		}

		while (input != random) {
			if (input > random) {
				if (input < max { max = input;}
					var tr = document.createElement("tr");
					var td = document.createElement("td");
					var text = document.creatTextNode(min + "~" + max);
					td.appendChild(text);
					tr.appendChild(td);
					document.getElementById("Table").appendChild(tr);
					break;
			}
		}
	}
</script>	
</body>
</html>
