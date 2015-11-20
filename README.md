
<html>
    <head>
        <meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
        <title>Railway Enquiry System</title>
    </head>
    <body bgcolor="pink">
    <center>  <h1>Welcome to Railway Enquiry System</h1>
        <font size="5">  <a href="searchbytrain.html">Search By Train no</a><br>
        <a href="searchbystation.html">Search By Station</a></font>
    </center></body>
</html>


<html>
    <head>
        <title></title>
        <meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    </head>
    <body>
    <center><h1>Welcome to Railway Enquiry System</h1> 
        <table border="0" width="50%">
            <form method="post" action="searchbystation.jsp">
                <tr><td>Enter Source Station</td><td> <input type="text" name="sstn"></input></td></tr>
                 <tr><td>Enter Destination Station</td><td> <input type="text" name="sdtn"></input></td></tr>
                 <tr><td colspan="2"><input type="submit" value="search"></tr>
            </form>   
        </table>
    </center> 
</body>
</html>



<html>
    <head>
        <title></title>
        <meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    </head>
    <body>
    <center><h1>Welcome to Railway Enquiry System</h1>
        <table border="0" width="40%">
            <form method="post" action="searchbytrain.jsp">
                <tr><td>Train Number</td><td><input type="text" name="strain"></input></td></tr>
                <tr align="center"><td colspan="2"><input type="submit" value="search"></td>
                    </tr></table>
        </form>
        </table>
        </center>
    </body>
</html>
