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
Using <map> tag name the map.

### STEP 4
Create clickable regions in the image using <area> tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE

### map.html
```
~
<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <font color="green"><b>Pallikonda</b></font>
        </h1>
        <h3 align="center">
            <font color="orange"><b>SRIDHARSHAN D (212223040205)</b></font>
        </h3>
        <center>
            <img src="map.png" usemap="#MyCity" height="610" width="1450">
            <map name="MyCity">
                <area shape="rect" coords="300,300,900,400" href="home.html" title="My Home Town">
                <area shape="circle" coords="500,200,60" href="temple.html" title="Sri Ranganathar Temple">
                <area shape="rect" coords="50,50,400,400" href="river.html" title="Palar River">
                <area shape="rect" coords="500,500,1328,1691" href="mountain.html" title="Mountain">
            </map>
        </center>
    </body>
</html>
~
```
### home.html
```
~

<html>
    <head>
        <title>
            My Home Town
        </title>
    </head>
    <body bgcolor="orange">
        
            <h1 align="center"><font color="red">PALLIKONDA</font></h1>
            <h4 align="center" font="italic">
            <font color="blue"><h5 align="center" font="algerian"> Panchayat
            </h5></b>
            </font> 
            </h4>
            <hr size="3" color="red">
            <p align="justify">
                <font face="Georgia" size="5">
        

<br>Pallikonda is a selection grade town panchayat in Vellore district in the Indian state of Tamil Nadu. 
<br>It connects with 90 villages and the town of Gudiyatham.
<br>History
Pallikonda hosts a large non-sepulchral megalithic assembly with a vast capstone supported by three equally enormous boulders. The presence of the megalith was officially reported by Col. Congreve of the Madras Regiment in 1845 and was included in the book "Rude Stone Monuments" by J. Fergusson in 1872.[2] The capstone projections are positioned so that they point towards north and south. The surface of the capstone is riddled with more than 75 cupules, built in clusters. Cupules of a large cluster form direct sight-lines to the position of the stars Vega and Capella during solstice sun rise and sunset.[3]

"Uttara Ranganathan" temple beside the Palar river bank has the deity is "Anantashayana", the sleeping form of Vishnu. Since the deity lies north of the river Palar, it is termed as "Uttara" (North).
</font>
</p>
</body>
</html>
~
```
### temple.html
```
~
<html>
    <head>
        <title>
            My Home Town
        </title>
    </head>
    <body bgcolor="gold">
        <h1 align="center"><font color="red">PALLIKONDA</font></h1>
        <h4 align="center" font="italic">
        <font color="blue">  <b>Arulmigu Sri Aranganayagi samedha Sri Uthira Ranganathar Swamy Temple.</b>
        </font> 
        </h4>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" size="5">
        It is 2000 years old temple associated with the history of Sri Varadharaja Perumal Kanchipuram.
<center>
    <img src="Temple1.jpg">
    <br>The main Temple Tower (Rajagopuram)<br>
    <img src="Divine2.jpg">
    <br>The lord Vishnu is in Sayana Thirukolam on Adhishesha(five headed snake). 
</center>
</font>
      </p>
    </body>
</html>
~
```
### river.html
```
~
<html>
    <head>
        <title>
            My Home Town
        </title>
    </head>
    <body bgcolor="skyblue">
        <body bgcolor="gold">
            <h1 align="center"><font color="red">PALLIKONDA</font></h1>
            <h4 align="center" font="italic">
            <font color="blue"><h5 align="center" font="algerian">Palar River -- Water Source
            </h5></b>
            </font> 
            </h4>
            <hr size="3" color="red">
            <p align="justify">
                <font face="Georgia" size="5">
        
        <br>It rises in the Nandi Hills in Chikkaballapura district of Karnataka state
         <br> Flows
          <br>93 kilometres (58 mi) in Karnataka,
          <br> 33 kilometres (21 mi) in Andhra Pradesh and 
          <br>222 kilometres (138 mi) in Tamil Nadu 
          <br>Before reaching its confluence into the Bay of Bengal at Vayalur about 75 kilometres (47 mi) south of Chennai. 
          <br>It flows as an underground river for a long distance only to emerge near Bethamangala town, from where, gathering water and speed, it flows eastward down the Deccan Plateau.
          <br>The Towns of Bethamangala, Santhipuram, Kuppam,Mottur, Ramanaickenpet, Vaniyambadi, Ambur, Melpatti, Gudiyatham, Pallikonda, Anpoondi, Melmonavoor, Vellore, Katpadi, Melvisharam, Arcot, Ranipet, Walajapet, Kanchipuram, Walajabad, Chengalpattu, Kalpakkam, and Lattur are located on the banks of the Palar River.
          <br> Of the seven tributaries,
         <br>the chief tributary is the Cheyyar River.
        <center><img src="palar.jpg"></center>
    </font>
    </p>
    </body>
    </html>
~
```
### mountain.html
```
~
<html>
    <head>
        <title>
            My Home Town
        </title>
    </head>
    
        <body bgcolor="gray">
            <h1 align="center"><font color="red">PALLIKONDA</font></h1>
            <h4 align="center" font="italic">
            <font color="blue"><h5 align="center" font="algerian"> MOUNTAIN && FOREST
            </h5></b>
            </font> 
            </h4>
            <hr size="3" color="red">
            <p align="justify">
                <font face="Georgia" size="5">
        


 <center> <img src="mount.jpg"></center>  
                </font>
                </p>
</body>
</html>
~
```
## OUTPUT
![Screenshot 2024-05-08 203727](https://github.com/Sridharshan23005550/NearMe/assets/149986733/8fcd60ab-9df4-4f72-994f-ffcce2eb8017)

![Screenshot 2024-05-08 203905](https://github.com/Sridharshan23005550/NearMe/assets/149986733/5a8bfb58-7d68-4188-bffb-c0b8d3da3b7c)

![Screenshot 2024-05-08 204218](https://github.com/Sridharshan23005550/NearMe/assets/149986733/88a8602b-0177-4226-ae91-4e912f025eca)

![Screenshot 2024-05-08 204428](https://github.com/Sridharshan23005550/NearMe/assets/149986733/0f614cb1-293e-427e-a0fb-9598c3df5043)

![Screenshot 2024-05-08 204730](https://github.com/Sridharshan23005550/NearMe/assets/149986733/295b35e9-4134-4869-bd1d-c222879dcfd3)

## RESULT
The program for implementing image maps using HTML is executed successfully.
