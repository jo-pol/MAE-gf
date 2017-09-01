### Contents
* [Ground names](#ground-names)
* [Stitches](#stitches)
* [Tiling](#tiling)
* [Footsides](#Footsides)

### Ground names
Unfortunately grounds do not have one unique name. Not even in one language. Also, the same name is used for different grounds. To make naming even more difficult, Groundforge does not make a difference in Torchon or Flemish grounds.    
Example: The picture shows the working-scheme's of one unit of _Slavic rose ground_ and one unit of _Fond au cinq trous_. Groundforge gives the same [result][ex-5G].           
![rose-cinq][pic-r5g]    

### Stitches
Names of stitches used in this wiki:
* Cross only. In working scheme's coloured in grey.    
* Half stitch = (twist if not already done), cross, twist. Coloured green.       
* Cloth stitch = cross, twist, cross. Coloured purple.        
* Whole stitch & twist = (twist if not already done), cross, twist, cross, twist. Coloured red.   
* Plaits = (twist,) cross, twist, cross, twist, cross, twist, cross (, twist), .... . Coloured blue.

Sometimes, onorthodox stitches are used, like `Cross only`. (Examples will be in this wiki.)
    
![pic-tct]Groundforge has rules as which stitch-code gets what colour, according to the Belgian colour code. In this wiki, the pair-diagrams will not always show the Belgian colour code, due to the following, illustrated with an example. 
Suppose, we wish to work on the example above. The whole stitch & twist in the middle can be specified several ways. We prefer to use `ctc B1=tctct`, see [here][ex-tctct]. However, doing so, Groundforge colours this stitch in black in the pair-diagram (the left one). If we wish to see a red stitch, we have to use `ctc A1=ctcr A2=ctcr B1=ctct`, see [here][ex-ctct].

We have tried `ctctclllllctctc` as a substitute for picots. Groundforge needs some time to generate this, and the result is not as expected.

### Tiling
Most examples use the `brick` parameter setting, drawn as a blue rectangle when shown, since it's less ID's to specify. Some scheme's do not have a working brick diagram, so, of course, a `checkers` parameter is used, drawn as a red rectangle when shown.

Please note, that the ID's needed for the stitches shift somehow. `A1` is not in the upperleft corner of the shown units in the examples.

### Footsides
The examples provided focus on just elements of the grounds. No attention is paid to footsides. This may sometimes lead to tilted figures. 




[pic-tct]: https://github.com/MAETempels/MAE-gf/blob/master/images_wt/gf-tctct.png
[pic-r5g]: https://github.com/MAETempels/MAE-gf/blob/master/images_wt/gf-slaaf-vierge.png

[ex-tctct]: https://d-bl.github.io/GroundForge/index.html?m=88%2011%3Bbricks%3B16%3B16%3B0%3B0&s1=ctc%20B1%3Dtctct
[ex-ctct]: https://d-bl.github.io/GroundForge/index.html?m=88%2011%3Bbricks%3B16%3B16%3B0%3B0&s1=ctc%20B1%3Dctct%20A2%3Dctcr%20A1%3Dctcr
[ex-5G]: https://d-bl.github.io/GroundForge/index.html?m=5831%20-4-7%3Bbricks%3B16%3B16%3B0%3B0&s1=ct%20A1%3Dctct%20C1%3Dctct

