# Preeti translation
```javascript
$('body').on('input', '.convert-preeti', function (event) {
	var text = this.value;
	var convert = setUnicodePreeti(text);
	this.value = convert;

	return true;
});
// Example: sf]bh]g = कोदजेन
```

![Nepali preeti to unicode](https://github.com/codexen/nepali-typing/blob/master/guide/keyboardlayout-traditional.jpg "Traditional translation")

# Romanize translation
```javascript
$('body').on('keypress', '.convert-romanize', function (event) {
	return setUnicode(event,this);
});
// Example: kodejen = कोदजेन
```

![Nepali romanized translation](https://github.com/codexen/nepali-typing/blob/master/guide/keyboardlayout-romanized.jpg "Romanized translation")