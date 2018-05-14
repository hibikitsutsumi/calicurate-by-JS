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


---------------------------------------
  let oddNumbers = [];
  let counter = 0;
  let value = 1;

  for (counter = 0; counter < 80; counter+=1){
  	oddNumbers[counter] = value;
  	value +=2;
  }
  
  document.getElementById("here").innerHTML = oddNumbers;
  
  -------------------------------------------------------
  
	let userDetails = [];
	userDetails[0] = prompt("what is your first name?");
	userDetails[1] = prompt("what is your last name?");
	userDetails[2] = prompt("how old are you?");
	
	let info = document.getElementById("here").innerHTML = userDetails[0] + " " + userDetails[1] + " " + userDetails[2];
	
  
