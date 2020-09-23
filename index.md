
<!doctype html>
<html>
<head>
<meta charset="UTF-8">
<title>学生进出校报备结果页</title>
	
	<script>  
function getCurDate()  
{  
 var d = new Date();  
 var week;  
 switch (d.getDay()){  
 case 1: week="星期一"; break;  
 case 2: week="星期二"; break;  
 case 3: week="星期三"; break;  
 case 4: week="星期四"; break;  
 case 5: week="星期五"; break;  
 case 6: week="星期六"; break;  
 default: week="星期天";  
 }  
 var years = d.getFullYear();  
 var month = add_zero(d.getMonth()+1);  
 var days = add_zero(d.getDate());  
 var hours = add_zero(d.getHours());  
 var minutes = add_zero(d.getMinutes());  
 var seconds=add_zero(d.getSeconds());  
 var ndate = years+"-"+month+"-"+days+"   "+hours+":"+minutes+":"+seconds+" ";  
 divT.innerHTML= ndate;  
}  
  
function add_zero(temp)  
{  
 if(temp<10) return "0"+temp;  
 else return temp;  
}  
  
setInterval("getCurDate()",100);  
  
</script>  
	
	


	
	<style type="text/css">
		.a{
			width: 280px;
			height: 280px;
			background-color:#0D8A04 ;
			
				}
	</style>
	

	
	<!-- Designed by 李旭日，2020.9.22
造福人类，益寿延年
-->
	
	
	
	
	
</head>

	
	<font face=黑体>
	
<body style="width:430px; overflow: hidden;">
	

	
	
	<font size="3em">
<div>
	
	<p>
	  姓名&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;   &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 
<input type=text style="border:0;height:20px; width: 120px;font-size:0.960em;color:#666666;margin-bottom: 0">
	</p>
	
		<hr style="border:none;border-top:1px solid #DEDEDE;" />
		
		<p>学号&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;   &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 
			<input type=text style="border:0;height:20px; width: 120px;font-size:0.960em;color:#666666;margin-bottom: 0">
			</p>
		
		<hr style="border:none;border-top:1px solid #DEDEDE;" />
		
		<p>学院&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;   &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 
			<input type=text style="border:0;height:20px; width: 120px;font-size:0.960em;color:#666666;margin-bottom: 0">
			</p>
		
		<hr style="border:none;border-top:1px solid #DEDEDE;" />
		
	<p>年级&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 
			<input type=text style="border:0;height:20px; width: 120px;font-size:0.960em;color:#666666;margin-bottom: 0">
			</p>
	
	<hr style="border:none;border-top:1px solid #DEDEDE;" />
	
	<p>班级&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 
			<input type=text style="border:0;height:20px; width: 120px;font-size:0.960em;color:#666666;margin-bottom: 0">
			</p>
	<hr style="border:none;border-top:1px solid #DEDEDE;" />
	<br>
	<br>
	
	
	</div>
</font>
		
		<center>
		
		<div class=a>
	
			<p{line-height:5px;}>&nbsp;</p>
			<p>&nbsp;
				
</p>
			
<fontface=黑体>
			
			<p{line-height:5px;}>
				
					<font size="7" >
						<center>
							<font color=ffffff>
								进校<br>已报备
							</font>
						</center>
					</font>
				
				</p>
	
	
			
			
			</font>
			
			</div>
		</center>
		
		
		
		<div>
		
		 <p>
			 <font face=黑体>
			 <font size="6" >
				 <center> 
					 <font color=000000>
						 <strong>
							 
	<div id="divT"></div> 
							 
						 </strong>
					 </font>
	 			</center>
			 </font>
			 </font>
			</p>
			<p></p><br>
			<br>
			<br>
			<center><p><font color=#DEDEDE;size=1>Designed by Lixuri  2020.9.23</p></center>
		</div>
		
		
		<br>
	<br>
	<br>
	<br>
	<br>
	<br>
		
		
		
		</body>
	
	
	
	
	
</font>
</html>
