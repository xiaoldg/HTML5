```html
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
		<b>你愛吃什麼水果?</b><br>
		<input type="radio" accesskey="a" name="fruit" value="apple" tabindex="1"> apple(alt-a)<br>
		<input type="radio" accesskey="b" name="fruit" value="banana" tabindex="4"> banana(alt-b)<br>
		<input type="radio" accesskey="l" name="fruit" value="lemmon" tabindex="3"> lemmon(alt-l)<br>
		<input type="radio" accesskey="t" name="fruit" value="tomato" tabindex="2"> tomato(alt-t)<br>
        
        <input type="submit" value="送出">
        <input type="reset"  value="清除">
	</form>
	<br>

	<form id="checkbox_form">
		<b>你喜歡的水果</b><br>
		<input type="checkbox" name="fruit1" value="apple" checked> apple<br>
		<input type="checkbox" name="fruit2" value="banana"> banana<br>
		<input type="checkbox" name="fruit3" value="lemmon"> lemmon<br>
		<input type="checkbox" name="fruit4" value="tomato"> tomato<br>

		<input type="submit" value="送出">
        <input type="reset"  value="清除">
	</form>

</body>
</html>
```
