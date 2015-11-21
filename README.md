## CPR
A light weight color picker

Usuage:

cpr(options)

###Example
```javascript
cpr({
	palette: ['#ffffff', '#eeeeee', '#dddddd'],
	click: function(color){
		alert('color clicked ' + color)
	},
	focus: function(){
		//got focus
	},
	blur: function(){
		//lost focus
	}
});
```