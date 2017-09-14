# vHIV
An HIV vaccine (preliminary)
<p align="center">
  <img src="vHIV.png" width="500"/>
</p>
<p align="center">
  vHIV (salmon and red) shown bound to N6 heavy and light chains (blue and yellow)
</p>
<p align="center">
  (based on 5TE4.PDB -- DOI:10.1016/j.immuni.2016.10.027)
</p>
<p>
After seeing the zHIV neutralizer on my computer screen for the first time, one of the first questions that came to mind was whether or not it would be possible to make more molecules like that one. The neutralizer was derived from the N6 antibody, which aside from the fact that it can neutralize some 98% of all HIV clades it was tested against, has the interesting property that the light chain had evolved in such a way that it essentially stayed out of the way with the majority of the binding interaction being between the heavy chain and HIV's gp120 protein. This feature of N6 was used to make the small molecule neutralizer zHIV. So in essence the question is whether or not it is possible to trick the immune system into making antibodies that bind mostly with one chain or the other such that making small molecule theraputics from the antibodies would be facilitated. Another way to ask this question is to ask whether or not it is possible to create a vaccine that elicits antibodies with single chain binding properties.
</p>
<p>
I already had a crystal structure of N6 bound to gp120 on my computer. I had left gp120 alone and had gly21 software pick glycosylation sites on an N6 fragment for the purpose of the neutralizer design. So what if I left N6 alone and had gly21 pick glycosylation sites on gp120? In other words, to make a neutralizer, glycosylate one of the molecules, to make a vaccine, glycosylate the other. Wouldn't it be great if we tried the vaccine and the immune system automatically generated broadly neutralizing antibodies like N6? Wouldn't it be great if they bound gp120 with a single chain? So I went ahead and did the design. Like with zHIV one would need to select glycosylation sites from among those suggested by gly21 experimentally. Look for mutants that express efficiently and are glycosylated efficiently. One might like to pay attention to glycosylation sites that are already there. And one might like to use a more complete crystal structure of gp120. The one in 5TE4.PDB appears to be incomplete.
</p>
<p>
Interestingly, work has been proceeding along these lines using gp120's built in glycosylation sites and selective deglycosylation in the vicinity of the CD4 binding site (DOI:10.1016/j.celrep.2017.04.013). Needless to say, there's more to the picture than meets the eye. Gp120 trimers that are completely glycosylated show very little immunogenicity.
</p>
