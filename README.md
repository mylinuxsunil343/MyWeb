Web Development

# Properties of document object

When html document is loaded in the browser, it becomes a document object. It is the root element that represents the html document. It has properties and methods. By the help of document object, we can add dynamic content to our web page.

<a href="https://www.javatpoint.com/document-object-model">ref</a>

Ex: 
<code>

<script type="text/javascript">  
function printvalue(){  
    var name=document.form1.name.value;  
    alert("Welcome: "+name);  
}  
</script>  
  
<form name="form1">  
Enter Name:<input type="text" name="name"/>  
<input type="button" onclick="printvalue()" value="print name"/>  
</form>  

</code>

# Javascript - document.getElementById() method

The document.getElementById() method returns the element of specified id.

<code>

<script type="text/javascript">  
function getcube(){  
var number=document.getElementById("number").value;  
alert(number*number*number);  
}  
</script>  
<form>  
Enter No:<input type="text" id="number" name="number"/><br/>  
<input type="button" value="cube" onclick="getcube()"/>  
</form>  

</code>