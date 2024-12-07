# Ex04 Places Around Me
# Date:19/11/2024
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
Image Map:
```
<html>
    <head>
        <title> Imagemap</title>
        <style>
            h1,h2{
                font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            }
            .center{
                  text-align: center;
            }
        </style>
    </head>
    <body>
        <div style="text-align: center;">
        <h1> My Landmarks</h1>
        <h2> click the place to know more about it</h2>
        
        <map>
            <div style="text-align: center;">
           
            <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-07 203207.png"  usemap="#Mapnew" class="center" >
            </div>
            <Map name="Mapnew">
                <area shape="rect" coords="1153,65,1900,681" href="c:\Users\admin\tt\HTML Codes\Sri ramachandra college.html">
                <area shape="rect" coords="148,258,349,329" href="c:\Users\admin\tt\HTML Codes\Prestige Bella Vista.html">
                <area shape="rect" coords="258,333,490,392" href="c:\Users\admin\tt\HTML Codes\MMS Hospital.html">
                <area shape="rect" coords="486,444,733,566" href="c:\Users\admin\tt\HTML Codes\Iyyapanthangal Bus Depot.html">
        </map>
    </div>
   
    </body>
</html>
```
Sri ramachandra College:
```
<html>
   <head>
       <title> Sri Ramachandra College</title>
       
   </head>
   <body>
       <h1 style="text-align: center;"> Sri Ramachandra College</h1>
       <h2 style="text-align: center;"><a href="https://maps.app.goo.gl/Ao6pzFC9KkoVd9Qj9" title="Sri Ramachandra College"> Locations </a></h2>
       <div style="text-align: center;">
       <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-07 195201.png" width="30%" height="30%" >
       <h2> Sri Ramachandra Institute of Higher Education and Research (SRIHER), formerly Sri Ramachandra University and Sri Ramachandra Medical College and Research Institute, is a private institute located in Porur, Chennai, India.[1] SRIHER consists of nine constituent colleges and faculties[2] with more than 6,000 students.[1] SRIHER was founded by Sri Ramachandra Education & Health Trust on September 11, 1985, by N. P. V. Ramasamy Udayar. It was founded as a medical college, and awarded the deemed-to-be-university status in September 1994.The National Institutional Ranking Framework (NIRF) ranked Sri Ramachandra Institute of Higher Education and Research 96 overall in India in 2024, 10th in Dental Category, 55 among universities, 20 in the medical ranking, and 31 in the pharmacy ranking.[10] It was ranked 1 among among private health science university in India in 2022 by India Today. </h2>
       
   
      </div>
      
   </body>
</html>
```
Prestige Bella Vista:
```
<html>
   <head>
       <title>Prestige Bella Vista</title>
       
   </head>
   <body>
       <h1 style="text-align: center;"> Prestige Bella Vista</h1>
       <h2 style="text-align: center;"><a href="https://maps.app.goo.gl/xqAeFothTXFQDB4v7" title="Prestige Bella Vista"> Locations</a></h2>
       <div style="text-align: center;">
       <img src="file:///C:/Users/admin/Pictures/Screenshots/PrestigeBellaVista.png" width="30%" height="30%" >
       <h2> The Prestige Group marks its foray into the Chennai Residential Market, with its newest development – Prestige Bella Vista. Located on Mount Poonamallee Road, Porur – Bella Vista is touted to be one of Chennai’s most lavish and serene Residential Developments. Spread across 25.18 acres, Prestige Bella Vista offers a tranquil green recluse for compact and relaxed urban living. This development comprises of 2613 Residences that include 1, 2, 3 & 4 bedroom units that have been designed to suit the most exclusive urban living standards, created through a network of soothing water bodies and gardens. </h2>
       
   
      </div>
      
   </body>
</html>
```
MMS Hospital:
```
<html>
   <head>
       <title>MMS Hospital</title>
       
   </head>
   <body>
       <h1 style="text-align: center;"> MMS Hospital </h1>
       <h2 style="text-align: center;"><a href="https://maps.app.goo.gl/hPRG3sZwaQr2iTod7" title="MMS Hospital">Locations</a></h2>
       <div style="text-align: center;">
       <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-07 201613.png" width="30%" height="30%" >
       <h2>Mahalakshmi Multispeciality Hospital is a leading, cost-effective healthcare facility located in Porur Iyyapanthangal, Poonamalle, providing comprehensive care 24/7. Designed to offer all the benefits of a large hospital in a more patient-friendly environment, we ensure a hassle-free experience with easy admission and discharge processes. Our hospital boasts a capacity of over 50 beds, including 12 ICU beds, and combines world-class medical services with top-notch healthcare management practices.


        We offer exceptional care across various specialties, including Orthopaedics, Obstetrics, IVF, Plastic Surgery, Trauma, and General Medicine, available around the clock. Our advanced infrastructure features laminar flow operation theatres, a Cardiac Cath Lab, and state-of-the-art radiology and laboratory services, ensuring patients receive the best possible treatment. The hospital spans 12,000 square feet and includes two modular operation theatres, a rehabilitation unit, and an in-house pharmacy. </h2>
       
   
      </div>
      
   </body>
</html>
```
Iyyapanthangal Bus Depot:
```
<html>
   <head>
       <title>Iyyapanthangal Bus Depot</title>
       
   </head>
   <body>
       <h1 style="text-align: center;"> Iyyapanthangal Bus Depot </h1>
       <h2 style="text-align: center;"><a href="https://maps.app.goo.gl/hYdv2fpT12f32ySa9" title="MMS Hospital">Locations</a></h2>
       <div style="text-align: center;">
       <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-07 201924.png" width="30%" height="30%" >
       <h2>The six-acre Iyyappanthangal bus terminus was opened in 1994.[1] It operates 162 buses[2] to places such as Koyambedu, Tambaram, Kundrathur, Sommangalam, Kovalam, Sunguvachattiram, Parrys Corner, Anna Salai, Tambaram, T Nagar and Mint. About 150,000 commuters take buses from here daily.The state highways department undertook renovation of the terminus at a cost of ₹ 4.1 million in March 2010. The work to lay the concrete floor within the terminus area has begun. Among the 25 MTC depots, this is the first terminus to be taken up for renovation. The renovation includes construction of a compound wall, replacement of old lights, creating concrete parking areas for buses, installation of electronic sign boards, and raising the level of the terminus 1.5 feet above the height of Mount-Poonamallee High Road to prevent waterlogging during the monsoon. Facilities for toilets and drinking water for both passengers and MTC staff was also planned. Iyyappanthangal Bus Depot was one of the top most collection in revenue in Chennai in 2000s.</h2>
       
   
      </div>
      
   </body>
</html>
```
     
# OUTPUT

![alt text](<Screenshot 2024-12-07 210847-1.png>)

![alt text](<Screenshot 2024-12-07 211001.png>)

![alt text](<Screenshot 2024-12-07 210905.png>)

![alt text](<Screenshot 2024-12-07 210925.png>)

![alt text](<Screenshot 2024-12-07 210944.png>)

# RESULT
The program for implementing image maps using HTML is executed successfully.
