# bar-chart
<!DOCTYPE html>
<head>
<meta charset="utf-8"/>
<title>UVcharts</title>
<body>
<script src='C:\Users\EduStan\Desktop\UV\vendor\d3.min.js'> </script>

<script src='C:\Users\EduStan\Desktop\UV\vendor\uvcharts.min.js'> </scripts>
<script type="text/javascript"> 
 
var init = function () {
var graphdef = {
 categories : ['uvcharts'],
dataset : [
   { name : 'java Installation', value: 98 },
   { name : 'Eclipse Installation',value: 85},
   { name : 'String Reverse Code',value:78},
    { name : 'Comparator code', value:60}
]
}
};
var config = {
meta : {
  
caption : 'Third Assignment',
subcaption : 'Day 1'
}
};
var chartObject = uv.chart('Bar',graphdef);
};
</script>
</head>

<div id='uv-div'></div>

</body>
<script>
init();
<script>
</html>
