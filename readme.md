<!doctype html>
<html>
<head>
<meta charset="utf-8">
<title>�Ĵ�Сд</title>
<script>
function shuaxin(){
window.location.reload();	
}
function gaixiao() {  
    var c=document.getElementById('tx1').value;
var odiv1=document.getElementById('div1').innerHTML;
 var i=odiv1.length;
var o=i-c;
var daxie=odiv1.substr(0,[o]);

var ob=document.getElementById('div1').innerHTML=daxie;
}  


</script>
</head>

<body>
<p>��������ӵ����ڼ����ַ���ʼɾ�������Ԫ�أ�������ʼ��ť</p>
<input type="button" value="��ʼ" onClick="gaixiao()">
<input type="button" value="ˢ��" onClick="shuaxin()">
<input  id="tx1" type="text"  >
<div id="div1">Welcome to the underground city</div>
</body>
</html>