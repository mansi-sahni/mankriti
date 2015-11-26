<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">

<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<title></title>
<meta name="keywords" content="" />
<meta name="description" content="" />
<link href="http://fonts.googleapis.com/css?family=Source+Sans+Pro:200,300,400,600,700,900|Quicksand:400,700|Questrial" rel="stylesheet" />
<link href="default.css" rel="stylesheet" type="text/css" media="all" />
<link href="fonts.css" rel="stylesheet" type="text/css" media="all" />



</head>
<body>
<div id="header-wrapper">
	<div id="header" class="container">
		<div id="logo">
			<h1><span class="icon icon-cog"></span><a href="index.html">RAILWAYS</a></h1>
			<div id="menu">
				<ul>
					<li class="current_page_item"><a href="index.html" title="">Homepage</a></li>
					<li><a href="trainsbetween.html" title="">Trains Between</a></li>
					<li><a href="trainroute.html"  title="">Train Route</a></li>
					
				</ul>
			</div>
		</div>
	</div>
</div>
<div id="page-wrapper">
	<div id="page" class="container">
		<div class="title">
			<h2>Welcome to our project</h2>
		</div>
		<p>Something about your project. Have fun :) </p>
	</div>
</div>
<div class="wrapper">
	<div id="three-column" class="container">
		<div><span class="arrow-down"></span></div>
		<div id="tbox1">
			<div class="title">
				<h2>Indian Railways</h2>
			</div>
			<p>Some things about Indian Railways</p>
			<a href="index.html" class="button">Learn More</a> </div>
		<div id="tbox2">
			<div class="title">
				<h2>Trains Between Stations</h2>
			</div>
			<p>Something about trains between Stations.</p>
			<a href="trainsbetween.html" class="button">Learn More</a> </div>
		<div id="tbox3">
			<div class="title">
				<h2>Train Route</h2>
			</div>
			<p>Something about Train route.</p>
			<a href="trainroute.html" class="button">Learn More</a> </div>
	</div>

</div>
<div id="copyright" class="container">
	<p>&copy; Untitled. All rights reserved. | Design by MANKRITI</a>.</p>
		
        <ul class="contact">
			<li><a href="#" class="icon icon-twitter"><span>Twitter</span></a></li>
			<li><a href="#" class="icon icon-facebook"><span></span></a></li>
			<li><a href="#" class="icon icon-dribbble"><span>Pinterest</span></a></li>
			<li><a href="#" class="icon icon-tumblr"><span>Google+</span></a></li>
			<li><a href="#" class="icon icon-rss"><span>Pinterest</span></a></li>
		</ul>
</div>
</body>
</html>

<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">

<html xmlns="http://www.w3.org/1999/xhtml">
<head>

<title></title>
<link href="http://fonts.googleapis.com/css?family=Source+Sans+Pro:200,300,400,600,700,900|Quicksand:400,700|Questrial" rel="stylesheet" />
<link href="default.css" rel="stylesheet" type="text/css" media="all" />
<link href="fonts.css" rel="stylesheet" type="text/css" media="all" />

        <script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyCUp-1btiHqwBiXYNh6nCHUp1iRXqjuhzM&signed_in=true&callback=initialization" async defer>
        </script>
      
        <script>
        var trains =    [
                        ["Agra","AGC",27.158074,77.989552],
                        ["Ahmedabad","ADI",22.998602,72.611028],
                        ["Ajmer","AII",26.457851,74.637503],
                        ["Ambala","UMB",30.338472,76.827572],
                        ["Amritsar","ASR",31.633369,74.867110],
                        ["Aurangabad","AWB",19.860131,75.311444],
                        ["Bangalore","SBC",12.978433,77.569456],
                        ["Bareilly","BE",28.337181,79.411039],
                        ["Bhopal","BPL",23.267977,77.414007],
                        ["Bhubaneshwar","BBS",20.266621,85.843798],
                        ["Bhusaval","BSL",21.047001,75.788382],
                        ["Bilaspur","BSP",22.054984,82.171717],
                        ["Chandigarh","CDG",30.701897,76.822000],
                        ["Coimbatore","CBE",10.996650,76.967222],
                        ["Cuttack","CTC",20.463880,85.900156],
                        ["Dehradun","DDN",30.314184,78.033430],
                        ["Dhanbad","DHN",23.791287,86.429792],
                        ["Ernakulam ","ERS",9.969079,76.290935],
                        ["Erode","ED",11.327991,77.726062],
                        ["Ghaziabad","GZB",28.653827,77.427040],
                        ["Gorakhpur","GKP",26.759579,83.382267],
                        ["Guwahati","GHY",26.182067,91.750687],
                        ["Haridwar","HW",29.948272,78.155552],
                        ["Howrah","HW",22.583818,88.342170],
                        ["Indore","INDB",22.717471,75.868272],
                        ["Jabalpur","JBP",23.172413,79.932124],
                        ["Jaipur","JP",26.920248,75.786804],
                        ["Jammu","JAT",32.706530,74.880672],
                        ["Jhansi","JHS",25.444845,78.552577],
                        ["Jodhpur","JU",26.283627,73.023007],
                        ["Kanpur","CNB",26.454948,80.350436],
                        ["Katihar","KIR",25.547953,87.565122],
                        ["Kharagpur","KGP",22.340898,87.325806],
                        ["Kota","KOTA",25.223796,75.880756],
                        ["Lucknow","LKO",26.831646,80.922082],
                        ["Madurai","MDU",9.917721,78.111641],
                        ["Moradab","MB",28.831296,78.765830],
                        ["Mumbai","BCT",18.970760,72.819478],
                        ["Mysore","MYS",12.316717,76.646333],
                        ["Nagpur","NGP",21.151924,79.088689],
                        ["Delhi","NDLS",28.642771,77.220962],
                        ["Patna ","PNBE",25.602724,85.137240],
                        ["Pune","PUNE",18.528887,73.874388],
                        ["Raipur","R",21.256362,81.629883],
                        ["Rajkot","RJT",22.311768,70.803047],
                        ["Ranchi","RNC",23.349483,85.335677],
                        ["Ratlam","RTM",23.340627,75.050484],
                        ["Rourkela","ROU",22.228090,84.861896],
                        ["Siwan","SV",26.211032,84.358302],
                        ["Surat","ST",21.204884,72.840947],
                        ["Tiruchirapalli","TPJ",10.794201,78.685384],
                        ["Tirupati","TPTY",13.627891,79.419398],
                        ["Trichur","TCR",10.514514,76.207672],
                        ["Udaipur","UDZ",24.568357,73.699800],
                        ["Ujjain","UJN",23.178716,75.781445],
                        ["Visakhapatnam","VSKP",17.722048,83.289731]
                        ];
        
        var polyOptions = {
            strokeColor: '#000000',
            strokeOpacity: 1.0,
            strokeWeight: 3
        }
       var apicode;
        var data_list=[];
        var l =0;
        
        
            function initialization() {
                
                var map = new google.maps.Map(document.getElementById('src'), {
                    zoom: 4,
                    center: {lat: 22, lng: 77 }
                });
         }
            function route_show(train_num){
                
                var map = new google.maps.Map(document.getElementById('src'), {
                    zoom: 4,
                    center: {lat: 21, lng: 78 }
                });
                poly = new google.maps.Polyline(polyOptions);
                    poly.setMap(map);
                
                document.getElementById("wait").innerHTML = "Please Wait....."
                  var xmlhttp = new XMLHttpRequest();
                var url = 'http://api.railwayapi.com/route/train/'+train_num+'/apikey/lxeqx8167/';
                xmlhttp.open("GET", url, true);
                xmlhttp.send();
           
                xmlhttp.onreadystatechange = function() {
                    if (xmlhttp.readyState == 4 && xmlhttp.status == 200) {
                        var myArr = xmlhttp.responseText;
                        obj = JSON.parse(myArr);
                        if(obj.response_code != 200){
                            document.getElementById("wait").innerHTML = "*Invalid Train Number/ Connection Problem"
                            return;
                        }
                        for(var i=0;i<obj.route.length;i++){
                        
                            if(!((obj.route[i].lat < 37.6 && obj.route[i].lat > 8.4) && (obj.route[i].lng < 97.25 && obj.route[i].lng > 68.7))) {
                                
                                apicode = obj.route[i].code;
                                
                                
                                for(var j=0;j<trains.length;j++){
                                    var source_code = trains[j][1];
                                
                                    if(source_code === apicode){

                                        c_lat = trains[j][2];
                                        c_lng = trains[j][3];
                                        var xyz = obj.route[i].fullname+"\nArrival Time: "+obj.route[i].scharr+"\nDeparture: "+ obj.route[i].schdep+"\nDay: "+obj.route[i].day;
                                        data_list[l] = [c_lat, c_lng, xyz];
                                        l++;
                                    }
                                    
                                }
                    
                            }
                            else{
                                
                                c_lat = obj.route[i].lat;
                                c_lng = obj.route[i].lng;
                                var xyz = obj.route[i].fullname+"\nArrival Time: "+obj.route[i].scharr+"\nDeparture: "+ obj.route[i].schdep+"\nDay: "+obj.route[i].day;
                                data_list[l] = [c_lat, c_lng, xyz];
                                l++;
                            }
                        }
               
                        for( var i=0;i<data_list.length;i++){
                                                     
                            var path = poly.getPath();
                            
                              var latLng = new google.maps.LatLng( data_list[i][0], data_list[i][1]);
                              var marker = new google.maps.Marker({
                                    position:latLng,
                                    map:map,
                                    title: data_list[i][2]
                                });
                                path.push(latLng)
                                
                        }
                        document.getElementById("wait").innerHTML = ""
                        data_list = [];
                        l=0;
                    }
                };
                

            }
             
          </script>
</head>
<body>
<div id="header-wrapper">
	<div id="header" class="container">
		<div id="logo">
			<h1><span class="icon icon-cog"></span><a href="index.html">RAILWAYS</a></h1>
			<div id="menu">
				<ul>
					<li class="current_page_item"><a href="index.html" title="">Homepage</a></li>
					<li><a href="trainsbetween.html" title="">Trains Between</a></li>
					<li><a href="trainroute.html"  title="">Train Route</a></li>
					
				</ul>
			</div>
		</div>
	</div>
</div>

<div class="wrapper">
	<div id="three-column" class="container">
		<div><span class="arrow-down"></span></div>
		<div id="tbox1">
			<div class="title">
				<h2>Indian Railways</h2>
			</div>
			<p>Some things about Indian Railways</p>
			<a href="index.html" class="button">Learn More</a> </div>
		<div id="tbox2">
			<div class="title">
				<h2>Trains Between Stations</h2>
			</div>
			<p>Something about trains between Stations.</p>
			<a href="trainsbetween.html" class="button">Learn More</a> </div>
		<div id="tbox3">
			<div class="title">
				<h2>Train Route</h2>
			</div>
			<p>Something about Train route.</p>
			<a href="trainroute.html" class="button">Learn More</a> </div>
	</div>
    

    <table>
		<form>
      
            <tr>
            <td style="margin-left: 80px;"><label>Enter the Train Number <input type="text" name="field1"/></label></td>
        
            <td><input type="button" name="check" class="button button-small" onclick="route_show(this.form.field1.value)" value="Find the Route" /></td>
        </form>
        </tr>
           <tr>
            <td><div id = "src" style ="width:580px; height:450px; margin-left: 80px;"></div></td>
            <td><p id="wait"></p></td>
		    </tr>
            </table>
</div>



<div id="copyright" class="container">
	<p>&copy; Untitled. All rights reserved. | Design by MANKRITI</a>.</p>
		
        <ul class="contact">
			<li><a href="#" class="icon icon-twitter"><span>Twitter</span></a></li>
			<li><a href="#" class="icon icon-facebook"><span></span></a></li>
			<li><a href="#" class="icon icon-dribbble"><span>Pinterest</span></a></li>
			<li><a href="#" class="icon icon-tumblr"><span>Google+</span></a></li>
			<li><a href="#" class="icon icon-rss"><span>Pinterest</span></a></li>
		</ul>
</div>
</body>
</html>


<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">

<html xmlns="http://www.w3.org/1999/xhtml">
<head>

<title></title>
<link href="http://fonts.googleapis.com/css?family=Source+Sans+Pro:200,300,400,600,700,900|Quicksand:400,700|Questrial" rel="stylesheet" />
<link href="default.css" rel="stylesheet" type="text/css" media="all" />
<link href="fonts.css" rel="stylesheet" type="text/css" media="all" />

<script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyDAUNUXQNb6Oh0iWLN5-6UJvEOwenfLc4c&signed_in=true&callback=initMap&libraries=geometry" async defer>
        </script>
        <script>
        var trains =    [
                        ["Agra","AGC",27.158074,77.989552],
                        ["Ahmedabad","ADI",22.998602,72.611028],
                        ["Ajmer","AII",26.457851,74.637503],
                        ["Ambala","UMB",30.338472,76.827572],
                        ["Amritsar","ASR",31.633369,74.867110],
                        ["Aurangabad","AWB",19.860131,75.311444],
                        ["Bangalore","SBC",12.978433,77.569456],
                        ["Bareilly","BE",28.337181,79.411039],
                        ["Bhopal","BPL",23.267977,77.414007],
                        ["Bhubaneshwar","BBS",20.266621,85.843798],
                        ["Bhusaval","BSL",21.047001,75.788382],
                        ["Bilaspur","BSP",22.054984,82.171717],
                        ["Chandigarh","CDG",30.701897,76.822000],
                        ["Coimbatore","CBE",10.996650,76.967222],
                        ["Cuttack","CTC",20.463880,85.900156],
                        ["Dehradun","DDN",30.314184,78.033430],
                        ["Dhanbad","DHN",23.791287,86.429792],
                        ["Ernakulam ","ERS",9.969079,76.290935],
                        ["Erode","ED",11.327991,77.726062],
                        ["Ghaziabad","GZB",28.653827,77.427040],
                        ["Gorakhpur","GKP",26.759579,83.382267],
                        ["Guwahati","GHY",26.182067,91.750687],
                        ["Haridwar","HW",29.948272,78.155552],
                        ["Howrah","HW",22.583818,88.342170],
                        ["Indore","INDB",22.717471,75.868272],
                        ["Jabalpur","JBP",23.172413,79.932124],
                        ["Jaipur","JP",26.920248,75.786804],
                        ["Jammu","JAT",32.706530,74.880672],
                        ["Jhansi","JHS",25.444845,78.552577],
                        ["Jodhpur","JU",26.283627,73.023007],
                        ["Kanpur","CNB",26.454948,80.350436],
                        ["Katihar","KIR",25.547953,87.565122],
                        ["Kharagpur","KGP",22.340898,87.325806],
                        ["Kota","KOTA",25.223796,75.880756],
                        ["Lucknow","LKO",26.831646,80.922082],
                        ["Madurai","MDU",9.917721,78.111641],
                        ["Moradab","MB",28.831296,78.765830],
                        ["Mumbai","BCT",18.970760,72.819478],
                        ["Mysore","MYS",12.316717,76.646333],
                        ["Nagpur","NGP",21.151924,79.088689],
                        ["Delhi","NDLS",28.642771,77.220962],
                        ["Patna ","PNBE",25.602724,85.137240],
                        ["Pune","PUNE",18.528887,73.874388],
                        ["Raipur","R",21.256362,81.629883],
                        ["Rajkot","RJT",22.311768,70.803047],
                        ["Ranchi","RNC",23.349483,85.335677],
                        ["Ratlam","RTM",23.340627,75.050484],
                        ["Rourkela","ROU",22.228090,84.861896],
                        ["Siwan","SV",26.211032,84.358302],
                        ["Surat","ST",21.204884,72.840947],
                        ["Tiruchirapalli","TPJ",10.794201,78.685384],
                        ["Tirupati","TPTY",13.627891,79.419398],
                        ["Trichur","TCR",10.514514,76.207672],
                        ["Udaipur","UDZ",24.568357,73.699800],
                        ["Ujjain","UJN",23.178716,75.781445],
                        ["Visakhapatnam","VSKP",17.722048,83.289731]
                        ];
                        
        
            var sflag = 0, dflag=0;
            var markers = [];
            var source_latlng, dest_latlng;
            var source_code, dest_code, source_name, dest_name;
            function initMap() {
                
                var smap = new google.maps.Map(document.getElementById('src'), {
                    zoom: 4,
                    center: {lat: 22, lng: 77 }
                });
         
                var dmap = new google.maps.Map(document.getElementById('dest'), {
                    zoom: 4,
                    center: {lat: 21, lng: 78 }
                });
         
                smap.addListener('click', function(s) {
                    sflag +=  1;
                    srcMarker(s.latLng, smap);
                });
                
                dmap.addListener('click', function(d) {
                    dflag += 1;
                    destMarker(d.latLng, dmap);
                });
                
            }
            
            function reset() {
                for (var i = 0; i < markers.length; i++) {
                    markers[i].setMap(null);
                }
                markers = [];
                sflag=0;
                dflag=0;             
            }


            function srcMarker(latLng, smap) {
                if(sflag == 1){
                    var marker = new google.maps.Marker({
                        position: latLng,
                        title: 'Source Position',
                        map: smap,
                    });
                    source_latlng = latLng;
                    markers.push(marker);
                }
            }
              
            function destMarker(latLng, dmap) {
                if(dflag == 1){
                    var marker = new google.maps.Marker({
                        position: latLng,
                        title: 'Destination Position',
                        map: dmap,
                    });
                    dest_latlng = latLng;
                    markers.push(marker);
                }
            } 
            function distcalc(){
                if(markers.length == 0){
                    alert("Please Select Source and Destination Position");
                }
                else{
                    document.getElementById("slot").innerHTML = "<h2>Please Wait....</h2>"
                    var a = new google.maps.LatLng(trains[0][2],trains[0][3]);
                    var source_min_distance = google.maps.geometry.spherical.computeDistanceBetween(source_latlng,a);
                    var dest_min_distance = google.maps.geometry.spherical.computeDistanceBetween(dest_latlng,a);
                                        
                    for(var i = 0; i < trains.length; i++) {
                        
                        var a = new google.maps.LatLng(trains[i][2],trains[i][3]);
                        
                        var source_distance = google.maps.geometry.spherical.computeDistanceBetween(source_latlng,a);
                        var dest_distance = google.maps.geometry.spherical.computeDistanceBetween(dest_latlng,a);
                        
                        
                        if(source_distance < source_min_distance){
                            source_min_distance = source_distance;
                            source_code = trains[i][1];
                            source_name = trains[i][0];
                        }
                        
                        if(dest_distance < dest_min_distance){
                            dest_min_distance = dest_distance;
                            dest_code = trains[i][1];
                            dest_name = trains[i][0];
                        }
                    }
                }
                schedule();
                
            }
            function schedule(){
                var xmlhttp = new XMLHttpRequest();
                var url = 'http://api.railwayapi.com/between/source/'+source_code+
                '/dest/'+dest_code+'/apikey/lxeqx8167/';

                xmlhttp.open("GET", url, true);
                xmlhttp.send();
           
                xmlhttp.onreadystatechange = function() {
                    if (xmlhttp.readyState == 4 && xmlhttp.status == 200) {
                        var myArr = xmlhttp.responseText;
                        obj = JSON.parse(myArr);
                        var table_header = "<h3>"+source_name+" To "+dest_name+"</h3>"+"<table> <tr> <th>Train Number</th><th>Train Name</th></tr>";
                        var table_data = "";
                        if(obj.total == 0){
                            document.getElementById("slot").innerHTML = "<h2>No Train/s Found</h2>"
                            return;
                        }
                        for(var i=0;i<obj.train.length;i++){
                            table_data += "<tr><td>"+obj.train[i].number+"</td><td>"+obj.train[i].name+"</td></tr>";
                        }
                        document.getElementById("slot").innerHTML = table_header+table_data
                    }
                };
            }
            
            
        </script>
   

</head>
<body>
<div id="header-wrapper">
	<div id="header" class="container">
		<div id="logo">
			<h1><span class="icon icon-cog"></span><a href="index.html">RAILWAYS</a></h1>
			<div id="menu">
				<ul>
					<li class="current_page_item"><a href="index.html" title="">Homepage</a></li>
					<li><a href="trainsbetween.html" title="">Trains Between</a></li>
					<li><a href="trainroute.html"  title="">Train Route</a></li>
					
				</ul>
			</div>
		</div>
	</div>
</div>

<div class="wrapper">
	<div id="three-column" class="container">
		<div><span class="arrow-down"></span></div>
		<div id="tbox1">
			<div class="title">
				<h2>Indian Railways</h2>
			</div>
			<p>Some things about Indian Railways</p>
			<a href="index.html" class="button">Learn More</a> </div>
		<div id="tbox2">
			<div class="title">
				<h2>Trains Between Stations</h2>
			</div>
			<p>Something about trains between Stations.</p>
			<a href="trainsbetween.html" class="button">Learn More</a> </div>
		<div id="tbox3">
			<div class="title">
				<h2>Train Route</h2>
			</div>
			<p>Something about Train route.</p>
			<a href="trainroute.html" class="button">Learn More</a> </div>
	</div>
    
    <div id="portfolio" class="container">
    <table>
    <tr>
		<td><div class="box">
				<h3>Source Position</h3>
				<p>Click on the Map to select source position.</p></td>
		</div>
    <td><div class="box" style="margin-left:90px;">
				<h3>Destination</h3>
				<p>Click on the Map to select destination position.</p></td>
		</div>
    </tr>
    <tr>
    <td><div class="column1" id="src" style = "width:480px; height:600px;"></td>
		<td>
		<div class="column4" id="dest" style = "width:480px; height:600px;margin-left: 90px;"></td>
    </tr>    
         </table>
         <button onclick="distcalc()" class="button button-small"> Find the trains</button> <button onclick="reset()"class="button button-small">Reset</button>
    </div>

    </div>
</div>
<div id="wrapper2">
	<div id="slot"></div>
</div>


<div id="copyright" class="container">
	<p>&copy; Untitled. All rights reserved. | Design by MANKRITI</a>.</p>
		
        <ul class="contact">
			<li><a href="#" class="icon icon-twitter"><span>Twitter</span></a></li>
			<li><a href="#" class="icon icon-facebook"><span></span></a></li>
			<li><a href="#" class="icon icon-dribbble"><span>Pinterest</span></a></li>
			<li><a href="#" class="icon icon-tumblr"><span>Google+</span></a></li>
			<li><a href="#" class="icon icon-rss"><span>Pinterest</span></a></li>
		</ul>
</div>
</body>
</html>

