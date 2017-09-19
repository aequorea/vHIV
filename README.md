# vHIV2
An HIV vaccine (preliminary). -- This version shows more clearly the symmetry between creating a glycosylated HIV neutralizing molecule (see zHIV) and using designed in glycans to create an epitope focused vaccine. The design is called "preliminary" because the crystal structure of the gp120 monomer is incomplete.
<p align="center">
  <img src="vHIV2.png" width="500"/>
</p>
<p align="center">
  vHIV (raspberry and red) shown bound to N6 heavy chain (blue)
</p>
<p align="center">
  Potential glycosylation sites selected by gly21 software on the gp120 monomer are shown in red.
</p>
<p align="center">
  (based on 5TE4.PDB -- DOI:10.1016/j.immuni.2016.10.027)
</p>
<p>
After seeing the zHIV neutralizer on my computer screen for the first time, one of the first questions that came to mind was whether or not it would be possible to make more molecules like that one. The neutralizer was derived from the N6 antibody, which aside from the fact that it can neutralize some 98% of all HIV isolates it was tested against, has the interesting property that the light chain had evolved in such a way that it essentially stayed out of the way with the majority of the binding interaction being between the heavy chain and HIV's gp120 protein. This feature of N6 was used to design the small molecule HIV neutralizer zHIV.
</p>
<p>
Although initally I was thinking along the lines of trying to find a way to do high speed screening of a combinitorial antibody library to find single chain binders, eventually I started to wonder if it would be possible to trick the immune system into making antibodies that bind mostly with one chain or the other. Then I began to think that maybe vaccine design is somehow the "inverse" of neutralizer design, where one creates the inverse by coating all parts of an antigen with the exception of the desired binding epitope with glycans. Thus one might manipulate the immunogenicity of that antigen such that the response would be a single chain binder.
</p>
<p>
It's easy enough to play this game using the crystal structure I used to do the zHIV neutralizer design. Just glycosylate gp120 instead of the antibody fragment leaving the portion of the gp120 to which the antibody is bound unglycosylated. This is shown above.
</p>
<p>
Interestingly, work has been proceeding along these lines using gp120's built in glycosylation sites and selective deglycosylation in the vicinity of the CD4 binding site (doi:10.1016/j.celrep.2017.04.013). Gp120 trimers that are completely glycosylated showed little immunogenicity. If however, glycans in the vicinity of the CD4 binding site were removed, the trimers became immunogenic. The nature of the antibody binding in the selective deglycosylation experiments was not sufficiently characterized to determine if any were single chain binders, although there were some indications of neutralization broadness.
</p>
<p>
I should also mention that the concept of epitope focusing by attaching an antigen fragment to a protein scaffold for display to the immune system has been done previously (doi:10.1038/nature12966).
</p>
