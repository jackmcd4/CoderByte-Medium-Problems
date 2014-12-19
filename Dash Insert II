//Works in every case but with zero, should be an easy fix
/*Using the JavaScript language, have the function DashInsertII(str) 
insert dashes ('-') between each two odd numbers and insert asterisks ('*') between each two even numbers in str.
For example: if str is 4546793 the output should be 454*67-9-3. Don't count zero as an odd or even number.*/

function DashInsertII(num) { 
var arr =num.toString().split("");
  var arr2 =[];
  for(var i=0; i<arr.length; i++){
    if(arr[i]%2===0 && arr[i+1]%2===0){
      arr2.push(arr[i], "*");
    }
    else if(arr[i]%2!==0 && arr[i+1]%2!==0){
      arr2.push(arr[i], "-");
    }
    else{
      arr2.push(arr[i]);
    }
  }
  if(arr2[arr2.length-1]==="-" || arr2[arr2.length-1]==="*"){
    arr2.pop(arr2[arr2.length-1]);
  }
  return arr2.join("");
         
}
