### Contents
* [Introduction](#introduction)
* [Spider formula's](#spider-formulas)
* [To big matrix](#to-big-matrix)
<br><br>

### Introduction
On this page some mathematics for those who like that. Including formula in pseudo-code.
<br><br>

### Spider formula's
As shown in the [spiders][spiders-page] article, spider-matrices can be generated.  
In all formula N is the number of legs on one side. The spider will thus have 4N legs.       
Spaces have to be ingored. The sign & means "concatenate": "A" & "B" => "AB". The "" are omitted.
<br>   
For the **traditional spider in a square**, the following code will do the trick. N>=2.      
Brick:    
```  
5 & (for i=1 to N: -) & 5 & (for i=1 to N: -)               
-C & (for i=1 to N-2: D) & 632 & (for i=1 to N-2: A) & B              
(for j=1 to N-2:                                                     
5 & (for i=1 to N: 6) & 3 & (for i=1 to N: 2)                    
next j)                                                          
5 & (for i=1 to N: 6) & - & (for i=1 to N: 2)                 
```    
<br>

### To big matrix
<img align="left" src=https://github.com/MAETempels/MAE-gf/blob/master/images/gf-sn-nott.png/> We wished to find the matrix-scheme for the crossed-snowflake-in-a-square. Just putting te snowflake in the square won't work, since the snowflake requires 11 "nodes", whereas the square has 9 nodes inside. So, the square has to be enlarged. The matrix in the picture follows the rules for matrices, but the tiles are too big for Groundforge to handle. 
<br><br><br><br><br><br><br><br> 
        


[spiders-page]: https://github.com/MAETempels/MAE-gf/wiki/Spiders

[to-big-sn]: https://github.com/MAETempels/MAE-gf/blob/master/images/gf-sn-nott.png