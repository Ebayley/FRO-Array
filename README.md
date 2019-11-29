# FRO-Array

# js
let waarde=document.getElementById("menukaart");

let pasta = [ 
    
" Macaroni met ham en kaas", 
" Spaghetti met ham en kaas", 
" Tagliatelli met ham en kaas", 
" Spaghetti met spinazie en room", 
" Macaroni met spinazie en room", 
" Tagliatelli met spinazie en room", 
" Spaghetti met gehakt-tomatensaus en kaas", 
" Macaroni met gehakt-tomatensaus en kaas", 
" Tagliatelli met gehakt-tomatensaus en kaas", 
" Spaghetti met spekjes, spinazie en room", 
" Spaghetti met courgette en tomatensaus", 
" Macaroni met courgette en tomatensaus", 
" Tagliatelli met courgette en tomatensaus", 
" Lasagne met courgette en tomatensaus", 
" Lasagne met room, doperwten en tomatensaus", 
" Lasagne met spinazie en tomatensaus en kaas"  ];

let pasta1 = pasta[0];
let pasta2 = pasta[1];

console.log(pasta.length);

pasta.push(" Einde menu ");
pasta.unshift("Pasta menu: ");
 
for (let count = 0; count < pasta.length; count++) {
    console.log(pasta[count]);
}

waarde.innerHTML=pasta;

# Html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Array</title>
</head>

<body>
    
    <div id = "menukaart">

    </div>

    
 
<script src="Array.js"></script>
</body>
</html>
