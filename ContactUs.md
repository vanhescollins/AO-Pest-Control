## Contact Us
<head>
<link href="/css/bootstrap.min.css" rel="stylesheet">
		<link href="/style.css" rel="stylesheet" type="text/css"> 
		<script src="/js/jquery.min.js"></script>
		<script src="/js/bootstrap.min.js"></script>
		<link rel="stylesheet" type="text/css" href="/css/dataTables.bootstrap.min.css">
		<link rel="stylesheet" type="text/css" href="/css/datepicker.css">
		<script type="text/javascript" language="javascript" src="/js/jquery.dataTables.min.js"></script>
		<script type="text/javascript" language="javascript" src="/js/dataTables.bootstrap.min.js">	</script>
		<script type="text/javascript" language="javascript" src="/js/bootstrap-checkbox.min.js"></script>
		<script type="text/javascript" language="javascript" src="/js/bootstrap-datepicker.js"></script>
<script>
function validateForm() {
    var x = document.forms["myForm"]["fname"].value;
    if (x == "") {
        alert("Name must be filled out");
        return false;
    }
}
</script>
</head>
<body>
<nav class="navbar navbar-default">
  <div class="container-fluid">
    <ul class="nav navbar-nav">
      <li><a href="readme2">Home</a></li>
      <li><a href="About">About</a></li>
      <li><a href="services">Services</a></li>
      <li class="active><a href="ContactUs">Contact</a></li>
    </ul>
  </div>
</nav>
<h1>Contact Us</h1>
<form name="myForm" action="/action_page.php"
onsubmit="return validateForm()" method="post">
Name: <input type="text" name="fname">
<input type="submit" value="Submit">
    
<br><br>

<a href="/AO-Pest-Control/">Back to Home</a><br>
<a href="About">About Us</a><br>
<a href="services">Services</a><br>
<a href="ContactUs">Contact Us</a><br>
</form>
