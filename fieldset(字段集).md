``` html
<!DOCTYPE html>
<html>
<head>
	<title></title>
	<meta charset="utf-8">
	<style>
	form{width:280px;height:160px;border:2px solid grey;
    border-radius:6px;padding:10px;background-color:#85C1E9}
    </style>
</head>
<body>
	<form id="radio_form">
		<fieldset>
		<legend>你愛吃什麼水果?</legend>   
		<input type="radio" name="fruit" value="apple" > apple<br>
		<input type="radio" name="fruit" value="banana" > banana<br>
		<input type="radio" name="fruit" value="lemmon" > lemmon<br>
		<input type="radio" name="fruit" value="tomato" > tomato<br>
        
        <input type="submit" value="送出">
        <input type="reset"  value="清除">
        </fieldset>
	</form>
	<br>

	<form id="checkbox_form">
		<fieldset>
		<legend>你喜歡的水果</legend>
		<input type="checkbox" name="fruit1" value="apple" tabindex="2"> apple<br>
		<input type="checkbox" name="fruit2" value="banana" tabindex="4"> banana<br>
		<input type="checkbox" name="fruit3" value="lemmon" tabindex="1"> lemmon<br>
		<input type="checkbox" name="fruit4" value="tomato" tabindex="3"> tomato<br>

		<input type="submit" value="送出">
        <input type="reset"  value="清除">
    </fieldset>
	</form>

</body>
</html>
<!-- <legend> -->
<!-- <fieldset></fieldset> -->
```
 ![image](https://github.com/4060E046/PNG-JPG-GIF/blob/master/fieldset(%E5%AD%97%E6%AE%B5%E9%9B%86).PNG)
