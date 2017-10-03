# vHIV
An HIV vaccine (preliminary). -- This version shows more clearly the symmetry between creating a glycosylated HIV neutralizing molecule (see aequorea/zHIV) and using designed-in glycans to create an epitope focused vaccine.
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
I wondered if it was possible to get the immune system to make more antibodies like N6 by making a vaccine. When I had the glycodesign software pick glycosylation sites on the N6 fragment, I did it with the fragment bound to gp120 to avoid glycosylating the binding pocket. Maybe a good way to make a vaccine would be to design glycans into gp120 such that they avoid the binding pocket. It's a different method of "epitope focusing." Maybe this is something we should be looking into, not just for HIV, but for other things as well. Find the conserved region on a virus, and use glycodesign to focus on it.
</p>
<p>
I call this design "preliminary" because I don't know which version of gp120 would work the best. It would be great to come up with something that works even better than N6 which only neutralizes 98% of isolates it was tested against. It might be nice to know something about the structures of the isolates that N6 doesn't work on and whether or not simply removing the light chain from N6 allows binding to some of these isolates. It might also be interesting to see what kinds of antibodies are made when isolates that can't bind N6 are used as a base for epitope focused design. There may be something about the local geometry in the vicinity of the CD4 binding that serves to encourage antibodies that are more broadly neutralizing.
</p>
<p>
Work has been proceeding along these lines using gp120's built in glycosylation sites and selective deglycosylation in the vicinity of the CD4 binding site (doi:10.1016/j.celrep.2017.04.013). Gp120 trimers that are completely glycosylated showed little immunogenicity. If however, glycans in the vicinity of the CD4 binding site were removed, the trimers became immunogenic. The nature of the antibody binding in the selective deglycosylation experiments was not sufficiently characterized to determine if any were single chain binders, although there were some indications of neutralization broadness.
</p>
<p>
I should also mention that epitope focusing by attaching an antigen fragment to a protein scaffold for display to the immune system has been done previously (doi:10.1038/nature12966).
</p>
