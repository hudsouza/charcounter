# charcounter
An easy way to make a character count down for your form inputs with jQuery

* * *

## How it works:
The jQuery finds everything with a "characterCount" class inside a form and get each ID and maxLength;
It inserts the value of the maxLength inside the span tag;
Onkeyup it counts the value of the input and subtracts from the maxlength

## Notes:
All fields must have a "characterCount" class. It can be a input, textarea...
You must declare a maxLength, otherwise the value will be undefined
The TEXT FIELD ID and the SPAN CLASS must be the same.
e.g.: 
`<input type='text' id='**name**'>`
`<span class='**name**'>`
