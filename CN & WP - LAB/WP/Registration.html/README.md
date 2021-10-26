
Search or jump to…
Pull requests
Issues
Marketplace
Explore
 
@19wh1a1238 
it-19wh1a1234
/
III-ITA-LAB
Public
1
00
Code
Issues
Pull requests
Actions
Projects
Wiki
Security
Insights
III-ITA-LAB/CN&WP LAB/Registration.html
@it-19wh1a1234
it-19wh1a1234 Add files via upload
Latest commit 6bc57b3 22 days ago
 History
 1 contributor
60 lines (55 sloc)  1.42 KB
   
<Html>  
 
<style> 
body {
  background-image: url("background6.jpg");
  background-repeat: no-repeat, repeat;
   background-attachment: fixed;
  background-size: cover;
  
}
</style>
<br>  
<br>  
<form>  
  <div style = "float:left;width:100%">
  <center><h1 style="color:Black;">FEEDBACK</h1></center>
     </br>
</br></br>
<center><label> Firstname </label>         
<input type="text" name="firstname" size="15"/> <br> <br>  
  
<label> Lastname: </label>         
<input type="text" name="lastname" size="15"/> <br> <br>  
<label>Date of Event: </label>
<input type="date" name="date" size="15"/> <br> <br>  
<label>   
Mode of payment :  
</label>   
<select>  
<option value="Cash"></option>
<option value="Cash">Cash</option>  
<option value="UPI">UPI</option>  
<option value="Net Banking">Net Banking</option>  
<option value="Card">Card</option>    
</select>  
  
<br>  
<br>  
<label>   
Gender :  
</label><br>  
<input type="checkbox" name="male"/> Male <br>  
<input type="checkbox" name="male"/> Female <br>   
<br>  
<br>  
  
<label>   
Phone :  
</label>  
<input type="text" name="country code"  value="+91" size="2"/>   
<input type="text" name="phone" size="10"/> <br> <br>  
Address  
<br>  
<textarea cols="60" rows="3" value="address">  
</textarea>  
<br> <br>  
<a href="thankyou.jpg"><input type="button" value="Submit"/></a> </center>
</form>  
</body>  
</html>  
