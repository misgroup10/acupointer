
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>PHP practice1</title>
</head>
<body>
	<?php
		$begin=12;
		$end=18;
		for($i = $begin; $i <= $end; $i +=3 ){		
	?>
	<p style="font-size: <?php echo $i;?> pt">
	第一支PHP網頁程式
	<?php
		print "</p>";
		} 
	?>
	
</body>
