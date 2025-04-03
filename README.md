<!DOCTYPE html>
<head>
<style>
body {
font-family: tahoma;
text-align: center;
}
header {
letter-spacing: 6px;
colour: white;
backgroud: royalblue;
padding: 20px;
}
h2 {
font-size: 2em;
width: 100%;
}
section {
padding; 30px;
margin-bottom: 40px;
}
td {
padding: 10px;
}
table {
margin: auto;
}
#my-order {
background-color: #29C1C4
padding: 25px;
display: none;
}
.container {
display-content: flex;
justify-content: center;
flex-wrap: wrap;
}

.cards {
boader: 10px solid #ccc;
background-color: ivory;
margin: 25px;
padding; 25px;
box-shadow: 6px 6px 6px rgba(0,0,0,0.3);
}

.icons { 
font-size: 8em;
padding: 25px 
}

button, .button {
background: royalblue;
border: 0;
colour: white;
padding: 10px;
width: 70%;
margin-bottom: 10px;
}

.blue {
background: teal;
}

.footer {
padding: 30px;
bckground: grey;
}

.circle {
color: white;
font-size: 2.5em;
display: inline-block;
height: 40px;
margin: 15px;
width: 40px;
border-radius: 50%;
background: deeppink;
padding: 5px 10px 15px 10px;
font-family: helvetica;
}
</style>
</head>
<body> 
<header>
<h1>
i-DINEO LOGISTICS 
</h1>
<h4>
Deliver your parcel
</h4>
<br>
<h2>Welcome</h2>
</header>
<section class="blue container" style=background-color:white;">
<h2>
OUR SERVICES://
</h2>
<article class="card"> 
<div class="icon"> &#9749;</div>
<h3> Dineo Diseko</h3>
<p>Founder -Provides constant input to team members and offer clients fast abd simple websites.<p/>
<button>Learn More</button>
</article>
</article class="card">
<div class="icon"> &#9734;</div>
<h3> Dineo Dineo</h3>
<p>Jnr. Web Developer - Creates beautiful websites for businesses in Potch.</>
<button>Learn More</button>
 </articles>
</section>
<section> 
</div>
<script>
function placeOrder(){
results = "<h3>Success</h3> Here is your order.";
results +=<br>Name: " + orderForm.elements["my-name"].value;
results +=<br>Address: " + orderForm.elements["my-address"].value;
results +=<br>I like to order: " + oder.Form.elements["my-drink"].value;
results +=<br>Quality: " + orderForm.elements["my-qty"].value;
var orderResults + document.getElementsById("my-order")
orderResults.style.display = "block";
orderResults.innerHTML = results;
}
</script>
</body>
<section>
<h2> MY ORDER FROM: </h2>
</section>
<table class="card" style=background-color:white>
<tr>
<td> Name: </td>
<td><input type="text" size="25" name="my name"></td>
</tr>

<tr>
<td> Address: </td>
<td><input type="text" size="25" name="my address"></td>
</tr>

<tr>
<td> Farourite Drink: </td>
<td>
<select name="my-drink">
<option> Milk </option>
<option> Coffee </option>
<option> Tea </option>
</select>
 </td>

 <tr>
 <td> Quality: </td>
 <td>
 <input type="number" name="my-qty" value="1" min="1" max="5">
 <small>(max 5)</small>
 </td>
 </tr>
 
 <tr>
 <br>
 </tr>
 <tr>
 <td colspan="2">
 <input class="button" 
 value ="Process Order"
 onclick="placeOrder();">
 <Input class="button"
 type="reset" value="Clear"
 onclick="document.getElementById('my-order').style.display = 'none'";>
 </td> 
 </table>
 <form>
 <h1>GOOFY FORM:</h1>
 What's the silliest idea you have ever had?
 <input type="text" size="50" size="50"
 <br></br>
 <button>Submit</button>
 <br>
 <div id"=my-order">
 </div>
 </form> 
 <section class="blue container" style=background-color:white;">
<h2>
OUR TEAM://
</h2>
<article class="card"> 
<div class="icon"> &#9745;</div>
<h3> Neo Diseko</h3>
<p>Data Analyst.<p/>
</article>
<article class="card" style=background-color:white;">
<div class="icon"> &#10083;</div>
<h3>Neonyane Diseko</h3>
<p>Data Scientist.<p/>
 </articles>
 <br>
</section>
<article class="card" style=background-color:white;">
<h3>GET IN TOUCH.</h3>
<p>:Probably the best place to create your websites in all of Potch.</p> 
<br>
<h3>Contact Us:</h3>
<p>We would love to hear from you.</p>
<br>Call or email us. <br>
Mobile: 076 895 0832//
<br>
Email:disekodineo93@gmail.com
<br>
<div> <h3> THANKS FOR VISITING! </h3></div>
<br>
</article>
<p>
ABOUT US: Founded in 2022, by Dineo Diseko. We've provided services to over 100 clients and deliverd over 10,000 parcels.
</p>
<div class="circle">F</div>
<div class="circle">I</div>
<div class="circle">T</div>
&copy;
2022 i-Dineo Logistics.

