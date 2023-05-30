# 5556
<select name="select" onchange="window.open(this.options[this.selectedIndex].value)">
<option value="http://www.microsoft.com/ie"> Internet Explorer</option>
<option value="http://www.microsoft.com"> Microsoft Home</option>
<option value="http://msdn.microsoft.com"> Developer Network</option>
</select>

<Script Language="JavaScript"> 

　　 var timedate= new Date("October 1,2002"); 

　　 var times= "国庆节"; 

　　 var now = new Date(); 

　　 var date = timedate.getTime() - now.getTime(); 

　　 var time = Math.floor(date / (1000 * 60 * 60 * 24)); 

　　 if (time >= 0) 

　　 document.write( "现在离"+times+"还有: "+time +"天")

</Script>

