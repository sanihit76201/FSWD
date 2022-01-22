
# FSWD

## MongoDB : Document database – used by your back-end application to store its data as JSON (JavaScript Object Notation) documents
## Express (sometimes referred to as Express.js): Back-end web application framework running on top of Node.js
## Angular (formerly Angular.js): Front-end web app framework; runs your JavaScript code in the user's browser, allowing your application UI to be dynamic
## Node.js : JavaScript runtime environment – lets you implement your application back-end in JavaScript

Install The follwing software: <br/>

Visual Studio Code https://code.visualstudio.com/ <br>
git - Installation guide https://git-scm.com/ <br/>
node.js - Download page https://nodejs.org/en/ <br/>
mongodb https://www.mongodb.com/try/download/community <br/>

## Configure git and connect to github
Step 1: install git <br>
Step 2: run the following commands in your command prompt<br>
       - git clone https://github.com/{username}/FSWD.git <br>
       - git config --global user.name "{username}" <br>
       - git config --global user.email "MY_NAME@example.com" <br>
       - git pull origin main <br>
       - git add . <br>
       - git commit -m " Your message" <br>
       - git push origin main<br>
Step 3 open Your git hub repository and see the changes


## Introduction to HTML5 
### video elemets

step 1: open visual studio code <br> 

step 2: write code for video elemets  [video.html] <br>

step 3: run the file using browser <br>

### Audio elemets

step 1: open visual studio code <br> 

step 2: write code for audio elemets  [audio.html] <br>

step 3: run the file using browser <br>

### Canvas

HTML canvas tag is used to draw graphics, on the fly, via JavaScript <br>
1. Colors, Styles, and Shadows
2. Line Styles
3. Rectangles
4. Paths
5. Transformations
6. Text
7. Image Drawing
8. Image Drawing

write code(canvas.html) for above using canvas methods 

### SVG (Scalable Vector Graphics)

HTML svg element is a container for SVG graphics.
1. SVG Circle
2. SVG Rectangle
3. SVG Rounded Rectangle
4. SVG Star
5. SVG Logo

 write code(SVG.html) for above using svg 
 
 ### Web Storage
 
 With web storage, web applications can store data locally within the user's browser.<br>
#### web storage provides two objects for storing data on the browser

1. window.localStorage - stores data with no expiration date
2. window.sessionStorage - stores data for one session (data is lost when the browser tab is closed)

write code(localStorage.html) for above using localStorage <br>
write code(sessionStorage.html) for above using sessionStorage

## Drag & Drop

Drag and drop is a very common feature. It is when you "grab" an object and drag it to a different location.

div id="div1" ondrop="drop(event)" ondragover="allowDrop(event)" <br>
img id="drag1" src="logo.jpg" draggable="true" ondragstart="drag(event)" width="336" height="69" <br>

write code (drag_drop.html) to drag logo to div <br>

## Geo Location.
HTML Geolocation API is used to locate a user's position <br>

Check if Geolocation is supported <br>
-If supported, run the getCurrentPosition() method. If not, display a message to the user <br>
-If the getCurrentPosition() method is successful, it returns a coordinates object to the function specified in the parameter (showPosition)<br>
-The showPosition() function outputs the Latitude and Longitude<br>

write code (location.html) to print lattitude and longitude <br>


