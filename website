
<!DOCTYPE html> 

<html> 
<head> 
<title>Home Questionnaire<span id="selection-marker-1" class="redactor-selection-marker"></span></title> 
</head> 

<body> 
<h1>What is your favorite place to travel?</h1> 
<p>I am building a directory of the sweetest travel destinations.</p> 

<form name="travel" onsubmit="identify(event)"> What is your favorite travel destination? <input name="destination" required="" size="81" type="text"/> 
<br><br><br> 
Any recommendations (cool things to do, places to visit or restaurants to eat)? 
<br><br> 
<textarea cols="81" name="details" required="" rows="10"> </textarea> 
<br><br> 
Name: <input name="fullname" required="" size="75" type="text"/> 
<br><br> 
Email: <input name="email" required="" size="75" type="email"/> 
<br><br> <input name="submit" type="submit" value="submit"/> </form> 

<script type="text/javascript"> 
function identify(e){ 
e.preventDefault(); 
var form = e.target; 
var email = form["email"].value; 
var fullname = form["fullname"].value; 
var destination = form["destination"].value; 
var details = form["details"].value; 
var user = { 
  email: email, 
  name: fullname, 
  destination: 
  destination, 
  details: details 
}; 
// Placeholder for an Identify call
analytics.identify('1234', { 
  email: email, 
  name: fullname 
}); 
// Placeholder for a Track call
analytics.track('destination submitted', user, function() { 
  window.location.href = ""; 
}); } 
</script> 

</body> 
</html>
