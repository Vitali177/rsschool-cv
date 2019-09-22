# CV

##	Hello, I am Skrabatun Vitali
1. **Contact in** 
 + email (v.skrabatun@gmail.com) 
 + telegram (@vitali177) 
2. **Goal**: to create intuitive and beautiful sites.
3. **Skills**: 
 + HTML+CSS+JS
 + basic C++
4. *Code example*:  This is a part  of code of my mini-game

```javascript
var view = {
	displayMessage: function(msg) {
		var messageArea = document.getElementById('messageArea');
		messageArea.innerHTML = msg;	
	},

	displayHit: function(location) {
		var cell = document.getElementById(location);
		cell.setAttribute('class', 'hit');
	},

	displaySank: function(ship) {
		for (var i = 0; i < ship.locations.length; i++)  { 

			let location = ship.locations[i];
			console.log(location);

			var cell = document.getElementById(location);
			cell.setAttribute('class', 'sank');  
		}

	console.log(ship);
	},

	displayMiss: function(location) {
		var cell = document.getElementById(location);
		cell.setAttribute('class', 'miss');
	}
};  
```
5. **Experience**:
 + course-work on C++
 + tasks on HTML/CSS in codecademy

