html基本格式 http://120.114.133.91

```html
<!DOCTYPE html>
<html>
<head>
    <title>網頁標題</title>
    <meta charset="utf-8">
</head>
<body>

</body>
</html>
```

body 網頁主體
```
background=”” //背景圖片 
bgcolor=”” //背景顏色 
text=”” //本文文字顏色
```
br 強制換行

p 文字分段
```
align=”right” 
align=”center” 
align=”left” 
```
```
pre 原格式
hr 分隔線
h1~h6 文字標題
b 粗體字
i 斜體字
u 文字加底線
sup 上標籤
sub 下標籤
```

font 設定文字外觀
```
size=”” //字體大小 
face=”” //文字字型 
color=”” //顏色
```
```
符號	語法
<	&lt
>	&gt
&	&amp
“	&quot
&nbsp	不換行的空白
```
圖片
```
img
   src=”” //圖片連結 
   border=”” //圖片邊框 
   height=”” //圖片高度 
   width=”” //圖片寬度 
   title=”” //圖片註解 
alt=”” //圖片錯誤時顯示的文字
```


JavaScript
範例
```html
<script>
    dt = new Date();
    document.write(dt.toLocaleString());
</script>
```
```
script
src=”” //script單獨放在其他的檔案內，該檔案的URL
```

事件屬性	發生時機
```
onload	    載入網頁時
onclick	    按一下滑鼠時
ondblclick	雙擊滑鼠時
onmousedown	按下滑鼠時
onmouseup	放開滑鼠時
onmouseover	指標移動到物件上面時
onmousemove	指標在物件上移動時
onmouseout	指標移出物件時
```

