# calicurate-by-JS

<!DOCTYPE html>
<html>
<head>
	<title>Average</title>
</head>
<body>
	<p id="here">the average goes here</p>
<script>
	let numberArray = [10,50,97,22,9,13,1000,1000,75];
	let average;
	let sum = 0;
	let i;

	for(i = 0; i < 9; i += 1){
		sum += numberArray[i];
	}

	average = sum / 9;

	document.getElementById("here").innerHTML = average;


</script>


</body>
</html>
