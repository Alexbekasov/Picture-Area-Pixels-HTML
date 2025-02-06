<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Map are elemendid HTML</title>
  <link rel="stylesheet" href="mapstyle.css">
</head>
<body>
<h1>Map ootab hiire klicki!</h1>
<img src="mapPilt.png" alt="pilt" usemap="#pilt">
<map name="pilt">
<!-----circle coords=x,y,R-->
<area shape="circle" coords="354,90,60" href="ring.html" alt="ring">
  <!--rectangle-->
  <area shape="rect" coords="107,141,271,251" href="rectangle.html" alt="rectangle">
  <!--poly-->
  <area shape="poly" coords="114,162, 191,63,266,164" href="poly.html" alt="poly">
</map>
<div id="Kirjeldus">Siia tuleb kirjeldus></div>
</body>
</html>
----------------------------------
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Map are elemendid HTML</title>
    <link rel="stylesheet" href="mapstyle.css">
</head>
<body>
<h1>Map ootab hiire klicki!</h1>
<img src="mapPilt.png" alt="pilt" usemap="#pilt">
<map name="pilt">
<!-----circle coords=x,y,R-->
<area shape="circle" coords="354,90,60" href="ring.html" alt="ring">
  <!--rectangle-->
  <area shape="rectangle" coords="107,141,271,251" href="rectangle.html" alt="rectangle">
  <!--poly-->
  <area shape="poly" coords="114,162, 191,63,266,164" href="poly.html" alt="poly">
</map>
<div id="Kirjeldus">Siia tuleb ring></div>
</body>
</html>
------------------------------
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Map are elemendid HTML</title>
    <link rel="stylesheet" href="mapstyle.css">
</head>
<body>
<h1>Map ootab hiire klicki!</h1>
<img src="mapPilt.png" alt="pilt" usemap="#pilt">
<map name="pilt">
<!-----circle coords=x,y,R-->
<area shape="circle" coords="354,90,60" href="ring.html" alt="ring">
  <!--rectangle-->
  <area shape="rectangle" coords="107,141,271,251" href="rectangle.html" alt="rectangle">
  <!--poly-->
  <area shape="poly" coords="114,162, 191,63,266,164" href="poly.html" alt="poly">
</map>
<div id="Kirjeldus">Siia tuleb rectangle></div>
</body>
</html>
-------------------------------------
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Map are elemendid HTML</title>
    <link rel="stylesheet" href="mapstyle.css">
</head>
<body>
<h1>Map ootab hiire klicki!</h1>
<img src="mapPilt.png" alt="pilt" usemap="#pilt">
<map name="pilt">
<!-----circle coords=x,y,R-->
<area shape="circle" coords="354,90,60" href="ring.html" alt="ring">
  <!--rectangle-->
  <area shape="rectangle" coords="107,141,271,251" href="rectangle.html" alt="rectangle">
  <!--poly-->
  <area shape="poly" coords="114,162, 191,63,266,164" href="poly.html" alt="poly">
</map>
<div id="Kirjeldus">Siia tuleb poly></div>
</body>
</html>
-----------------------------------------------
div#Kirjeldus{
    width:1000px;
    height:100px;
    padding:10px;
   position:absolute;
    top:100px;
    left:450px;
    border:1px solid #ccc;
}
