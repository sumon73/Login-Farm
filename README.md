
<!DOCTYPE html>
<html>
<head> <title> All Abdate News </title>

<style>

#myProgress {
  position: relative;
  width: 100%;
  height: 30px;
  background-color: #ddd;
}

</style>


</head>






<body>
<h1 id="myProgress">   
   my progress
   
   </h1>

<button onclick="move()">Click Here
</button>






<script> 
function move() {var elem=document.getelementbyid ("myBar");
var width= 1;
var id = setInterval(frame, 10);
function frame(){if (width >=100) {clear Interval(id);} else{width++;elem.style.width=width +'%';} 
}
}
</script>

</body>







</html>
© 2022 GitHub, Inc.
Terms
