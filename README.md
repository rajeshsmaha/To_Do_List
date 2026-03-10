# Ex03 To-Do List using JavaScript
## Date:10/03/2026

## AIM
To create a To-do Application with all features using JavaScript.

## ALGORITHM
### STEP 1
Build the HTML structure (index.html).

### STEP 2
Style the App (style.css).

### STEP 3
Plan the features the To-Do App should have.

### STEP 4
Create a To-do application using Javascript.

### STEP 5
Add functionalities.

### STEP 6
Test the App.

### STEP 7
Open the HTML file in a browser to check layout and functionality.

### STEP 8
Fix styling issues and refine content placement.

### STEP 9
Deploy the website.

### STEP 10
Upload to GitHub Pages for free hosting.

## PROGRAM
```
<!DOCTYPE html>
<html>
<head>
<title>Project Deadline</title>

<style>

body{
font-family: Arial;
margin:0;
height:100vh;
display:flex;
justify-content:center;
align-items:center;
background: linear-gradient(to right,#8fb3e8,#caa6e8);
}

.container{
background:white;
width:450px;
padding:30px;
border-radius:15px;
box-shadow:0 5px 15px rgba(0,0,0,0.2);
}

h1{
text-align:center;
}

.deadline{
text-align:center;
margin-bottom:20px;
font-size:18px;
}

input{
width:70%;
padding:10px;
border-radius:6px;
border:1px solid #ccc;
}

button{
padding:10px 15px;
background:#3b82f6;
color:white;
border:none;
border-radius:6px;
cursor:pointer;
}

ul{
list-style:none;
padding:0;
margin-top:20px;
}

li{
margin:10px 0;
font-size:16px;
}

</style>

</head>

<body>

<div class="container">

<h1>Project Deadline</h1>

<div class="deadline">
Deadline: 10 March 2026 – 6:00
</div>

<input type="text" id="taskInput" value="Home work">
<button onclick="addTask()">Add Task</button>

<h3>To-Do List</h3>

<ul id="taskList">
<li>Research requirements</li>
<li>Create project plan</li>
<li>Design the UI</li>
<li>Develop core features</li>
<li>Test the application</li>
</ul>

</div>

<script>

function addTask(){

let task = document.getElementById("taskInput").value;

if(task==="") return;

let li = document.createElement("li");
li.textContent = task;

document.getElementById("taskList").appendChild(li);

document.getElementById("taskInput").value="";

}

</script>

</body>
</html>
```


## OUTPUT
<img width="1318" height="870" alt="image" src="https://github.com/user-attachments/assets/7988f4b9-6903-4114-ac9a-f11491bfb69a" />



## RESULT
The program for creating To-do list using JavaScript is executed successfully.
