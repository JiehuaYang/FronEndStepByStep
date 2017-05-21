1 If you quote some other font-family from google front and at the same time you want to have bold style,you must guarantee have <link href="https://fonts.googleapis.com/css?family=Source+Sans+Pro:400,700" rel="stylesheet"> rather than only <link href="https://fonts.googleapis.com/css?family=Source+Sans+Pro" rel="stylesheet">

2 In order to adapt to different size of browser ,use 
body{
	border:20px solid #bdc3c7;
	max-width: 700px;
	width: 80%;
	margin:20px auto;
	font-family: 'Source Sans Pro', sans-serif;
	padding:  20px;

}
and use em(relative to parent element)  rem (relative to root element I think it better than em)
3 If I put h2 into a div class  then make the font -size :2.0rem ,it is different from only use h2.I don't know why.

4 https://css-tricks.com/examples/hrs/ can be used to adjust the hr style.