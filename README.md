## CPR
A light weight color picker

Usuage:

cpr(options)

###Example
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

###options:

**palette**
palette to show

**click**
click callback

**focus**
focus callback

**blur**
blur callback