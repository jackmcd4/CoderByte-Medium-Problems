/*Using the JavaScript language, have the function TripleDouble(num1,num2)
take both parameters being passed, and return 1 if there is a straight triple
of a number at any place in num1 and also a straight double of the same number in num2. 
For example: if num1 equals 451999277 and num2 equals 41177722899, then return 1 because
in the first parameter you have the straight triple 999 and you have a straight double,
99, of the same number in the second parameter. If this isn't the case, return 0.*/

function TripleDouble(num1,num2) { 
var arr =num1.toString().split("");
  var num =0;
  for(var i=0; i<arr.length; i++){
    if(arr[i]===arr[i+1] && arr[i]===arr[i+2]){
      num = arr[i];
      break;
    }
  }
var arr2 =num2.toString().split("");
  for(var i=0; i<arr2.length; i++){
    if(arr2[i]===arr2[i+1] && arr2[i]===num){
      return 1;
    }
  }
  return 0;
}
