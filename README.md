# form.login
<!DOCTYPE html>
<html>
<head>
	<title>form.html</title>
</head>
<body>

<table border="1" cellpadding="5" cellspacing="0" align="center">
<form>
	<tr>
	  <td>
	<label for="username">username :</label>
	<input type="text" id="username">
    </tr>
      </td>
 
	<br>

	<tr>
		<td>
	<label for="x">password :</label>
	<input type="password" id="x">
		</td>
	</tr>

	<br>

	<tr>
		<td colspan="2">
	<input type="radio" id="pria" name="jeniskelamin"> <label for="pria">pria</label>
	<input type="radio" id="wanita" name="jeniskelamin"> <label for="wanita">wanita</label>
		</td>
	</tr>

	<br>
	
	<tr>
		<td>
	<input type="checkbox" id="musik" name="hobi"> <label for="musik">musik</label>
	<input type="checkbox" id="olahraga" name="hobi"> <label for="olahraga">olahraga</label>
	<input type="checkbox" id="baca" name="hobi"> <label for="baca">baca</label>
		</td>
	</tr>

	<br>

	<tr>
		<td>
	<textarea></textarea>
		</td>
	</tr>
    
    <br>

    <tr>
    	<td>
    	<select>
    	<option>Jakarta</option>
    	<option>Bogor</option>
    	<option>Depok</option>
    	<option>Tangerang</option>
    	<option>Bekasi</option>
    	</select>
    	</td>
    </tr>
    	   
	<tr>
		<td>
	<button type="submit">kirim</button>
		</td>
	</tr>

</form>
</table>

</body>
</html>
