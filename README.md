# websocket


<!DOCTYPE html>

<html> 
<head>
</head>
<body>


<script>
	function myFunction() {
		var exampleSocket = new WebSocket("ws://localhost:8080/myHandler");
		exampleSocket.onopen = function (event) {
		  exampleSocket.send("Trade 1"); 
		};
		return '';
	}
	//document.getElementById("demo").innerHTML = 
	myFunction();
</script>

<div id="demo"/>

</body>
</html>
