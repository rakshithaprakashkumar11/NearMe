# Ex04 Places Around Me
## Date: 

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
"""

   <html>
   
    <head>
        <title> My City</title>
    </head>
    <body>
        <h1 align="center"> 
        <font color="red"><b> Gingee</b></font>
        </h1>
        <h3 align="center">
        <font color="blue"><b>RAKSHITHA(212223220083)</b></font>
        </h3>
        <center>
        <img src="map.jpeg" usemap="#MyCity" height="610" width="1450">
        <map name="MyCity">
        <area shape="circle" coords="700,250,850,400" href="home.html" title="My Home Town">
        <area shape="circle" coords="570,230,45" href="school.html" title="My School">
        <area shape="circle" coords="640,200,30" href="ground.html" title="Ground">
        <area shape="circle" coords="1120,360,25" href="church.html" title="Church">
        </center>
        </map>
    </body>
</html>

"""


## OUTPUT
![Screenshot 2024-04-10 144022](https://github.com/rakshithaprakashkumar11/NearMe/assets/150994181/55c15930-6b0a-4388-80d3-ece2a2a20274)
![Screenshot 2024-04-10 144022](https://github.com/rakshithaprakashkumar11/NearMe/assets/150994181/8600255b-b17a-49ac-8673-1d86c5df81b4)
![Screenshot 2024-04-10 144022](https://github.com/rakshithaprakashkumar11/NearMe/assets/150994181/696d4985-069b-4f4d-833c-819d294bbe48)
![Screenshot 2024-04-10 144022](https://github.com/rakshithaprakashkumar11/NearMe/assets/150994181/07dc5222-02e5-4374-9c61-bf0bc19b59d9)



## RESULT
The program for implementing image maps using HTML is executed successfully.
