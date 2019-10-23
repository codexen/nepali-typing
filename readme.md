#Preeti translation
```javascript
$('body').on('input', '.convert-preeti', function (event) {
	var text = this.value;
	var convert = setUnicodePreeti(text);
	this.value = convert;

	return true;
});
```

#Romanize translation
```javascript
$('body').on('keypress', '.convert-romanize', function (event) {
	return setUnicode(event,this);
});
```