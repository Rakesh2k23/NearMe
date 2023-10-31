# Ex04 Places Around Me
## DATE: 19-10-2023
## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
index.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Map</title>
</head>
<body>
    <img src="Map.png" usemap="#image-map">

    <map name="image-map">
        <area target="_blank" alt="Chennai Central" title="Chennai Central" href="central.html" coords="962,331,1127,450" 
shape="rect">
        <area target="_blank" alt="Chennai Port" title="Chennai Port" href="port.html" coords="1762,307,1876,413" shape="rect">
        <area target="_blank" alt="Chennai Egmore " title="Chennai Egmore " href="egmore.html" coords="87,666,263,723" shape="rect">
        <area target="_blank" alt="Rajiv Gandhi Govt Hospital" title="Rajiv Gandhi Govt Hospital" href="hospital.html" coords="1031,487,1192,567" shape="rect">
        <area target="_blank" alt="Fort St. George Museum" title="Fort St. George Museum" href="fort.html" coords="1444,495,1647,597" shape="rect">
    </map>
</body>
</html>
```




## OUTPUT





## RESULT
The program for implementing image maps using HTML is executed successfully.
