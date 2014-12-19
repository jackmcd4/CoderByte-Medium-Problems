/*Using the JavaScript language, have the function CaesarCipher(str,num)
take the str parameter and perform a Caesar Cipher shift on it using the num 
parameter as the shifting number. A Caesar Cipher works by shifting each letter
in the string N places down in the alphabet (in this case N will be num). 
Punctuation, spaces, and capitalization should remain intact.
For example if the string is "Caesar Cipher" and num is 2 the output should be "Ecguct Ekrjgt"*/

function CaesarCipher(str,num) { 
    var arr =[];
    var re = /[a-z]/i;
    for(var i=0; i<str.length; i++){
        if(str[i].match(re)){
            arr.push(str.charCodeAt(i)+num);
        }
        else{
            arr.push(str.charCodeAt(i));
        }
    }
    for(var i=0; i<arr.length; i++){
        arr[i] = String.fromCharCode(arr[i]);
    }
    return arr.join("");
}
