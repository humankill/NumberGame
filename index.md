<!DOCTYPE html>
<html>
<head>
	<title>
		
	</title>
</head>
<body>
	<script>
		var rand
		rand = Math.floor((Math.random()*10)+1);

		var guess
		guess = window.prompt("Please guess a number from 1 to 10")

		random= parseInt(rand);
		again= parseInt(guess);


		while (again != random){
			again = window.prompt("Please guess another number from 1 to 10")
	}
		alert("Congratulation!")

			
		</script>

</body>
</html>
