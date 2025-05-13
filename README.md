# Ex.08 Design of Interactive Image Gallery
## Date:17.04.2025

## AIM:
To design a web application for an inteactive image gallery with minimum five images.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for positioning and styling.

### Step 4:
Write JavaScript program for implementing interactivity.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Interactive Image Gallery</title>
</head>
<body>
<header style="text-align: center; background-color: #333; color: whit
<h1>Actor Vijay</h1>
</header>
<div style="white-space: nowrap; overflow-x: auto; padding: 1rem;">
<div style="display: inline-block; margin-right: 10px;" onclick="o
<img src="im1.png" style="height: 200px;">
</div>
<div style="display: inline-block; margin-right: 10px;" onclick="o
<img src="im2.png" style="height: 200px;">
</div>
<div style="display: inline-block; margin-right: 10px;" onclick="o
<img src="im3.png" style="height: 200px;">
</div>
<div style="display: inline-block;" onclick="openModal(this)">
<img src="im4.png" style="height: 200px;">
</div>
</div>
<div id="modal" style="display: none; position: fixed; z-index: 1; lef
<span style="position: absolute; top: 15px; right: 35px; color: wh
<img id="modalImage" style="display: block; margin: 5% auto; max-w
</div>
<script>
function openModal(element) {
var modal = document.getElementById("modal");
 
var modalImg = document.getElementById("modalImage");
modal.style.display = "block";
modalImg.src = element.querySelector("img").src;
}
function closeModal() {
document.getElementById("modal").style.display = "none";
}
</script>
</body>
</html>
```
## OUTPUT:
![image](https://github.com/user-attachments/assets/153f6071-9a97-4b80-a5bb-874ffb3bd946)

![image](https://github.com/user-attachments/assets/43a280cc-6d13-4754-a6cd-67f161c15f86)

## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
