Function (value) { 
     var hex  = value.toString(); 

     var str = ''; 

     for (var n = 0; n < hex.length; n += 3) { 

           str += String.fromCharCode(parseInt(hex.substr(n, 2), 16)); 

     } 

  return str.substring(0,2); 

} 
