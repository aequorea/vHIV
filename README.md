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
I wondered if it was possible to get the immune system to make more antibodies like N6 by making a vaccine. When I had the glycodesign software pick glycosylation sites on the N6 fragment, I did it with the fragment bound to gp120 to avoid glycosylating the binding pocket. Maybe a good way to make a vaccine would be to design glycans into gp120 instead. It's a different method of "epitope focusing." Maybe this is something we should be looking into, not just for HIV, but for other things as well. Find the conserved region on a virus, and use glycodesign to focus on it.
</p>
<p>
I call this design "preliminary" because there are many different HIV isolates and I don't know which version of gp120 would work the best. I don't know how different the CD4 binding sites in different isolates really are. I don't know how the immediate surroundings of the CD4 binding site varies between the different isolates. It might be nice to know something about the structures of the isolates that N6 doesn't work on.
</p>
<p>
So when I look at Fig. 1, Table C, in the above mentioned reference I see 4 "fails" which out of 181 tested isolates makes sense since they claim 98% effectiveness for the antibody. The fails are: T278-50 from clade AG, BL01.DG from clade B, 6471.V1.C16 from clade C, and TV1.29 from clade C. There were also a couple of isolates where the binding was weak: CAP210.E8 from clade C, and 57128.vrc15 from clade D. It would be nice if there were structures of the gp120 molecules from these 6 isolates. Wouldn't it be weird if the only reason N6 had trouble with these isolates is that the light chain was getting in the way?
</p>
<p>
Suppose this is the case. Pick the version of gp120 with the biggest hump causing the biggest obstruction preventing the N6 heavy chain from binding. Try epitope focusing with that one. Maybe we get antibodies that can bind the most obstructed one as well as the others. In other words we would be making a vaccine that might encourage the production of antibodies with a minimalist light chain.
</p>
