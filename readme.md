# Preeti translation
```javascript
$('body').on('input', '.convert-preeti', function (event) {
	var text = this.value;
	var convert = setUnicodePreeti(text);
	this.value = convert;

	return true;
});
```
Example:
sf]bh]g = कोदजेन



# Romanize translation
```javascript
$('body').on('keypress', '.convert-romanize', function (event) {
	return setUnicode(event,this);
});
```

Example:
kodejen = कोदजेन

![alt text](https://github.com/codexen/nepali-typing/guide/keyboardlayout-traditional.png "Traditional translation")
![alt text](https://github.com/codexen/nepali-typing/guide/keyboardlayout-romanized.png "Romanized translation")