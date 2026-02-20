# Ex03 Places Around Me
## Date: 16.02.2026

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google as an image.

### STEP 3
Insert the image using ```<img>``` tag and link it to the map.

### STEP 4
Using ```<map>``` tag name the map.

### STEP 5
Create clickable regions in the image using ```<area>``` tag.

### STEP 6
Write HTML programs for all the regions identified.

### STEP 7
Execute the programs and publish them.

## CODE:
```
map.html

<html>
    <head>
        <title> nagapattinam MAP</title>
    </head>

    <body bgcolor="pink">
        <h1 align="center">NAGAPATTINAM   HARINI SREE N (212225230093)</h1>
        <br>
        
        
       <img src="mapapp/static/Screenshot 2026-02-16 091221.png" usemap="#image-map">





<img src="Screenshot 2026-02-16 091221.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="devi cinemas" title="devi cinemas" href="devi.html" coords="1021,532,1191,613" shape="rect">
    <area target="" alt="light house" title="light house" href="light.html" coords="1386,632,1446,611,1513,661,1489,716,1429,732,1373,697" shape="poly">
    <area target="" alt="nagai beach" title="nagai beach" href="beach.html" coords="1406,109,68" shape="circle">
    <area target="" alt="harbour" title="harbour" href="harbour.html" coords="1354,216,1301,353,1457,335" shape="poly">
    <area target="" alt="bus stand" title="bus stand" href="bus.html" coords="1015,344,1168,492" shape="rect">
</map>
    </body>
</html>


beach.html

<html>
    <head>
        <title>nagai beach</title>
    </head>
    <body bgcolor="red">
        <h>nagai beach</h>
        <p> Nagai Beach in Nagapattinam is a beach pavilion located in the heart of the town, offering a serene environment with its own beach. It is situated on arriya natty street, 8th lane, Melakottaivasal, Nagapattinam, Tamil Nadu 611003, India. The beach pavilion is well-rated by visitors, with an average rating of 4.30 out of 5 stars based on 32 reviews. It is conveniently located about 0.65 kilometers from the Velippalaiya railway station, making it easily accessible for travelers </p>
    </body>
</html>

harbour.html

<html>
    <head>
        <title>harbour</title>
    </head>
    <body bgcolor="green">
        <h>harbour</h>
        <p> 
Nagapattinam Harbour is a natural port located in the Bay of Bengal, specifically in the Tamil Nadu state of India. It is situated at the mouth of the river Kaduvayar and has been a significant maritime hub for centuries. The harbour is known for its historical importance during the Medieval Cholas period and has been a key port for trade and naval expeditions. It was later colonized by the Portuguese and later the Dutch, who made it the capital of the Dutch Coromandel. The British East India Company later captured the town in 1781. </p>
    </body>
</html>


bus.html

<html>
    <head>
        <title>bus stand </title>
    </head>
    <body bgcolor="cyan">
        <h>bus stand</h>
        <p> Nagapattinam Bus stand at Nagapattinam Municipality
is an import bus station because it is connected by two national highways, Nh 45A to Villupuram and Nh 67 to Coimbatore and Gundlupete in Karnataka state , In this Tnstc Corporation runs plenty of buses From velankanni to trichy Via Nagapattinam Bus Stand. </p>
    </body>
</html>


light.html

<html>
    <head>
        <title>light house</title>
    </head>
    <body bgcolor=" orange">
        <h>light house</h>
        <p>The Nagapattinam Lighthouse is a historic landmark located in the coastal town of Nagapattinam, Tamil Nadu, India. It stands tall at approximately 29 meters and serves as a vital navigational aid for ships entering the Bay of Bengal. The lighthouse offers panoramic views of the surrounding coastline and is an important landmark in the region. It was constructed in 1935, replacing an earlier tower that dated back to 1863. </p>
    </body>
</html>

devi.html

<html>
    <head>
        <title>devi cinemas</title>
    </head>
    <body bgcolor="grey">
        <h >devi cinemas</h>
        <p> Devi Cinemas in Nagapattinam is a premier cinema destination known for its state-of-the-art facilities and innovative features. The cinema hall offers a comfortable viewing experience with high-gain screens, advanced audio processors, and comfortable seating </p>
    </body>
</html>
```

## OUTPUT

![alt text](<Screenshot (30).png>)
![alt text](<Screenshot (31).png>)
![alt text](<Screenshot (32).png>)
![alt text](<Screenshot (34).png>)
![alt text](<Screenshot (35).png>)
![alt text](<Screenshot (37).png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.

