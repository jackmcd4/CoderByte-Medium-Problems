/*Using the JavaScript language, have the function NumberEncoding(str)
take the str parameter and encode the message according to the following rule: 
encode every letter into its corresponding numbered position in the alphabet. 
Symbols and spaces will also be used in the input. For example: if str is "af5c a#!" 
then your program should return 1653 1#!. */

function NumberEncoding(str) { 
  var re = /[a-z]/i;
  var newStr=[];
  for(var i=0; i<str.length; i++){
    if(str[i].match(re)){
      newStr.push(str.charCodeAt(i)-96);
    }
    else{
      newStr.push(str[i]);
    }
  }
  return newStr.join("");
  }
