/*Using the JavaScript language, have the function PalindromeTwo(str)
take the str parameter being passed and return the string true if the parameter is a palindrome, 
(the string is the same forward as it is backward) otherwise return the string false. 
The parameter entered may have punctuation and symbols but they should not affect whether the string is in fact a palindrome.
For example: "Anne, I vote more cars race Rome-to-Vienna" should return true. */

function PalindromeTwo(str) { 
var re = /[a-zA-Z]/;
  var arr = [];
  for(var i=0; i<str.length; i++){
    if(str.charAt(i).match(re)){
      arr.push(str.charAt(i).toLowerCase());
    }
  }
    var hold = arr.join("");
    arr = arr.reverse().join("");
  if(arr==hold){
    return true;
  }
  else{
    return false;
  }
}
