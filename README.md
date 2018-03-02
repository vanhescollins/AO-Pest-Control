<script>
function validateForm() {
    var x = document.forms["myForm"]["fname"].value;
    if (x == "") {
        alert("Name must be filled out");
        return false;
    }
}
</script>

## Welcome to my cars website

You can use the [editor on GitHub](https://github.com/vanhescollins/car/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/vanhescollins/car/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

<h2>My First JavaScript</h2>

<button type="button"
onclick="document.getElementById('demo').innerHTML = Date()">
Click me to display Date and Time.</button>

<p id="demo"></p>

<h2>What Can JavaScript Do?</h2>

<p id="demo2">JavaScript can change HTML content.</p>

<button type="button" onclick='document.getElementById("demo2").innerHTML = "Hello JavaScript!"'>Click Me!</button>

<p>In this case JavaScript changes the src (source) attribute of an image.</p>

<button onclick="document.getElementById('myImage').src='images/pic_bulbon.gif'">Turn on the light</button>

<img id="myImage" src="pic_bulboff.gif" style="width:100px">

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

<button type="button" onclick="myExternalFunction()">Try it</button>

<p>(myExternalFunction is stored in an external file called "jsScript.js")</p>

<script src="jsScript.js"></script>

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
<a href="page2.html">Page2</a>
