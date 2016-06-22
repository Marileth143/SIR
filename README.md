<html>
	<head>
	</head>
		<script>
			function love(){
			var l= document.getElementById("love1");
			var o= document.getElementsByTagName("INPUT");

			for(var x=0;x<o.length; x++){
			o[x].value=l.value;
			}
			}
		</script>		
	<body>
		<center>
		<h3 style="background-color:#248f8f; padding:10px 20px; color:white; width:350px">Assignment</h3>
		<form action="assignment.php" method="GET">
			<input type ="text" name="l1" id="love1" onkeyup="love()"></input>
			<input type ="text" name="l2" id="love2" onkeyup="love()"></input>
			<input type ="text" name="l3" id="love3" onkeyup="love()"></input>
			<input type ="text" name="l4" id="love4" onkeyup="love()"></input>
			<input type ="text" name="l5" id="love5" onkeyup="love()"></input>
		</center>
		</form>
	</body>
</html>
