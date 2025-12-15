# Ex04 Places Around Me
# Date:1.12.2025
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
```
map.html

<html>
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="magenta"><b>CHIDAMBARAM</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>SANJAY</b></font>
</h3>
<center>
<map name="MyCity">
<img src="sanj map.jpg" usemap="#image-map">

<map name="image-map">
    <area target="_self" alt="college" title="college" href="college.html" coords="16,66,180,148" shape="rect">
    <area target="_self" alt="temple" title="temple" href="temple.html" coords="493,232,704,294" shape="rect">
    <area target="_self" alt="my home town" title="my home town" href="D:\web\EX4\Image_map\kishore\mapapp\static\mytown.html" coords="546,398,617,441" shape="rect">
    <area target="_self" alt="pichavaram beach" title="pichavaram beach" href="beach.html" coords="995,116,1098,165" shape="rect">
    <area target="_self" alt="mangrove forest" title="mangrove forest" href="forest.html" coords="1079,13,1237,101" shape="rect">
</map>
</map>
</center>
</body>
</html>

beach.html

<html>
<head>
<title>PICHAVARAM BEACH</title>
</head>
<body bgcolor="silver">
<h3 align="center">
<font color="black"><b>PICHAVARAM BEACH</b></font>
</h3>
<hr size="7" color="red">
<p align="justify">
<font face="Georgia" size="10">
Pichavaram beach is a picturesque coastal destination in Tamil Nadu, primarily known as a gateway to the Pichavaram Mangrove Forest, the world's second-largest mangrove ecosystem. While the beach offers sandy shores and clear waters for relaxation, the main attraction is the extensive mangrove forest, which can be explored by boat through its network of canals and islands. Visitors can enjoy boating, birdwatching, and experiencing the unique natural beauty and ecological importance of this mangrove habitat
</body>
</html>

college.html

<html>
<head>
<title>COLLEGE</title>
</head>
<body bgcolor="aqua">
<h3 align="center">
<font color="black"><b>COLLEGE</b></font>
</h3>
<hr size="7" color="red">
<p align="justify">
<font face="Georgia" size="10">
Kamarajar Polytechnic College in Chidambaram was a technical institution offering medical and engineering diploma courses, with facilities including a library, hostel, cafeteria, and labs. However, the college is permanently closed, as indicated by multiple sources. 
</body>
</html>

forest.html

<html>
<head>
<title>MANGROVE FOREST</title>
</head>
<body bgcolor="silver">
<h3 align="center">
<font color="black"><b>MANGROVE FOREST</b></font>
</h3>
<hr size="7" color="red">
<p align="justify">
<font face="Georgia" size="10">
Mangrove forests are coastal, tropical wetlands characterized by salt-tolerant trees and shrubs with specialized root systems that thrive in intertidal zones. They act as vital nurseries for marine life, provide natural protection against storms and erosion, and filter water, making them crucial for both the environment and human communities
</body>
</html>

mytown.html

<html>
<head>
<title>MY HOME TOWN</title>
</head>
<body bgcolor="aqua">
<h3 align="center">
<font color="black"><b>MY HOME TOWN</b></font>
</h3>
<hr size="7" color="red">
<p align="justify">
<font face="Georgia" size="10">
Usuppur is a village panchayat located in the Cuddalore district of Tamil Nadu, near the temple town of Chidambaram. The village is also a designated Census Town, and its population is predominantly Hindu. 
</body>
</html>


temple.html

<html>
<head>
<title>TEMPLE</title>
</head>
<body bgcolor="skyblue">
<h3 align="center">
<font color="black"><b>TEMPLE</b></font>
</h3>
<hr size="7" color="red">
<p align="justify">
<font face="Georgia" size="10">
Thillai Nataraja Temple, also referred as the Chidambaram Nataraja Temple, is a Hindu temple dedicated to Nataraja, the form of Shiva as the lord of dance. This temple is located in Chidambaram, Tamil Nadu, India. This temple has ancient roots and a Shiva shrine existed at the site when the town was known as Thillai.
</html>
```
# OUTPUT
<img width="1920" height="1080" alt="Screenshot (6)" src="https://github.com/user-attachments/assets/4c914a28-4be3-4a8f-ad45-df6a98d8adf2" />
<img width="1920" height="1080" alt="Screenshot (7)" src="https://github.com/user-attachments/assets/27793b1e-e289-4e13-80aa-be2f52e3f640" />
<img width="1920" height="1080" alt="Screenshot (8)" src="https://github.com/user-attachments/assets/c23a99b1-4047-40cc-83d9-57e2a3f03db4" />
<img width="1920" height="1080" alt="Screenshot (9)" src="https://github.com/user-attachments/assets/407a49ef-af21-487f-a21e-9674840583af" />
<img width="1920" height="1080" alt="Screenshot (11)" src="https://github.com/user-attachments/assets/534b7d0f-15ef-4428-a7c4-3d45cc1a33c1" />






# RESULT
The program for implementing image maps using HTML is executed successfully.
