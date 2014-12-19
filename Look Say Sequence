/*Using the JavaScript language, have the function LookSaySequence(num) 
take the num parameter being passed and return the next number in the sequence
according to the following rule: to generate the next number in a sequence read 
off the digits of the given number, counting the number of digits in groups of 
the same digit. For example, the sequence beginning with 1 would be: 1, 11, 21, 1211, ...
The 11 comes from there being "one 1" before it and the 21 
comes from there being "two 1's" before it. So your program should return the next number in the sequence given num. */

function LookSaySequence(num) { 
var arr = num.toString().split("");
var arr2=[];  
  for(var i=0; i<arr.length; i++){
    if(arr[i+1]!==arr[i]){
      arr2.push(1, arr[i]);
    }
    if(arr[i+1]===arr[i] && arr[i+2]===arr[i]){
      arr2.push(3, arr[i]);
      i+=2;
    }
    if(arr[i+1]===arr[i]){
      arr2.push(2, arr[i]);
      i+=1;
    }
  }
return arr2.join("");
}
