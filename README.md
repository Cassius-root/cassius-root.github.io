<h6>:)</h6>
<style>body {
  background-color: Black;
  h6 {
  color: green;
  text-align: center;
}
}</style>
<script>
	var newWindow;
	
	setInterval(function(){
        var RandomX = (Math.random() * 1024) + 1;
        var RandomY = (Math.random() * 768) + 1;
	var specs = "height=100px, width=100px, left=" + RandomX + ", top=" + RandomY;
	newWindow = window.open("https://cassius-root.github.io/","test", specs);
	}, 50);
 	setInterval(function(){
	newWindow.close();
	}, 10000);	
	
</script>
