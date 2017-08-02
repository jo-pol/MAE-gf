### Contents
* [Ground names](#ground-names)
* [Stitches](#stitches)
* [Tiling](#tiling)
* [Braids](#braids)

### Ground names
Unfortunately grounds do not have one unique name. Not even in one language. Also, the same name is used for different grounds. 

### Stitches
Names used in this wiki:
* Cross only
* Half stitch = (twist if not already done), cross, twist    
* Cloth stitch = cross, twist, cross     
* Whole stitch & twist = (twist if not already done), cross, twist, cross, twist

Sometimes, onorthodox stitches are used, like `Cross only`. (Examples will be in this wiki.)

![pic-tct]Groundforge has rules as wich stitch-codes get what colour, according to the Belgian colour code. In this wiki, the pair-diagrams will not always show the Belgian colour code, due to the following, illustrated with an example. 
Suppose, we wish to work on the example above. The whole stitch & twist in the middle can be specified several ways. We prefer to use `ctc B1=tctct`, see [here][ex-tctct]. However, doing so, Groundforge colours this stitch in black in the pair-diagram (the left one). If we wish to see a red stitch, we have to use `ctc A1=ctcr A2=ctcr B2=ctct`, see [here][ex-ctct].

### Tiling
Most examples use the `brick` parameter setting, since it's less ID's to specify. Some scheme's do not have a working brick diagram, so, of course, a `checkers` parameter is used.

Please note, that the ID's needed for the stitches shift somehow. `A1` is not in the upperleft corner of the shown units in the examples.

### Braids
Groundforge can do braids, however, we have to feed it with a matrix covering the complete width of the braid, including footsides. This will lead to a considerable amount of ID's to specify in the stitches section. Therefor, the examples provided focus on just elements of the grounds. No attention is paid to footsides.




[pic-tct]: https://github.com/MAETempels/MAE-gf/blob/master/images/gf-tctct.png

[ex-tctct]: https://d-bl.github.io/GroundForge/index.html?m=88%2011%3Bbricks%3B16%3B16%3B0%3B0&s1=ctc%20B1%3Dtctct
[ex-ctct]: https://d-bl.github.io/GroundForge/index.html?m=88%2011%3Bbricks%3B16%3B16%3B0%3B0&s1=ctc%20B1%3Dctct%20A2%3Dctcr%20A1%3Dctcr