
<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8">
		<title>鼠标事件</title>
		<style type="text/css">
			body{
				background-color:coral;
			}
			img{
				width: 400px;
				height: 300px;
			}
			div{
				width: 300px;
				height: 300px;
				margin: 0 auto;
			}
		</style>
		<script type="text/javascript">
			function my(){
				alert("吃的来咯");
			}
			function myfouse(){
				var a=document.getElementById("demo");
				alert("吃完咯没有咯");
			}
		</script>
	</head>
	<body onload="my()">
		<div >
			![image](https://github.com/wendylz/mouse/raw/main/mouse.png)
			<input type="text" onchange="myfouse()" id="demo" onblur="myfouse()"/>
		</div>
		
	</body>
</html>
