# The Great RGB Color Guessing Game
> How well do you know RGB values? Test your skills today!

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)
* [Features](#features)
* [Inspiration](#inspiration)
* [Contact](#contact)

## General info
The Great RGB Color Guessing Game is a fun way to test your RGB value skills! Start with a value and try to guess which color swatch matches. Play on easy mode, hard mode, or reset the board at any time.

## Technologies
* HTML5
* CSS
* JavaScript

## Setup
Fork and clone this repo, run a local server, and you're ready to play!

## Code Examples
```javaScript
for(let i = 0; i < modeButtons.length; i++) {
	modeButtons[i].addEventListener("click", function() {
		modeButtons[0].classList.remove("selected");
		modeButtons[1].classList.remove("selected");
		this.classList.add("selected");	
		this.textContent === "Easy" ?	numSquares = 3 : numSquares = 6;
		reset();
	}
```

```javascript
function changeColors(color) {
	for(let i = 0; i < squares.length; i++) {
		squares[i].style.background = color;
	}
}
```

## Features
* Guess which color swatch matches a randomly generate RGB value
* Play on easy mode (guess from 3 color swatches) or hard mode (guess from 6 color swatches)
* Reset the board with a new RGB value at any time

## Status
Complete with the option to refactor and add features.

## Inspiration
I built The Great RGB Color Guessing Game to improve my JavaScript skills. I wanted to build something that would challenge me (at the time) while also producing something fun and usable. The ability to improve my RGB value recognition abilites was an added bonus!

## Contact
[Matt Long](https://www.linkedin.com/in/mattlong34/)

Feel free to contact me with any questions or suggestions!

