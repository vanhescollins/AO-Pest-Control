## Services Offered
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
<div class="col-md-8">
		<div class="panel panel-info">
			<div class="panel-heading">
				<div align="left">
					<b>Intro to services</b><br>
					<img src="images/NoBugs.png" alt="Rat man"><br><br>
					<img src="images/bugs.png" alt="Rat man"><br><br>
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
<form name="myForm" action="/action_page.php"
onsubmit="return validateForm()" method="post">
Name: <input type="text" name="fname">
<input type="submit" value="Submit">
    
    <p>Below is link to home</p>

<a href="/AO-Pest-Control/">Back to Home</a><br>
</form>
