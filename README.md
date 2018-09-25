3.3
ml>
<head>
<title>Indexof</title>
<script>
function index()
{ 
var a=document.getElementById("string").value;
var b=document.getElementById("letter").value;
var c=a.substr(3,6);
var d=a.match(b);
document.write('The actual string is : ' + a);
document.write('<br> Result of str.match('+b+'):'+d);
document.write('<br> Result of str.substr(3,6) is ' + c);
document.write('<br>'+a.toLowerCase());
document.write('<br>'+a.toUpperCase());
}
</script>
</head>
<body>
<form name="frm">
<table>
<tr>
	<td>The actual string is </td>
	<td><input type ="text" id="string"></td>
</tr>
<tr>
	<td>The match to be searched for is </td>
	<td><input type ="text" id="letter"></td>
</tr>
<button onclick="index()">Try it</button>
</table>
</form>
</body>
</html>
------------------------------------------------------------------
3.2
<html>
<head>
<title>Indexof</title>
<script>
function index()
{ 
var a=(document.getElementById("string").value);
var letter=document.getElementById("letter").value;
var c=a.indexOf(letter);
document.write('The actual string is : ' + a);
document.write('<br>');
document.write('The character to be searched for is : ' + letter);
document.write('<br>');
document.write('The index is ' + c);
}
</script>
</head>
<body>
<form name="frm">
<table>
<tr>
	<td>The actual string is </td>
	<td><input type ="text" id="string"></td>
</tr>
<tr>
	<td>The character to be searched for is </td>
	<td><input type ="text" id="letter"></td>
</tr>
<button onclick="index()">Try it</button>
</table>
</form>
</body>
</html>
