# RAD-seq
# Restriction‐site Associated DNA sequencing : scripts to find genetic variants in non-model fish species

By far, most of genomes of living creatures are scarcely known, most often only by their barcoding markers. When one needs to use some genetic variants in their population-s for characterizing a probable genetic structure at the population scale, we usually use Restriction‐site Associated DNA sequencing (RAD-seq) to find them out.

Here, I propose to find genetic variants in two fish species, Pollack (Pollachius pollachius) and Red Mullet (Mullus surmuletus, Atlantic area only). I propose this cookbook for analyzing RAD-seq raw reads, produced by Illumina, with the aim to characterize SNPs and INDELs. 

For studying population genetic structure in non-model species, individual variants should be compared between specimens from different localities. However, it can be very costy to perform individual RAD-sequencing for many specimens. That's the reason why we can first discover the variants and then genotype them 

First, we need to set up a strategy for fish sampling.

https://github.com/GATB/DiscoSnp

