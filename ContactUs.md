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
<style>
#titleDIV {
    width: 100%;
    height: 170px;
    background-color: #004d00;
	color: white;
}

#footerDIV {
    width: 100%;
    height: 40px;
    background-color: #004d00;
	color: white;
}
.container {
    position: relative;
    width: 100%;
    max-width: 900px;
}

.container img {
    width: 100%;
    height: auto;
}

.container .btn {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    -ms-transform: translate(-50%, -50%);
    background-color: #555;
    color: white;
    font-size: 16px;
    padding: 12px 24px;
    border: none;
    cursor: pointer;
    border-radius: 5px;
    text-align: center;
}

.container .btn:hover {
    background-color: black;
}
.navbar-nav.navbar-center {
    position: absolute;
    left: 50%;
    transform: translatex(-50%);
}
</style>
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
<div id="titleDIV">
<table width="100%" align="center">
	<tr>
		<td align="center">
			<h1>AO Pest Control</H1>
		</td>
	</tr>
	<tr>
		<td align="center">	
			<h4><i>Your first port of call for unwanted pests</i></h4>
		</td>
	</tr>
	<tr>
		<td align="left">
			<h3>Tel : 07808***757</h3>
		</td>
	</tr>
</table>
</div>

<div align="center">
<nav class="navbar navbar-default">
  <div class="container-fluid">
    <ul class="nav navbar-nav navbar-center">
      <li><a href="readme2">Home</a></li>
      <li><a href="About">About</a></li>
      <li><a href="services">Services</a></li>
      <li><a href="catchment">Catchment Areas/Hours</a></li>
      <li class="active"><a href="ContactUs">Contact</a></li>
    </ul>
  </div>
</nav>
</div>
<!-- **********************************************
**************************************************
-->
<div class="container">
  <h2>Contact Us</h2>
	<table>
		<tr>
			<td>
				<form name="myForm" action="/action_page.php" onsubmit="return validateForm()" method="post">
					<div class="form-group">
					<label for="fname">Name:</label> <input type="text" name="fname"><br>
					<label for="femail">Email:</label> <input type="text" name="femail"><br>
				

					
						<label for="comment">Please enter a brief description of your requirements. I am happy to discuss options and to provide a free, no obligation quote:</label>
						<textarea class="form-control" rows="5" id="comment"></textarea>
					</div>
					<input type="submit" value="Submit">
					<br><br>
				</form>
			</td>
			<td>
				<iframe src="https://www.google.com/maps/embed?pb=!1m14!1m12!1m3!1d75268.88852053697!2d-1.862902110632522!3d53.87571202898417!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!5e0!3m2!1sen!2suk!4v1520697921948" width="300" height="300" frameborder="0" style="border:0" allowfullscreen></iframe>	
			</td>
		</tr>
	</table>
	<br><br>
</div>



<div id="footerDIV">
<table width="90%" align="center">
	<tr>
		<td align="center">
			<h4><i>Call 07808***757 today for a no obligation, free estimate!</i></h4>
		</td>
	</tr>
</table>
</div>

<!-- **********************************************
**************************************************
-->	


</body>
