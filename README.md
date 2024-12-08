# Ex04 Places Around Me
## Date: 08.12.2024

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

## CODE:

'''
map.html
<html>
<head>
<title>My HomeTown</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Krishnagiri</b></font>
</h1>
<h2 align="center">
<font color="blue"><b>R.Mushafina (24008061)</b></font>
</h2>
<img src="Screenshot 2024-12-05 113720.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Krishnagiri District Court" title="Krishnagiri District Court" href="court.html" coords="684,375,42" shape="circle">
    <area target="" alt="MGR Nagar" title="MGR Nagar" href="mgrnagar.html" coords="799,526,897,560" shape="rect">
    <area target="" alt="Cambridge School " title="Cambridge School " href="cambridge.html" coords="711,668,63" shape="circle">
    <area target="" alt="Krishnagiri Sports Development Society" title="Krishnagiri Sports Development Society" href="sports.html" coords="743,209,36" shape="circle">
    <area target="" alt="Sri Kattu Veera Anjaneya Temple" title="Sri Kattu Veera Anjaneya Temple" href="temple.html" coords="1126,688,1206,752" shape="rect">
</map>
</body>
</html>

temple.html
<html>
<head>
<title>MY HOME TOWN</title>
</head>
<body bgcolor="white">
<h1 align="center">
<font color="DarkSlateBlue"><b>KRISHNAGIRI</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Sri Kattu Veera Anjaneya Temple</b></font>
</h3>
<p align="justify">
<front face="Georgia" size="S">
The Sri Kattu Veera Anjaneya Temple in Krishnagiri is a revered spiritual destination dedicated to Lord Hanuman. Known for its serene ambiance and architectural beauty, the temple attracts devotees seeking blessings, strength, and spiritual solace. It holds cultural and religious significance, drawing visitors not only from Krishnagiri but also from neighboring regions.

The temple is a center for various religious rituals, festivals, and community gatherings, making it an integral part of the local spiritual landscape. Devotees often visit to offer prayers and participate in special ceremonies that celebrate the virtues of Lord Hanuman, including devotion, courage, and humility.
</p>
</body>
</html>

sports.html
<html>
<head>
<title>MY HOME TOWN</title>
</head>
<body bgcolor="white">
<h1 align="center">
<font color="DarkSlateBlue"><b>KRISHNAGIRI</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Krishnagiri Sports Development Society</b></font>
</h3>
<p align="justify">
    <front face="Georgia" size="S">
    The Krishnagiri Sports Development Society is an organization committed to promoting sports and physical activities in the Krishnagiri district of Tamil Nadu. It aims to nurture local talent, encourage participation in various sports, and create awareness about the importance of fitness and well-being.

    The society organizes training programs, competitions, and events to engage athletes of all age groups and skill levels. By collaborating with schools, colleges, and community organizations, it works to build a strong sports culture in the region. The Krishnagiri Sports Development Society is instrumental in identifying potential athletes and providing them with the necessary resources and support to excel in their respective fields.
    <p>
</body>
</html>

cambridge.html
<html>
<head>
<title>MY HOME TOWN</title>
</head>
<body bgcolor="white">
<h1 align="center">
<font color="DarkSlateBlue"><b>KRISHNAGIRI</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Cambridge School</b></font>
</h3>
<p align="justify">
    <front face="Georgia" size="S">
    Cambridge School in Krishnagiri is a well-established educational institution dedicated to providing quality education to students. Known for its holistic approach to learning, the school emphasizes academic excellence, extracurricular activities, and character development. It offers a nurturing environment that fosters creativity, critical thinking, and a passion for learning.

    The school is equipped with modern facilities and resources to support effective teaching and learning. With a curriculum designed to cater to diverse learning needs, Cambridge School prepares students to excel in academics while instilling values that help them become responsible citizens. It is recognized for its experienced faculty and commitment to shaping well-rounded individuals.
    <p>
</body>
</html>

mgrnagar.html
<html>
<head>
<title>MY HOME TOWN</title>
</head>
<body bgcolor="white">
<h1 align="center">
<font color="DarkSlateBlue"><b>KRISHNAGIRI</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>MGR Nagar</b></font>
</h3>
<hr size="3" color="#FF8C00">
<p align="justify">
<front face="Georgia" size="S">
MGR Nagar is a residential area located in Krishnagiri, a district in the state of Tamil Nadu, India. Known for its peaceful environment and proximity to key facilities, MGR Nagar is a developing locality that caters to the needs of both families and working professionals.
<p>
</body>
</html>

court.html
<html>
<head>
<title>MY HOME TOWN</title>
</head>
<body bgcolor="white">
<h1 align="center">
<font color="DarkSlateBlue"><b>KRISHNAGIRI</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Krishnagiri District Court</b></font>
</h3>
<p align="justify">
    <front face="Georgia" size="S">
    The Krishnagiri District Court is the primary judicial authority for the Krishnagiri district in Tamil Nadu, India. Located in Krishnagiri town, it serves as an important institution for the administration of justice and resolution of legal disputes within the district. The court operates under the jurisdiction of the Madras High Court and handles a variety of cases, including civil, criminal, and family matters.

    It plays a crucial role in maintaining law and order and ensures access to justice for all residents of the district. The court complex is equipped with facilities for judges, lawyers, and the public, making it a hub for legal proceedings and related activities in the region. It also supports modern judicial practices through digital initiatives and legal aid services, reflecting its commitment to efficient and transparent justice delivery.
    <p>
</body>
</html>
'''


## OUTPUT
![alt text](image.png)
![alt text](image-2.png)
![alt text](image-3.png)
![alt text](image-4.png)
![alt text](image-5.png)








## RESULT
The program for implementing image maps using HTML is executed successfully.
