# vHIV
An HIV vaccine molecule. -- This version shows more clearly the symmetry between creating a glycosylated HIV neutralizing molecule (see aequorea/zHIV) and using designed-in glycans to create an epitope focused vaccine.
<p align="center">
  <img src="vHIV2.png" width="500"/>
</p>
<p align="center">
  vHIV (raspberry and red) shown bound to the zHIV N6 heavy chain fragment (blue)
</p>
<p align="center">
  Potential glycosylation sites selected by gly21 software on the gp120 monomer are shown in red.
</p>
<p align="center">
  (based on 5TE4.PDB -- DOI:10.1016/j.immuni.2016.10.027)
</p>
<p>
There may be more to making a vaccine that would encourage broadly neutralizing antibodies like N6 to arise than making a single type of vaccine molecule and doing a single vaccination. There is significant "affinity maturation" of the binding site and a significant number of mutations must occur for broadly neutralizing antibodies to arise. Since HIV itself has been seen to evolve broadly neutralizing antibodies that one might like to see as a response to an infection after immunization, one way to develop an immunization strategy that would result in these kinds of antibodies is to use HIV's behavior in the course of an infection as a model for the strategy.
</p>
<p>
One HIV behavior that may be of interest is that HIV early entrants, or "pioneers," have statistically fewer N-linked glycosylation sites and may have fewer glycans than HIV viruses that have been part of an infection for a while. Maybe this is part of the co-evolution of HIV with the antibodies that has been seen in cases where broadly neutralizing antibodies have arisen in the course of an HIV infection. To imitate this behavior we might like to see immunization as a series of vaccine molecules. In this series of molecules, start with fewer glycans and a more accessible CD4 binding site and progress to more glycans and a less accessible CD4 binding site. 
</p>
<p>
Another HIV behavior that may be of interest is that HIV varies the protein surface in areas that neighbor the CD4 binding site while leaving the binding site itself relatively constant. Since the antibodies are evolving to bind the area better, one imagines that it might be easier to improve the affinity to an area that is not changing. If the surface is changing, binding might initially improve, but when the surface changes, binding would likely drop to a lower efficiency. Thus binding to an area that doesn't change might continually improve, while binding to an area that changes might not. So it may also be important in the series of vaccine molecules to vary the protein surface in the vicinity of the desired binding site to better focus the antibody on it.
</p>
<p>
So based on the behavior of HIV itself, we have a method of vaccine design that uses glycodesign based epitope focusing with variational sharpening. Use glycans to provide the "broad strokes" for focusing on the region of interest, and use variation of the protein surface in the immediate vicinity of the region to more sharply focus the antibodies on it. It would be very nice to find out if this technique could be made to work.
</p>
