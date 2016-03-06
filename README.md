<!doctype html>
<html>
<head>
<meta charset="utf-8">

<title>RBS</title>
<link href="css.css" rel="stylesheet" type="text/css">
<link href="beermoney/stylesheet.css" rel="stylesheet" type="text/css">
<style type="text/css">
body,td,th {
	font-family: beermoney;
}
</style>
<link href="beer_money/stylesheet.css" rel="stylesheet" type="text/css">

<!--The following script tag downloads a font from the Adobe Edge Web Fonts server for use within the web page. We recommend that you do not modify it.-->
<script>var __adobewebfontsappname__="dreamweaver"</script>
<script src="http://use.edgefonts.net/aclonica:n4:default;aladin:n4:default;asap:n4:default;annie-use-your-telescope:n4:default;brush-script-std:n4:default;butcherman:n4:default;chewy:n4:default;arizonia:n4:default.js" type="text/javascript"></script>

</head>

<body>
	<div class="top">
		<center><font color="red" style="font-family: 'beer money'">R<font color="#FFFFFF">B</font>S <font color="#FF0000">Lat</font><font color="#FFFFFF">v<font color="#FF0000">ia</font></font>
</div>
<table>
	<tr>
    <td>
    	!!!
    </td>
    <td>
    <?php
    echo"<button><a href='registration.php'>Регистрация</button>"
	?>
    </td>
    <td>
    <a href="ieet.php"><button>Войти</button></a>
    </td>
    </tr>
</table>
	    <div class="body">
    <div class="text">
    	<div style="font-family: 'beer money'; font-weight: 5000; text-align: justify;"><FONT size="100px">
        <div class="text2">
        <?
            $query = "SELECT * FROM `news`";
            $res = mysql_query($query);
            while($row = mysql_fetch_array($res))
            {
            echo "Номер: ".$row['id']."<br>\n";
            echo "Имя: ".$row['firstname']."<br>\n";
            echo "Фамилия: ".$row['surname']."<br><hr>\n";
            }
?>
                ?></div></font>

		</div>
          </div>  
    </div>
    </div>
<div class="right"><font color="red" style="font-style: normal; font-size: 20px; font-weight: 400; font-family: arizonia;">©George</font>
</div>
</body>
</html>
