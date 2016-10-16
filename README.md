# move-in-path
Let your div move in SVG path

<svg version="1.1" id="图层_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
	 width="595.28px" height="841.89px" viewBox="0 0 595.28 841.89" enable-background="new 0 0 595.28 841.89" xml:space="preserve">
<path fill="green" stroke="#000000" stroke-miterlimit="10" d="M269,194c124,84,0,204,0,204s172-75,124-120s250-130,49-162
	s-123,0-123,0s-86-139-78-32s-90,122-90,122Z" />

</svg>
<div class="plot"></div>
<script type="text/JavaScript"> 
	   var path="M269,194c124,84,0,204,0,204s172-75,124-120s250-130,49-162s-123,0-123,0s-86-139-78-32s-90,122-90,122Z"
       var obj=new MoveInPath(path);
	   obj.dur=3;
	   obj.iterationCount=1000;
	   obj.run(function(x,y){
		   $(".plot").css({"left":x,"top":y});
	   })

</script> 

