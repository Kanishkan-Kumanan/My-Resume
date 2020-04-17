<html>
<head>
<title>Resume</title>
<link rel="stylesheet" type="text/css" href="style4.css">
<link rel="stylesheet" type="text/css" href="https://fonts.googleapis.com/css?family=Open+Sans&display=swap">
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
</head>
<body>
<div class="Personal">
<div class="Left-Col">
<h1>K.KANISHKAN</h1>
<h2>Full Stack Developer</h2>
<p><strong>E-Mail: <a href="#">kanishk.aero@gmail.com</a><br>
   Phone:+91-9003533010</strong><hr>
</p>
<h3><u>SKILLS</u></h3>	
<ul>
	<strong><li>Programming</li>
	<li>Web Development</li>
	<li>Mechanical Design</li></strong>
</ul><hr>
<h3><u>HOBBIES</u></h3>
<ul>
	<strong><li>Listening to Music</li>
	<li>Reading Books</li>
	<li>Playing Keyboard</li></strong>
</ul>
<div class="Symbols">
<ul>
	<li class="Social"><a href="#"><i class="fa fa-facebook-official fa-lg"></i>Facebook</a></li>
	<li><a href="#"><i class="fa fa-twitter fa-lg"></i>Twitter</a></li>
	<li><a href="#"><i class="fa fa-instagram fa-lg"></i>Instagram</a></li>
</ul>	
</div>
</div>
<div class="Right-Col">
<h2><u>ABOUT ME</u></h2>
<p>I am an Aeronautical Engineering graduate with some decent mechanical design and programming skills. I have completed a basic programming course from <strong>CSC Chennai</strong>. I have a one year of industrial experience of mechanical design.Due to my interest in Programming sector,I decided to change my current industry.I am currently undergoing <strong>Full Stack Web Development</strong> training at <strong>GUVI</strong>.</p>
<h2><u>EDUCATION</u></h2>
<table style="width: 100%">
	<tr>
		<th><u>DEGREE</u></th>
		<th><u>INSTITUTION</u></th>
		<th><u>PERCENTAGE</u></th>
	</tr>
	<tr>
		<td>B.E.Aeronautical</td>
		<td>Jeppiaar Engg College</td>
		<td>78.8%</td>		
	</tr>
	<tr>
		<td>HSC</td>
		<td>Sri Sankara Vidhyashramam</td>
		<td>85.7%</td>
	</tr>
	<tr>
		<td>SSLC</td>
		<td>Sri Sankara Vidhyashramam</td>
		<td>95.2%</td>
	</tr>
</table>
<h2><u>EXPERIENCE</u></h2>
<p><strong>Mechanical Design Engineer- FORD MOTORS Chennai</strong><br></p>
<ul>
	<li>Modelling Objects as per point-cloud</li>
	<li>Working with 2D layout of Factories</li>
	<li>Simplification of assets</li>
</ul>
</div>
</div>
</body>
</html>
*{
	margin: 0;
	padding: 0;
	font-family: 'Open Sans',sans-serif;
}

.Personal{
	display: flex;
	width: 100%;
	height: 100%;
	overflow: hidden;
}
.Left-Col{
	flex-basis: 30%;
	background-color: rgba(0,181,204,1);
	height: 100%;
}
.Right-Col{
	flex-basis: 70%;
	height: 100%;
}
.Left-Col h1{
	margin-top: 50px;
	font-size: 40px;
	margin-left: 20px;
	color: rgba(200,55,55,1);
}
.Left-Col h2{
	margin-top: 25px;
	font-size: 20px;
	margin-left: 20px;
	color: rgba(79,51,141,1);
}
.Left-Col p{
	margin-top: 15px;
	margin-left: 20px;
	line-height: 1.6;
}
.Left-Col h3{
	margin-left: 20px;
	margin-top: 20px;
	color: rgba(230,169,45,1);
}
ul
{
	margin-top: 15px;
	margin-left: 30px;
	line-height: 1.6;
	margin-bottom: 15px;
}
.Right-Col h2{
	text-align: left;
	margin-left: 25px;
	margin-top: 20px;
}
.Right-Col p{
	margin-left: 15px;
	margin-top: 25px;
	line-height: 1.6;
}
.Right-Col table{
	border-collapse: collapse;
	margin-top: 15px;
}
.Right-Col table td,th{
	border: 1px solid #dddddd;
	text-align: left;
	padding: 8px;
}
.Symbols ul{
	display: inline-flex;
	list-style: none;
	color:rgba(241,119,151);
}
.Symbols ul li{
	width: 35px;
	padding-left: 15px;
	padding-right: 25px;
	margin: 10px;
}
.Symbols ul li a{
	text-decoration: none;
	color: #fff;
}
.Social{
	padding-right: 20px;
}
