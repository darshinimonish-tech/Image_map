# Ex04 Places Around Me
# Date:3.10.2025
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
        <title>CHENNAI MAP</title>
    </head>
<body>
    <b><h1 align="center">CHENNAI MAP-DARSHINI(25017318)</h1></b>



<img src="map.jpg" usemap="#image-map" height="680px" width="1500px">

<map name="image-map">
    <area target="" alt="Jawaharlal Nehru stadium" title="Jawaharlal Nehru stadium" href="stadium.html" coords="525,219,715,284" shape="rect">
    <area target="" alt="Chennai Park" title="Chennai Park" href="park.html" coords="667,404,599,431,609,483,739,497,768,404" shape="poly">
    <area target="" alt="Kandhakottam Temple" title="Kandhakottam Temple" href="temple.html" coords="891,192,1140,261" shape="rect">
    <area target="" alt="Saravana Stores" title="Saravana Stores" href="store.html" coords="66,226,101" shape="circle">
    <area target="" alt="Secretariat Park" title="Secretariat Park" href="Secretariat.html" coords="1207,426,1412,515" shape="rect">
</map>
</body>
</html>
park.html
<html>
    <head>
        <title>park</title>
    </head>
    <body bgcolor="lime">
        <b><h1 align="center">CHENNAI PARK</h1></b>
        <hr>
       <b><p>Chennai has several notable parks, including the unique urban national park, Guindy National Park, known for its wildlife and blackbuck population, and the historic People's Park, which dates back to the mid-19th century. 
            Other parks like Anna Nagar Tower Park offer recreational facilities and architectural features, while newer developments like Kalaignar Centenary Park aim to provide diverse urban green spaces for relaxation and activities.
             The city's parks, from expansive urban forests to well-maintained community spaces, serve as vital ecological and recreational areas within the metropolitan landscape.
       </b> 
        </p>  

    </body>
</html>
secretariat.html
<html>
    <head>
        <title>secretariat park</title>
   </head>
   <body bgcolor="green">
    <b><h1 align="center">SECRETARIAT PARK</h1></b>
    <hr>
   <b><p>Secretariat Park in Chennai is an urban green space situated opposite Fort St. George and near the Chennai Port, offering a tranquil retreat with walking paths, a central fountain, a tree court with benches, and a sunken children's play area. 
        Inaugurated in 2009, this 18.5-acre park features accessible walkways, artistic murals, and granite plazas, making it a popular spot for relaxation, picnics, and community gatherings amidst the city's vibrant environment.
   </b>  
    </p>
   </body>
</html>
stadium.html
<html>
    <head>
        <title>stadium</title>
    </head>
    <body bgcolor="hotpink">
       <b><h1 align="center">JAWAHARLAL NEHRU STADIUM</h1></b>
       <hr>
        <b><p>The Jawaharlal Nehru Stadium in Chennai is a large, multi-purpose sports complex, also known as the Marina Arena, with a capacity of 40,000 for football and athletics, and an 8,000-seat indoor stadium for various indoor games, concerts, and events. 
            Named after India's first Prime Minister, it hosts the Indian Super League football team Chennaiyin FC, the Tamil Nadu football team, and the Pro Kabaddi League team Tamil Thalaivas, making it a vital sports and event venue in the city.
        </b>  
</p>
    </body>
</html>
store.html
<html>
    <head>
    <title>stores</title>
    </head>
    <body bgcolor="aqua">
        <b><h1 align="center">SARAVANA STORE</h1></b>
        <hr>
        <b><p>Super Saravana Stores in Purasaiwakkam is a one-stop-shop for all household needs, offering a wide range of products from groceries to clothing and home appliances. 
            The store features multiple floors with escalator facilities, trial rooms, parking options, and restrooms.
        </b>
             </p>
    </body>
</html>
temple.html
<html>
    <head>
        <title>Temple</title>
    </head>
    <body bgcolor="brown">
        <b><h1 align="center">TEMPLE</h1></b>
        <hr>
       <b><p>Kandaswami Temple, also known as Kandhakottam, is a prominent Hindu temple in Chennai's George Town neighborhood dedicated to Lord Murugan.
             This historical and architectural marvel features traditional Dravidian style and houses the presiding deity, Mutthu Kumāra Swāmi, along with his consorts Valli and Deivayanai. 
             The temple is managed by the Tamil Nadu Hindu Religious and Charitable Endowments Department and is a significant cultural site known for its musical and dance institutions and the temple tank, Saravana Poigai.
       </b>  
</p>

    </body>
</html>



```




# OUTPUT
![alt text](<Screenshot (17).png>)
![alt text](<Screenshot (21).png>)
![alt text](<Screenshot (20).png>)
![alt text](<Screenshot (18).png>)
![alt text](<Screenshot 2025-10-03 113311.png>)
![alt text](<Screenshot (19).png>)



# RESULT
The program for implementing image maps using HTML is executed successfully.
