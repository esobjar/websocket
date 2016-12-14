# websocket


	function myFunction() {
		var exampleSocket = new WebSocket("ws://localhost:8080/myHandler");
		exampleSocket.onopen = function (event) {
		  exampleSocket.send("Trade 1"); 
		};
		return '';
	}
	myFunction();
