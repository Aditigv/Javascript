# Javascript
*/Google Slide Link for Online Calc : https://docs.google.com/presentation/d/1WyGA6sj7IBtX5ny3r5_vihSXYUUKJIr0t3XlEpGt6ks/edit?usp=sharing
*/Google Slide Link for HTTP JSON SERVER : https://github.com/Aditigv/Javascript/blob/d928e51c76b3f12f8747826492d7bcbd345f6e36/Project%20HTTP%20JSON%20API%20SERVER.pdf
_____________________________________________________________________________________________________________________________
-----------------------------------------------------------------------------------------------------------------------------
*/Javascript Code for Online calculator basic operations
-----------------------------------------------------------------------------------------------------------------------------

-----------------------------------------------------------------------------------------------------------------------------
<!DOCTYPE html>	
<html>
<body>
<script>
function main(presskey) 
{
   var calc= document.getElementById("screen").value;
   if (presskey == '=')
      document.getElementById("screen").value =calc + "=" + eval(calc);
   else if (presskey == 'Clear')
      document.getElementById("screen").value = '';
   else
      document.getElementById("screen").value = calc + presskey;
}

</script>
  ----------------
 
<table border="2" cellspacing= 1 cellpadoing=1 >

<tr> 
<th colspan=5 rowspan=1><br><input type="text" id=screen></br></th> 
</tr>	

<TH colspan=2 rowspan=1>
<button type="button" onclick="main('Clear')">Clear</button>
</TH>
<TH>
<button type="button" onclick="main('=')">=</button>
</TH>
<TH>
<button type="button" onclick="main('(')">(</button>
</TH>
<TH>
<button type="button" onclick="main(')')">)</button>
</TH>
</TR>
-----------------------------------------------------------
<TH colspan=1 rowspan=1>
<button type="button" onclick="main('*')">*</button>
</TH>
<TH>
<button type="button" onclick="main('/')">/</button>
</TH>
<TH>
<button type="button" onclick="main('+')">+</button>
</TH>
<TH>
<button type="button" onclick="main('-')">-</button>
</TH>
<TH>
<button type="button" onclick="main('.')">.</button>
</TH>
</TR>
-------------------------------------------------------------
<TH>
<button type="button" onclick="main('1')">1</button>
</TH>
<TH>
<button type="button" onclick="main('2')">2</button>
</TH>
<TH>
<button type="button" onclick="main('3')">3</button>
</TH>
<TH>
<button type="button" onclick="main('4')">4</button>
</TH>
<TH>
<button type="button" onclick="main('5')">5</button>
</TH>
</TR>
------------------------------------------------------------
<TH>
<button type="button" onclick="main('6')">6</button>
</TH>
<TH>
<button type="button" onclick="main('7')">7</button>
</TH>
<TH>
<button type="button" onclick="main('8')">8</button>
</TH>
<TH>
<button type="button" onclick="main('9')">9</button>
</TH>
<TH>
<button type="button" onclick="main('10')">0</button>
</TH>
</TR>
</table> 
</body> 
</html>

------------------------------------------------------------------

---------------oooooooo-------------------------------------------
