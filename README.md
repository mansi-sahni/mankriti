
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
        <meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
        
    </head>
    <body>
        <center>
        <h1>Welcome to Graphics Era Train Enquiry System</h1>
        <%
        String sstn=request.getParameter("sstn");
        String sdtn=request.getParameter("sdtn");
            try{
        String sql="";
        int i=1;
        Class.forName("sun.jdbc.odbc.JdbcOdbcDriver");
       sql="SELECT m.trainno,source,destination FROM train_tran t,train_mst m where station like '"+sstn+"' or station like '"+sdtn+"'  and (t.trainno=m.trainno)";
        Connection con=DriverManager.getConnection("jdbc:odbc:geit1");
        Statement stmt=con.createStatement();
        ResultSet rs=stmt.executeQuery(sql);
        out.println("<table border=1"+" width='50%'>");
        out.print("<tr><th>Train No</td><th>Source Station</th><th>Destination Station</th></tr>");
        int flag=0;
        while(rs.next())
                       {
            int x=rs.getInt(1);
            flag=1;
            out.println("<tr><td><a href=searchbytrain.jsp?strain="+x+">"+x+"</a></td><td>"+rs.getString(2)+"</td><td>"+rs.getString(3)+"</td></tr>");
                       }
        out.println("</table>");
        if (flag==0)
            out.println("no record available");
        out.println("<a href=index.jsp>Back</a>");
    }catch(Exception e){
    out.println(e);
    }
            %>
    </center></body>
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
