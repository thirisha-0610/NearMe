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

 <!DOCTYPE html>
 
 <html lang="en">
  
 <head>
  
    <meta charset="UTF-8">
    
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <title>ImageMap</title>
    
 </head>
 
 <style>
  
    *{margin: 0;}
  
 </style>
 
 <script>
  
    function coordinate(event)
     
    {
     
        let x = event.clientX;
     
        let y = event.clientY;
     
        document.getElementById("text1").value=x;
     
        document.getElementById("text2").value=y;
     
    }
  
 </script>
 
 <body>
  
    <IMG src="Map.png" width="100%" height="500" usemap="#MapNew" onmousemove="coordin
    
        <MAP name="MapNew">
        
           <AREA shape="RECT" coords="643,196,631,147" href="https://www.saveetha.ac.i
           
           <AREA shape="RECT" coords="556,253,552,209" href="https://kingsedu.ac.in/" 
           
           <AREA shape="RECT" coords="903,118,918,150" href="https://srmeaswari.ac.in/
           
           <AREA shape="RECT" coords="960,380,947,330" href="https://sairam.edu.in/" t
           
           <AREA shape="RECT" coords="1032,162,1030,112" href="https://msec.edu.in/" t
           
           <AREA shape="RECT" coords="595,304,600,267" href="https://www.citchennai.ed
           
        </MAP>
        
        <br>
        
        X-coordinate
        
            <input type="text" id="text1">
            
        Y-coordinate 
        
            <input type="text" id="text2">
            
 </body>
 
 </html>

## OUTPUT

 ![Screenshot 2024-04-17 133532](https://github.com/thirisha-0610/NearMe/assets/149347494/5d2007cf-3ed6-4511-b272-f6bf27e4db23)

![Screenshot 2024-04-17 133713](https://github.com/thirisha-0610/NearMe/assets/149347494/45a6b370-6648-46a5-ab05-11e7ffe39296)

![Screenshot 2024-04-17 133639](https://github.com/thirisha-0610/NearMe/assets/149347494/36b2278c-8768-4550-b670-2ed8c79e8fda)

![Screenshot 2024-04-17 133818](https://github.com/thirisha-0610/NearMe/assets/149347494/29de290b-a2a2-41f5-8713-57d47c2dba9f)

![Screenshot 2024-04-17 133903](https://github.com/thirisha-0610/NearMe/assets/149347494/23869094-d1e1-4c2f-bfe3-ae008e68c01b)

![Screenshot 2024-04-17 133934](https://github.com/thirisha-0610/NearMe/assets/149347494/664d8529-af35-4e35-8236-80084227895d)


## RESULT
The program for implementing image maps using HTML is executed successfully.
