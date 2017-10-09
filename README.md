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
When I had the glycodesign software pick glycosylation sites on the N6 fragment, I did it with the fragment bound to gp120 to avoid glycosylating the binding pocket. Maybe a good way to make a vaccine would be to design glycans into gp120 instead. It's a different method of "epitope focusing." I call this design "preliminary" because there are many different HIV isolates and I don't know which version of gp120 would work the best. I don't know how different the CD4 binding sites in different isolates really are. I don't know how the immediate surroundings of the CD4 binding site varies between the different isolates.
</p>
<p>
When I look at Fig. 1, Table C, in the above mentioned reference I see 4 "fails" out of 181 tested isolates, these are the isolates that N6 fails to neutralize. The fails are: T278-50 from clade AG, BL01.DG from clade B, 6471.V1.C16 from clade C, and TV1.29 from clade C. There were also a couple of isolates where the binding was weak: CAP210.E8 from clade C, and 57128.vrc15 from clade D. It would be nice if there were structures of the gp120 molecules from these 6 isolates. Wouldn't it be interesting if the only reason N6 had trouble with these isolates is that the light chain was still getting in the way?
</p>
<p>
There is more to making a vaccine that would encourage antibodies that bind CD4 than just making a vaccine molecule, injecting it, and then getting nice antibodies before that one dose of vaccine gets cleared out of the system. Broadly neutralizing antibodies targeting the CD4 binding site take a while to develop. There is significant "affinity maturation" of the binding site going on and this can take time. In an HIV patient it can take years for broadly neutralizing antibodies to form. The question is, can we speed up this process? Maybe. But one might need some "booster shots" to give the process time to happen even in the best case. But given that we will likely need some booster shots to keep the target in circulation long enough for the maturation to occur, should all of the booster shots have the same vaccine as the initial dose or should there be a progression of structures? Maybe we should start with something easy to bind and make it progressively more difficult for binding to occur. Lead the evolution of the antibody binding site. We can try different gp120 structures and order them from easy to difficult. A difficult structure might have the binding pocket deeper than the others or might have a "shoulder" that might serve to engage the light chain so as to prevent a close approach. A difficult structure might have more densely packed glycans in the neighborhood of the binding pocket. So we have two parameters we can vary if we were interested in presenting epitope focused vaccines to the immune system with the intent of encouraging rapid evolution of broadly neutralizing antibodies.
</p>
