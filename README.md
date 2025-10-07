# Ex04 Places Around Me
## Date: 07/10/2025

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
```
map.html
<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center" style="color:red">GINGEE</h1>
        <h3 align="center" style="color:red">JANANI D - 25015838</h3>
               
      <img src="map.png" usemap="#image-map">

         <map name="image-map">
              <area target="" alt="gingee fort bridge" title="gingee fort bridge" href="bridge.html" coords="227,274,426,346" shape="rect">
              <area target="" alt="gingee fort way view point" title="gingee fort way view point" href="garden.html" coords="701,471,829,468,867,510,842,537,704,545,677,509" shape="poly">
              <area target="" alt="kamalakanni amman" title="kamalakanni amman" href="temple.html" coords="505,457,112" shape="circle">
              <area target="" alt="shri sivan kovil" title="shri sivan kovil" href="koil.html" coords="708,383,854,449" shape="rect">
              <area target="" alt="elephant pond" title="elephant pond" href="pond.html" coords="1136,467,101" shape="circle">
        </map>  
    </body>
</html>
bridge.html
<html>
    <head>
        <title>Gingee fort bridge</title>
    </head>
    <body bgcolor="red">
        <h1 align="center">
    <front color="yellow"><b>Gingee</b></front>
        </h1>
        <h3 align="center">
            <front color="pink"><b>Gingee fort bridge</b></front>
        </h3>
        <hr size="4" color="pink">
        <p align="justify">
            <front face="Georgia" size="5">The bridge is a wooden draw-bridge that
                 serves as the access point over a natural chasm to the Rajagiri citadel 
                 (the main hill‐fort part of Gingee). The chasm is a deep natural cut / cliff /
                  ravine which forms part of the fortification. To approach the main citadel in times
                   of peace and war, crossing this chasm is necessary.</front>
                  </p>
        </body>
        </html>
    garden.html 
    <html>
    <head>
        <title>Gingee fort viewpoint</title>
    </head>
    <body bgcolor="pink">
        <h1 align="center">
    <front color="yellow"><b>Gingee</b></front>
        </h1>
        <h3 align="center">
            <front color="red"><b>gingee fort viewpoint</b></front>
        </h3>
        <hr size="4" color="pink">
        <p align="justify">
            <front face="Georgia" size="5">Villages and agricultural lands surrounding 
                the fort. The contrast between greenery / fields and rocky fort walls is striking. 
     The fort’s own architecture: the layout of walls, bastions, gates (Pondicherry
     Gate, Arcot Gate), ruins of palaces, granaries, temples, Elephant Tank, and water reservoirs. 
     Other hills in the fort complex — seeing how the three hillocks are positioned relative to each other (looks dramatic from some viewpoints). 
     Distant features like roads, smaller settlements, possibly forest patches depending on direction and visibility. On clear days, the visibility is quite good.</front>
     </p>
     </body>
     </html>
    koil.html
 <html>
    <head>
        <title>shri sivan koil</title>
    </head>
    <body bgcolor="cyan">
        <h1 align="center">
    <front color="red"><b>Gingee</b></front>
        </h1>
        <h3 align="center">
            <front color="blue"><b>shri sivan koil</b></front>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <front face="Georgia" size="5">Since the Sivan Koil you asked about could be inside or near the Gingee Fort,
                 below are details about the fort complex which hosts several temples:
Gingee Fort is in Villupuram district, Tamil Nadu. It’s historically very old, with contributions from 
many dynasties including the Cholas, Kadavas, the Vijayanagar Empire, Nayaks, Marathas, Mughals and colonial powers. 
The fort complex is built over three hillocks: Krishnagiri, Rajagiri (Anandagiri), and Chakilidurg. 
Within the fort, there's a temple dedicated to the goddess Chenjiamman. 
</front>
        </p>
    </body>
    </html>
pond.html
    <html>
    <head>
        <title>elephant pond</title>
        <body bgcolor="lightgreen">
            <h1 align="centre">
                <front color="red"><b>Gingee</b></front>
            </h1>
            <h3 align="center">
                <front color="blue"><b>elephant pond</b></front>
            </h3>       
            <hr size="3" color="red">
            <p align="justify">
                <front face="Georgia" size="5">The Elephant Tank (also called
                     Anaikulam, meaning “Elephant Pond”) is a large water reservoir inside
                      Gingee Fort, situated to the south of the Kalyana Mahal. A Solivagant's 
                      Shoes It’s also called Elephant Tank or Elephant Pond because of 
                      its size and because elephants are said to have used it—for bathing or 
                      other functions. </front>
                
            </p>
    </head>
</html>
temple.html
<html>
    <head>
        <title>kammalakanni amman temple</title>
    </head>
    <body bgcolor="lightblue">
        <h1 align="center">
            <front color="red"><b>Gingee</b></front>
        </h1>
        <h3 align="center">
            <front color="blue"><b>kammalakanni amman temple</b></front>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <front face="Georgia" size="5">
                Local tradition holds that the shrine of Senjiamman / Kamalakanni Amman
                 may precede even the fort itself, with its development tracing back to
                  around 1200 CE, when Ananda Kon, a leader of the Konar community (shepherds), 
                  is said to have established early structures in this region. 
                There is an important festival of 10 days held annually for Kamalakanni Amman. 
                Car (chariot) processions are part of the events. 
               In earlier times, sacrificial practices (buffaloes, animals, even
                human heads in symbolic form in stone reliefs) were associated with the shrine, as noted in colonial‐historical and local accounts, though many of those practices have ceased. 
                Kamalakanni Amman is one of seven virgin guardian goddesses (seven Kannimar) of 
                 local area; in some versions of the legend she is understood to be the same as or closely identified with Senjiamman
            </front>
        </p>
    </body>
</html>

```
## OUTPUT
![alt text](<Screenshot 2025-10-07 085227-1.png>)
![alt text](<Screenshot 2025-10-07 085243.png>)
![alt text](<Screenshot 2025-10-07 090105.png>)
![alt text](<Screenshot 2025-10-07 090935.png>)
![alt text](<Screenshot 2025-10-07 090145.png>)
![alt text](<Screenshot 2025-10-07 085258.png>)
