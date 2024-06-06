```html
<!DOCTYPE html>
<html>
<head>
	<title>LED</title>
</head>
<body>
	<button id="0" class="led">Toggle LED 0</button>
	<button id="1" class="led">Toggle LED 1</button>
	<button id="2" class="led">Toggle LED 2</button>
	<button id="3" class="led">Toggle LED 3</button>
	<button id="9" class="led">all LEDs off</button>

    <script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.4/jquery.min.js">
    	
    </script>
    <script type="text/javascript">
    	$(document).ready(function(){
    		$(".led").click(function(){
    			var api_key="25UQC3UTBU5TGPEF";
    			// API Key
    			var field1 = $(this).attr('id');
    			rUr1="http://184.106.153.149/update?api_key="+api_key+"&field1="+field1;
    			$.get(rUr1);
    		});
    	});

    </script>
</body>
</html>

<!-- ThingSpeak -->
```
