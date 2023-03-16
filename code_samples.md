# Code Samples

Shown below will be samples of code that I have written this semester: 

**Python:** 

#This program is used to caculate hourly wage 

hours = input("Enter numbers of hours daily: ")

wage = input("Enter the hourly wage:  ")

print("Yearly wage =",int(hours) * int(wage) * 365)

**HTML:** 

<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Fizz Buzz</title>
<script>

function fizzbuzz() {
	var display = document.getElementById('display');
	var displayHTML = "";
	for (i = 1; i <= 100; i++) {
		var result = "";
		if (i % 3 == 0) result += "Fizz";
		if (i % 5 == 0) result += "Buzz"
		if (!result) result = i;
		displayHTML += "<p>" + result + "</p>";
	}
	display.innerHTML = displayHTML;
}

</script>

</head>

<body onload="fizzbuzz()">
<div id="display">

</div>
</body>

</html>
	
	
	
[Return to Home Page](./README.md)
