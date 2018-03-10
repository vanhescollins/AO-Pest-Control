## About Us
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
      <li class="active"><a href="About">About</a></li>
      <li><a href="services">Services</a></li>
      <li><a href="ContactUs">Contact</a></li>
    </ul>
  </div>
</nav>
<div class="col-md-8">
		<div class="panel panel-info">
			<div class="panel-heading">
				<div align="left">
					<b>About Us</b>
				</div>
			</div>
			       
			<table class="table custom">
				<thead class="blue-grey lighten-4 customtableheader">
					<tr>  
					   <th>Service</th> 
					   <th>Service Code</th> 
					   <th>Description</th> 
					   <th>Cost</th> 
					   <th></th> 
				  </tr>
				</thead>
				<tbody>
                <tr> 
						<td>Service details</td> 
						<td>Code details</td> 
						<td>Descr details</td> 
						<td>Cost details</td> 
						<td>Other details</td> 
                </tr>
				</tbody>
			</table>
			
		</div>
	</div>
<br><br>

<a href="/AO-Pest-Control/">Back to Home</a><br>
<a href="About">About</a><br>
<a href="services">Services</a><br>
<a href="ContactUs">Contact Us</a><br>
