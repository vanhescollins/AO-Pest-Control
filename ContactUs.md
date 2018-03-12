<head>
<link href="/css/bootstrap.min.css" rel="stylesheet">
	<link href="/style.css" rel="stylesheet" type="text/css"> 
	<script src="/js/jquery.min.js"></script>
	<script src="/js/bootstrap.min.js"></script>
	<link rel="stylesheet" type="text/css" href="/css/dataTables.bootstrap.min.css">
	<link rel="stylesheet" type="text/css" href="/css/datepicker.css">
	<script src="/js/jquery.dataTables.min.js"></script>
	<script src="/js/dataTables.bootstrap.min.js">	</script>
	<script src="/js/bootstrap-checkbox.min.js"></script>
	<script src="/js/bootstrap-datepicker.js"></script>
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
	<div align="center">
		<h1>AO Pest Control</H1>
		<br>	
		<h4><i>Your first port of call for unwanted pests</i></h4>
	</div>
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
	
	<br><br>
</div>



<div id="footerDIV">

			<h4><i>Call 07808***757 today for a no obligation, free estimate!</i></h4>
		
</div>

<!-- **********************************************
**************************************************
-->	


</body>
