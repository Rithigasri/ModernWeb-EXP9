# EXPERIMENT 09: CREATE A BIRTHDAY CARD USING HTML AND CSS.
## AIM:
To create a birthday card using html and css.
## ALGORITHM:
1. Create an HTML document with a head and body section.
2. In the head section, set the meta tags for character encoding, compatibility, and viewport.
3. Add a title for the document.
4. Define CSS styles to set the body background image and container background image, as well as positioning and styling for the text and image elements.
5. In the body section, create a container div with nested elements to display the birthday invitation content, including headings, text, and an image.
## PROGRAM:
### bday.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<style>
body
{
    background: url("https://img.freepik.com/free-photo/pink-cloudy-sky_1048-14279.jpg");
    background-repeat: no-repeat;
    background-size: cover;
}
.container {
background:url("bg.jpg") ;
background-position:center;
background-repeat: no-repeat;


}
</style>
<body >
    
    <div class="container">
        <div>
        
            <h1 style="font-family: cursive;text-align: center;padding-top: 180px;color: white;font-size:50px">Save the Date</h1>
            <h2 style="font-family:serif;font-size:40px;text-align: center;color: white">AVERY'S BIRTHDAY</h2>
            <h2 style="font-size: 60px;text-align: center;color:beige;padding-right: 550px">09 APRIL</h2>
            <p style="text-align: center;padding-right: 300px;font-size: 30px;color:cornsilk">At 6 pm o clock | Enclave Garden, Chennai</p>
            <img src="cake.jpg" style="float:right;width:250px;height: 250px;border-radius: 50%;position: absolute;top:350px;left:930px;">
            <p style="font-size:30px;text-align: center;color:plum;padding-bottom: 70px;"><i>My little angel is turning ONE</i><br/>Grace this occasion with your presence and blessing!! </p>
            
        </div>
    </div>
    
    
</body>
</html>
```
## OUTPUT:
![image](https://github.com/Rithigasri/ModernWeb-EXP9/assets/93427256/438b2227-5cb4-4e7d-afd7-81d16356e53f)

## RESULT:
Thus, a birthday card is created using html and css.
