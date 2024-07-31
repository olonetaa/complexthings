---
layout: post
title:  "Notes: Noncoding RNA: evolutionary hitchikers? actually useful?"
date:   2024-07-28 18:50:32 +0800
categories: biology notes
permalink: /posts/questions/noncodingRNA
---

This is my notes of [this](https://www.scientificamerican.com/article/revolutionary-genetics-research-shows-rna-may-rule-our-genome/#:~:text=Dozens%20of%20other%20research%20groups,to%20conduct%20some%20biochemical%20task.) article from Scientific American, plus links from supplemental resources and my own understanding.

****

Only 1%-2% of the human DNA sequence are genes that encode proteins, in other words, "genes" classically defined. 

**75% of DNA is transcribed into RNAs.** Noncoding RNA units that have a specific purpose are called "noncoding genes", and one study estimate their numbers to be almost twice as many as protein-encoding genes. 

A reason why they have long been ignored is that ncRNA is rarer in bacteria, which is often the subject for gene studies. **Model species are sometimes unreliable!**

In Richard Dawkin's book 'The Selfish Gene', he remarked that "junk" DNA, or "selfish DNA", may increase in frequency in the gene pool precisely because it has no effect on the body (p. 57). **This makes them advantageous compared to harmful genes.**

![]({{'/assets/images/junkDNAdiagram.png'|relative_url}})

This is also part of how some retroviruses work. [Endogenous retroviruses](https://en.wikipedia.org/wiki/Endogenous_retrovirus) are benign proviral sequences in genomes that are vertically inherited over generations. They came from retroviruses, a type of virus that insert their own genomes into the genome of their host's, but do not cause any disease. They are textbook examples of "selfish" DNA, and they have been lurking in our genomes for millions of years.

However, the point here is that at least some of our "junk" DNA do have functions, and not all of them are hitching rides!

## Noncoding RNA involved in gene regulation:
### Long ncRNA (lncRNA)
- X-inactivation (XIST gene is transcribed and the lncRNA wraps around the inactivated X chromosome)
- Acting as RNA scaffolds to RNA-binding protein in order to form functional assemblies
- Could maybe affect chromatin arrangement and affect gene regulation - such RNA could have repeating sequences.
	- [This](https://www.science.org/doi/abs/10.1126/science.adf3481?af=R) paper by Dr. Sara Zocher showed that there are long-lived lncRNA in mice brain cells that "are required for the maintenance of heterochromatin". Heterochromatin is the condensed and less translated part of the nucleus, so by affecting chromatin structure, ncRNA could affect gene regulation.
### MicroRNA
microRNA: upstream regulators (miRNA)
- E.g. lin-4 and let-7 in C. elegans → controls development upstream
- Let-7 has nearly identical genes in vertebrates and other classes of animals, therefore it must have originated before the divergence of these taxa (according to SciAm). **But couldn't they have emerged separately, since miRNAs are so short?**
- Main mechanism of miRNA gene regulation:
	- pre-miRNA is transcribed (several miRNA stuck together)
	- Dicer protein chops it up into individual miRNAs
	- miRNAs bond with Argonaute proteins, forms RNA-induced silencing complex (RISC)
	- miRNAs guide RISC to mRNA (one miRNA typically has a sequence compatible with lots of mRNAs, we don’t know how they manage to be selective, but several miRNAs might work together - might be advantageous since it allows flexibility in gene regulation, so individuals could better adapt to the environment)
	- Stops its transcription or degrades it
- What do miRNAs control?
	- Cell fate, cell cycle, apoptosis (important stuff!)

### Other classes of RNA

- PIWI-interacting RNAs (piRNAs): silence transposons in gametes 
- small nucleolar RNAs: work in nucleoli to modify ribosome RNA
- ...
