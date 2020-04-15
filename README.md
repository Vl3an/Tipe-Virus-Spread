# Tipe-Virus-Spread
![Virus](https://d1nhio0ox7pgb.cloudfront.net/_img/o_collection_png/green_dark_grey/256x256/plain/virus.png)

The goal is to simulate a virus propagation in a simple then a more precise way but also at different scales to compare then study the results. 
- We are using `Python 3` and some librairies such as
   * `Pygame`
   * `Numpy`
   * `MatPlotLib`
   
![py](https://pic.clubic.com/v1/images/1501281/raw)
   
## ToDo
Study the real cases of viruses, in particular corona, to compare and try to get closer to reality.

### Work at different scales:
**global / national**: transmission by migrations, modulating the probability according to each region in accordance with the degrees of development and fight of the virus.
**city**: transmission by routes, contact between individuals and according to groups of individuals (families, work teams, relationships ...)
**local**: simulate transmission between individuals treated individually. 2D model (cellular automata, percolation?) And more elaborate model (article from the world)

* vary the population and virus **parameters**:
   * population density.
   * immunity
   * movements. (local / city scale)
   * lethality.
   * contagious virus
   * cure rate
   * incubation time
   * outdoor survival (local scale, even city life ...)

### Graphs 
Study / display those propagation graphs in the population:
   * (*dead*,*healed* and *cured*) by *time*
   * *path traveled by the virus* according to *containment*
   * (*dead*,*healed* and *cured*) according to *density*, *lethality*, *immunity* 
   * ...
We also have to find (if there is one), **critical probabilities** / rate that separates two types of virus progression or weigh the influence of each parameter.
