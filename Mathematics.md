### Contents
* [Spider formula's](#spider-formulas)

### Introduction
On this page some mathematics for those who like that. Including formula in pseudo-code.

### Spider formula's
As shown in the [spiders][spiders-page] article, spider-matrices can be generated.  
In all formula N is the number of legs on one side. The spider will thus have 4N legs.       
Spaces have to be ingored. The sign & means "concatenate": "A" & "B" => "AB". The "" are omitted.    

For the **traditional spider in a square**, the following code will do the trick. N>=2.

`5 & (for i=1 to 5: -) & 5 & (for i=1 to 5: -)               `     
`-C & (for i=1 to N-2: D) & 632 & (for i=1 to N-2: A) & B    `           
`(for j=1 to N-2:                                                `      
`5 & (for i=1 to N: 6) & 3 & (for i=1 to N: 2)               `      
`next j)                                                     `      
`5 & (for i=1 to N: 6) & - & (for i=1 to N: 2)               `                   




[spiders-page]: https://github.com/MAETempels/MAE-gf/wiki/Spiders