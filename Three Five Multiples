/*Using the JavaScript language, have the function ThreeFiveMultiples(num) 
return the sum of all the multiples of 3 and 5 that are below num. For example: 
if num is 10, the multiples of 3 and 5 that are below 10 are 3, 5, 6, and 9, 
and adding them up you get 23, so your program should return 23. The integer being passed will be between 1 and 100. */

function ThreeFiveMultiples(num) { 
    var arr = [];
    var tot=0;
   for(var i=num-1; i>1; i--){
        if(i%5===0 || i%3===0){
            arr.push(i);
        }
    }
    for(var i=0; i<arr.length; i++){
        tot = tot+ arr[i];
    }
    return tot;
}
