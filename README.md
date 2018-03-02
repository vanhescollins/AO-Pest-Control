<script>
function validateForm() {
    var x = document.forms["myForm"]["fname"].value;
    if (x == "") {
        alert("Name must be filled out");
        return false;
    }
}
</script>
<script src="js/jsScript.js"></script>

## Welcome to AO Pest Control Website



<h2>Some Tests Below</h2>

<button type="button"
onclick="document.getElementById('demo').innerHTML = Date()">
Click me to display Date and Time.</button>

<p id="demo"></p>

<h2>What Can JavaScript Do?</h2>

<p id="demo2">JavaScript can change HTML content.</p>

<button type="button" onclick='document.getElementById("demo2").innerHTML = "Hello JavaScript!"'>Click Me!</button>

<p>In this case JavaScript changes the src (source) attribute of an image.</p>

<button onclick="document.getElementById('myImage').src='images/pic_bulbon.gif'">Turn on the light</button>

<img id="myImage" src="images/pic_bulboff.gif" style="width:100px">

<button onclick="document.getElementById('myImage').src='images/pic_bulboff.gif'">Turn off the light</button>

<script>
function myFunction() {
    document.getElementById("demo4").innerHTML = "Now the text changed!!!.";
}
</script>
<h1>A Web Page</h1>
<p id="demo4">A Paragraph</p>
<button type="button" onclick="myFunction()">Try it</button>

<h2>External JavaScript</h2>

<p id="demo3">A Paragraph.</p>

<button type="button" onclick="myExternalFunction()">Try this!!</button>

<p>(myExternalFunction is stored in an external file called "jsScript.js")</p>



<p id="TodayDate"></p>

<script>
var d = new Date();
document.getElementById("TodayDate").innerHTML = d.toDateString();
</script>

<form name="myForm" action="/action_page.php"
onsubmit="return validateForm()" method="post">
Name: <input type="text" name="fname">
<input type="submit" value="Submit">
</form>
<br><br>
<a href="page3">Services</a><br>
