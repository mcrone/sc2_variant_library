# A library of SARS-CoV-2 Spike gene variant virus-like particles

This library of plasmids codes for MS2 virus-like particles packaged with various S gene variants (Amino acid 319-869). This [library](https://www.addgene.org/browse/article/28220218/) is made available under the [OpenMTA](https://www.addgene.org/agreement/8/) to enable the development and validation of low-cost diagnostic tools for rapidly identifying clinically relevant SARS-CoV-2 variants. Additional variants will be added to the library when necessary based on WHO/PHE surveillance data.

Upon successful QC of the final two variants the complete library will be available as a single kit from Addgene. Should this not be affordable for laboratories (especially in the Global South) then they can contact [me](mailto:m.crone@imperial.ac.uk) directly and I will ship the materials free of charge.

Plasmids that make up this library:
* [MS2_SC2_S_WT](https://www.addgene.org/175044/)
* [MS2_SC2_S_Alpha](https://www.addgene.org/175045/)
* [MS2_SC2_S_Beta](https://www.addgene.org/175046/)
* [MS2_SC2_S_Gamma](https://www.addgene.org/175047/)
* [MS2_SC2_S_Delta](https://www.addgene.org/175950/)
* [MS2_SC2_S_Zeta](https://www.addgene.org/175952/)
* [MS2_SC2_S_Eta](https://www.addgene.org/175954/)
* [MS2_SC2_S_Theta](https://www.addgene.org/175951/)
* [MS2_SC2_S_Kappa](https://www.addgene.org/175953/)
* [MS2_SC2_S_Lambda](https://www.addgene.org/175048/)
* [MS2_SC2_S_Mu](https://www.addgene.org/177366/) [currently undergoing QC at Addgene]
* [MS2_SC2_S_C.1.2](https://www.addgene.org/177367/) [currently undergoing QC at Addgene]

These plasmids have the following mutations that fall within amino acid 319 and 869 of the S protein:
Plasmid | Mutations | Sequence
------------ | ------------- | -------------
MS2_SC2_S_WT | - | [genbank](https://github.com/mcrone/variant_library/blob/master/genbank/ms2_sc2_s_wt.gb)
MS2_SC2_S_Alpha | N501Y, A570D, P681H, T716I | [genbank](https://github.com/mcrone/variant_library/blob/master/genbank/ms2_sc2_s_alpha.gb)
MS2_SC2_S_Beta | E484K, N501Y, A701V | [genbank](https://github.com/mcrone/variant_library/blob/master/genbank/ms2_sc2_s_beta.gb)
MS2_SC2_S_Gamma | K417T, E484K, N501Y | [genbank](https://github.com/mcrone/variant_library/blob/master/genbank/ms2_sc2_s_gamma.gb)
MS2_SC2_S_Delta | L452R, T478K, P681R | [genbank](https://github.com/mcrone/variant_library/blob/master/genbank/ms2_sc2_s_delta.gb)
MS2_SC2_S_Zeta | E484K | [genbank](https://github.com/mcrone/variant_library/blob/master/genbank/ms2_sc2_s_zeta.gb)
MS2_SC2_S_Eta | E484K, Q677H | [genbank](https://github.com/mcrone/variant_library/blob/master/genbank/ms2_sc2_s_eta.gb)
MS2_SC2_S_Theta | E484K, N501Y, P681H | [genbank](https://github.com/mcrone/variant_library/blob/master/genbank/ms2_sc2_s_theta.gb)
MS2_SC2_S_Kappa | L452R, E484Q, P681R | [genbank](https://github.com/mcrone/variant_library/blob/master/genbank/ms2_sc2_s_kappa.gb)
MS2_SC2_S_Lambda | L452Q, F490S, T859N | [genbank](https://github.com/mcrone/variant_library/blob/master/genbank/ms2_sc2_s_lambda.gb)
MS2_SC2_S_Mu | R346K, K417N, E484K, N501Y, D614G, P681H | [genbank](https://github.com/mcrone/variant_library/blob/master/genbank/ms2_sc2_s_mu.gb)
MS2_SC2_S_C.1.2 | Y449H, E484K, N501Y, D614G, H655Y, N679K, T716I, T859N | [genbank](https://github.com/mcrone/variant_library/blob/master/genbank/ms2_sc2_s_c1-2.gb)

## Suggested preparation of VLPs
For instructions on how to prepare the VLPs refer to our [paper](https://www.nature.com/articles/s41467-020-18130-3). I've noticed that NiCo21(DE3) cells work just as well as Rosetta 2(DE3)pLysS.


## Suggested diagnostic workflows
* Sanger Sequencing ([github](https://github.com/kblin/covid-spike-classification)) ([protocols.io](https://www.protocols.io/view/sanger-sequencing-of-a-part-of-the-sars-cov-2-spik-bsbdnai6))
* Additional workflows under development...


## Variant mutation matrix

![variant matrix](https://github.com/mcrone/variant_library/blob/master/variant_matrix/who_variants.svg)

## Funding

Jameel Fund



