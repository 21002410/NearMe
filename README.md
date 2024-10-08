# Ex04 Places Around Me


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
        <title>MAP APP</title>
    </head>
    <body>
        <h1 align="center">NELLORE</h1>
        <h2 align="center">RAGALA SAI VIVEK(212223230163)</h2>
        <center>
            <img src="Screenshot 2024-03-21 142007.png" usemap="#image-map">

            <map name="image-map">
                <area target="" alt="Ayyapa Swamy Temple" title="Ayyapa Swamy Temple" href="temple.html" coords="662,557,295,643" shape="rect">
                <area target="" alt="Acer Mall Exclusive Store" title="Acer Mall Exclusive Store" href="acer.html" coords="761,224,82" shape="circle">
                <area target="" alt="Rainbow School" title="Rainbow School" href="school.html" coords="869,726,1010,704,1069,729,1001,757,937,757" shape="poly">
                <area target="" alt="Barshad Dargha" title="Barshad Dargha" href="dargha.html" coords="600,362,97" shape="circle">
                <area target="" alt="Narayana Medical College" title="Narayana Medical College" href="narayana.html" coords="865,394,1042,468" shape="rect">
</center>
</map>
    </body>
</html>
```
```
acer.html

<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="lavender">
        <h1 align="center">
        <font color="gold"><b>nellore</b></font>
        </h1>
        <h3 align="center">
        <font color="blue"><b>acer mall</b></font>
        </h3>
        <hr size="3" color="cyan">
        <p align="justify">
        <font face="Georgia" size="5">
            1)Acer Mall is an online retail platform operated by Acer Inc., a Taiwanese multinational hardware and electronics corporation specializing in advanced electronics technology. Acer Mall serves as a one-stop destination for customers looking to purchase Acer products directly from the manufacturer. The platform offers a wide range of Acer's innovative products, including laptops, desktops, monitors, tablets, smartphones, accessories, and other electronics.<br>
        </font>
        </p>
    </body>
</html>
```
```
temple.html

<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="cyan">
        <h1 align="center">
        <font color="gold"><b>nellore</b></font>
        </h1>
        <h3 align="center">
        <font color="blue"><b>AYAPA SWAMY TEMPLE</b></font>
        </h3>
        <hr size="3" color="cyan">
        <p align="justify">
        <font face="Georgia" size="5">
            1) Ayyapa Swamy Temple is located in, Grand Trunk Road, Auto Nagar, Nellore, Andhra Pradesh 524004.<br>

        </font>
        </p>
    </body>
</html>
```
```
school.html

<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="pink">
        <h1 align="center">
        <font color="gold"><b>nellore</b></font>
        </h1>
        <h3 align="center">
        <font color="blue"><b>RAINBOW SCHOOL </b></font>
        </h3>
        <hr size="3" color="cyan">
        <p align="justify">
        <font face="Georgia" size="5">
           1)Rainbow Scholl is located in Dhanalakshmipuram, to, Kalivelapalem, Nellore, Andhra Pradesh 524003

        </font>
        </p>
    </body>
</html>
```
```
narayana.html

<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="violet">
        <h1 align="center">
        <font color="gold"><b>nellore</b></font>
        </h1>
        <h3 align="center">
        <font color="blue"><b>NARAYANA MEDICAL COLLEGE AND HOSPITALS</b></font>
        </h3>
        <hr size="3" color="cyan">
        <p align="justify">
        <font face="Georgia" size="5">
            1)Narayana Medical COllege is located in Chintareddy Palem, Nellore, Andhra Pradesh 524003.<br>

        </font>
        </p>
    </body>
</html>

```
```
dargha.html
<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="purple">
        <h1 align="center">
        <font color="gold"><b>nellore</b></font>
        </h1>
        <h3 align="center">
        <font color="blue"><b>Barashaidh Dargha </b></font>
        </h3>
        <hr size="3" color="cyan">
        <p align="justify">
        <font face="Georgia" size="5">
            1) The Barashaidh Dargha famous for the annual festival of Rotiyaan ki Eid/Rottela Panduga in the month of Muharram in Hijr.<br>
            2)Bara Shaheed Darga Located in Ambedkar Nagar, Nellore, Andhra Pradesh 524003

        </font>
        </p>
    </body>
</html>

```

## OUTPUT
![Screenshot 2024-09-20 085825](https://github.com/user-attachments/assets/1540ee15-aeda-414d-b77f-05ced876dc01)
![Screenshot (10)](https://github.com/user-attachments/assets/4d37a7b0-b73e-466e-865b-b3ef48709654)
![Screenshot (11)](https://github.com/user-attachments/assets/8729e32c-1181-4caa-a1cc-c04ba406ee4d)
![Screenshot (12)](https://github.com/user-attachments/assets/158b1176-bd31-4411-b8b3-d00a30e3af1c)
![Screenshot (13)](https://github.com/user-attachments/assets/1b77587a-3d88-48d5-a79c-9f34a4b46976)
![Screenshot (14)](https://github.com/user-attachments/assets/1b25fe4f-b145-4b02-88ce-fc916b2c05a0)




## RESULT
The program for implementing image maps using HTML is executed successfully.
