Map and Object both are store values as key-values pair and both store unique key

Differences - 
In Map keys can be of any data type like string, number, symbols, function 
In Object keys can be of either string or symbol or if u define it in any other data type then it will convert it into an string 

In Map order of insertion is preserved even when u iterate over entries of map the entries should be in order 
In Object  the order of insertion is not guaranteed. while modern js engines generally preserve insertion order