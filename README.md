# assignment6
<html>
<head>
    <script>
        function view(num)
        {
        document.getElementById("result").value+=num
        }
        function compute()
        {

        let x=document.getElementById("result").value
        let y=eval(x)
        document.getElementById("result").value=y
        }
        
        function clr(){
        document.getElementById("result").value=""
        }
        </script>
</head>
<body>
    
    
<center>
    <h1>Simple calculator using javascript</h1>

<table border="1">
    <tr>
        <td colspan="3"><input type="text" id="result"</td>
        
    </tr>
    <tr>

<td><input type="button" value="0" onclick="view(0)"/></td>
<td><input type="button" value="1" onclick="view(1)"/></td>
<td><input type="button" value="2" onclick="view(2)"/></td>
<td><input type="button" value="+" onclick="view('+')"/></td>
</tr>
<tr>
<td><input type="button" value="3" onclick="view(3)"/></td>
<td><input type="button" value="4" onclick="view(4)"/></td>
<td><input type="button" value="5" onclick="view(5)"/></td>
<td><input type="button" value="-" onclick="view('-')"/></td>
</tr>
<tr>
    <td><input type="button" value="6" onclick="view(6)"/></td>
    <td><input type="button" value="7" onclick="view(7)"/></td>
    <td><input type="button" value="8" onclick="view(8)"/></td>
    <td><input type="button" value="*" onclick="view('*')"/></td>
</tr>

<tr>
<td><input type="button" value="9" onclick="view('9')"/></td>
<td><input type="button" value="+/-" onclick="view('+/-')"/></td>
<td><input type="button" value="=" onclick="compute()"/></td>
<td><input type="button" value="/" onclick="view('/')"/></td>
</tr>
<tr>
    <td><input type="button" value="clear" onclick="clr()"/></td>
</tr>

</table>
</center>
</body>
</html>
<style>

input[type="button"]
{
    background-color: rgba(206, 201, 201, 0.301);
    color: black;
    border: solid black 2px;
    width: 100%;
}

</style>
