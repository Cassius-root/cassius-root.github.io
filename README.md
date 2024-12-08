<h6>:)</h6>
<style>
body {
background-color:DarkOrange}
</style>

<script>
setInterval(myTimer, 1000);

function myTimer() {
	var newWindow;

	{
	var random = (Math.random() * 1300);
	var rando = (Math.random() * 1300);
	var specs = "height=100px, width=100px, left=" + random ", top=" + rando;
	newWindow = window.open("URL","test", specs);
	newWindow.close();
	}
}
</script>
