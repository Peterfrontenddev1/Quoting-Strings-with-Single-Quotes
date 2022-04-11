# Quoting-Strings-with-Single-Quotes

String values in JavaScript may be written with single or double quotes, 

as long as you start and end with the same type of quote.

Unlike some other programming languages, 

const doubleQuoteStr = "This is a string"; 

const singleQuoteStr = 'This is also a string';

The reason why you might want to use one type of quote over the other is if you want to use both in a string.
This might happen if you want to save a conversation in a string and have the conversation in quotes. Another use for it would be saving an <a> tag with various attributes in quotes, all within a string.
const conversation = 'Finn exclaims to Jake, "Algebraic!"';
const conversation = 'Finn exclaims to Jake, "Algebraic!"';
const goodStr = 'Jake asks Finn, "Hey, let\'s go on an adventure?"'; 
const badStr = 'Finn responds, "Let's go!"';

  Here badStr will throw an error.
  
In the goodStr above,
  
you can use both quotes safely by using the backslash \ as an escape character.

  Note: The backslash \ should not be confused with the forward slash /. They do not do the same thing.
  
Change the provided string to a string with single quotes at the beginning and end and no escape characters.
  
Right now, the <a> tag in the string uses double quotes everywhere. You will need to change the outer quotes to single quotes so you can remove the escape characters.
  
You should remove all the backslashes (\).
  
You should have two single quotes ' and four double quotes ".
  
const myStr = "<a href=\"http://www.example.com\" target=\"_blank\">Link</a>";
