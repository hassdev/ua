<?php
$ua=$_SERVER['HTTP_USER_AGENT'];
print_r($ua);
if((strpos($ua,'iPhone')!==false)||(strpos($ua,'iPod')!==false)||(strpos($ua,'iPad')!==false)||(strpos($ua,'Android')!==false)||(strpos($ua,'Windows Phone')!==false)) {
	//header("Location:http://google.com/");
	print_r("<br>I am not PC!");
	exit();
}
else {
	//header("Location:http://yahoo.com/");
	print_r("<br>I am PC!");
	exit();
}
?>
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8" />
<title>ua test</title>
</head>

<body>
</body>
</html>
