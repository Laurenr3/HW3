# HW3
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Projections</title>
</head>
<body>
    <h1>Lauren Robinson HW 3: In this project I learned how to display images in different projections</h1>
    
    <h2 style="color:red">Describe in your own words how you displayed the map in different projections using QGIS</h2>
    <p>In QGIS, changing the projection allows you to view your created map from different perspectives. 
        At the bottom of the screen, I clicked the CRS button and entered the EPSG associated with the desired projection. 
    </p>
    
    <h2>WGS84 Projection</h2>
    <h3>This projection has some size as well as shape distortion towards the top and bottom. The middle of the map is accurate in size and shape. </h3>
    <a href=".//maps/4326.png">
    <img src=".//maps/4326.png" alt="WGS84" width='500px'>
    </a>
    <h2>Aitoff Projection</h2>
    <h3>This projection is more accurate in size and shape towards the center. It becomes more distorted in both size and shape as you get further from the center of the map, both towards the top/bottom and the sides. </h3>
    <a href=".//maps/54043.png">
    <img src=".//maps/54043.png" alt="Aitoff" width='500px'>
    </a>
    <h2 style="color:red">Now, you should <u>add the following projections on your own:</u></h2>
    <h3>EPSG: 3857, 53018, 54034, 54027, 102016, and two additional projections that you choose.</h3>
    <p></p>
    <h2>Pseudo-Mercator Projection</h2>
    <h3>This projection is more accurate towards the middle, along the equator line but still has slight shape distortion. As you approach the top and bottom is becomes more distorted in size and shape.</h3>
    <a href="./maps/3857.png">
    <img src=".//maps/3857.png" alt="WGS84" width='500px'>
    </a>
    <h2>Winkel I Projection</h2>
    <h3>This projection is the most accurate directly in the middle. Beyond this point, size and shape begin changing and are no longerly entirely accurate. The top and bottom are the most distorted.</h3>
    <a href=".//maps/53018.png">
    <img src=".//maps/53018.png" alt="WGS84" width='500px'>
    </a>
    <h2>Equal Area Cylindrical Projection</h2>
    <h3>This projection distorts the top and bottom, making them much smaller and more compressed than usual. The middle, near the equator line, is accurate in both size and shape. </h3>
    <a href=".//maps/54034.png">
    <img src=".//maps/54034.png" alt="WGS84" width='500px'>
    </a>
    <h2>Equidistant Area Cylindrical Projection</h2>
    <h3>Similar to the previous projection, this projection strongly distorts the top and bottom of the map. While remaining accurate for the middle. </h3>
    <a href=".//maps/54034.png">
    <img src=".//maps/54034.png" alt="WGS84" width='500px'>
    </a>
    <h2>Equidistant Conic Projection</h2>
    <h3>This projection distorts the sides by making them larger and more stretched out, while making the middle smaller and more compressed. It also shows a view from the top of a globe, rather than looking straight on. </h3>
    <a href=".//maps/54027.png">
    <img src=".//maps/54027.png" alt="WGS84" width='500px'>
    </a>
    <h2>Azimuthal Equidistant Projection</h2>
    <h3>This projection looks similar to the previous projection, but it makes the middle/top even smaller and more compressed, as well as making the outsides more stretched out.</h3>
    <a href=".//maps/102016.png">
    <img src=".//maps/102016.png" alt="WGS84" width='500px'>
    </a>
    <h2>Sphere Robinson Projection</h2>
    <h3>This is another projection that is more accurate in the middle, with a distorted top and bottom. The edges are curved in this projection.</h3>
    <a href=".//maps/53030.png">
    <img src=".//maps/53030.png" alt="WGS84" width='500px'>
    </a>
    <h2>Grid Global Projection</h2>
    <h3>This is similar to the previous projection, except the edges are straight lines instead of being curved like the previous projection. This projection also has more accuracy in the middle and increased distortion towards the outsides and the top/bottom.</h3>
    <a href=".//maps/3410.png">
    <img src=".//maps/3410.png" alt="WGS84" width='500px'>
    </a>
    <h2>Data used for this project</h2>
    <a href="https://www.naturalearthdata.com/http//www.naturalearthdata.com/download/10m/cultural/ne_10m_admin_0_countries.zip"> Download Natrual Earth 1:10m Cultural Vector </a>
</body>
</html>
