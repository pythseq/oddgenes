# oddgenes

A list of weird gene annotations or things that break bioinformatics assumptions


## Gene structures

### 1bp length exon

Evidence given for a 1bp length exon in Arabadopsis and different splicing models are discussed

http://www.nature.com/articles/srep18087

### 0bp length exon

The phenomenon of recursive splicing can remove sequences progressively inside an intron, so there can exist "0bp exons" that are just the splice-site sequences pasted together.

"To identify potential zero nucleotide exon-type ratchet points, we parsed the RNA-Seq alignments to identify novel splice junctions where the reads mapped to an annotated 5' splice site and an unannotated 3' splice site, and the genomic sequence at the 3' splice site junction was AG/GT"

https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4529404/


### Twintron

A twintron is essentially an intron-within-an-intron, which could be formed by a mobile element (TE) insertion. The original idea is that the internal intron has to be spliced first before the outer one is, but several classes have been discovered. See https://en.wikipedia.org/wiki/Twintron

### Very large number of isoforms in Dscam

"Dscam has 24 exons; exon 4 has 12 variants, exon 6 has 48 variants, exon 9 has 33 variants, and exon 17 has two variants. The combination of exons 4, 6, and 9 leads to 19,008 possible isoforms with different extracellular domains (due to differences in Ig2, Ig3 and Ig4). With two different transmembrane domains from exon 17, the total possible protein products could reach 38,016 isoforms"

Ref https://en.wikipedia.org/wiki/DSCAM https://www.wikigenes.org/e/gene/e/35652.html

### Translational frameshift

"The main distinction between frameshifts resulting from mutation and those resulting from ribosomal frameshifting is that the latter are controlled by various mechanisms found in codons...Certain codons take longer to translate, because there are not equal amounts of tRNA of that particular codon in the cytosol..." which leads to ribosomal slippage into an alternative reading frame

Ref https://en.wikipedia.org/wiki/Translational_frameshift

### A Stop codon that is not a stop codon

In some cases a stop codon is not interpreted as such. When it is interpreted, it is sometimes called "Stop codon readthrough" and can encode for an amino acid. The amino acid Selenocysteine is coded for by a stop codon (https://en.wikipedia.org/wiki/Selenocysteine) and Pyrrolysine also is coded for by a stop codon (https://en.wikipedia.org/wiki/Pyrrolysine). Both of these lie outside the conventional 20 amino acid code


There are several other stop codon modifications described here http://www.nature.com/nrg/journal/v16/n9/box/nrg3963_BX2.html?foxtrotcallback=true

## Wormbase

### Adding leader sequence to mRNA

"About 70% of C. elegans mRNAs are trans-spliced to one of two 22 nucleotide spliced leaders. SL1 is used to trim off the 5' ends of pre-mRNAs and replace them with the SL1 sequence. This processing event is very closely related to cis-splicing, or intron removal."

The region that is spliced out is called an outron

http://www.wormbook.org/chapters/www_transsplicingoperons/transsplicingoperons.html

### Polycistronic transcripts/operons

"A characteristic feature of the worm genome is the existence of genes organized into operons. These polycistronic gene clusters contain two or more closely spaced genes, which are oriented in a head to tail direction. They are transcribed as a single polycistronic mRNA and separated into individual mRNAs by the process of trans-splicing"

http://www.wormbook.org/chapters/www_overviewgenestructure.2/genestructure.html

## Evolution

### Possible adaptive bacteria->eukaryote HGT

A possible horizontal gene transfer from bacteria to eukaryotes is found in an insect that feeds on coffee beans. Changes that the gene had to undergo are covered (added poly-A tail, shine-dalgarno sequence deleted)

https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3306691/

### Transgenerational epigenetic inheritence

This phenomena of epigenetic modifications being passed down across generations garners a lot of media attention and scientific attention. The idea of it being influenced by what "one does in life" such as experiencing famine is also very interesting.

https://en.wikipedia.org/wiki/Transgenerational_epigenetic_inheritance


## Codon usage

### Alternative start codons

"The most common start codons for known Escherichia coli genes are AUG (83% of genes), GUG (14%) and UUG (3%)"

"Here, we systematically quantified translation initiation of green fluorescent protein (GFP) from all 64 codons and nanoluciferase from 12 codons on plasmids designed to interrogate a range of translation initiation conditions."

https://www.sciencedaily.com/releases/2017/02/170221080506.htm

## Molecular

### Complex DNA structures

DNA can form complex structures such as quadruplex or four stranded DNA instead of a standard double stranded (dsDNA) helix. This has had implications that it may have important biological function.

See https://news.cnrs.fr/articles/unlocking-the-secrets-of-four-strand-dna

## RNA world

### RNA editing

RNA editing is a post-transcriptional modification to the mRNA to change the bases. A-to-I editing is a common one in mammals which would make the RNA appear to have a G where there is an A is in the genomic DNA.

Other editing occurs also https://en.wikipedia.org/wiki/RNA_editing

### Maternal RNAs being passed down

Maternal RNAs being active against the zygote (e.g. https://en.wikipedia.org/wiki/Maternal_to_zygotic_transition) and lead to complex transgenerational effects

### Lowly expressed RNA has large effects

A lncRNA VELUCT almost flies under the radar in a lung cancer screen due to being very lowly expressed such that it is "below the detection limit in total RNA from NCI-H460 cells by RT-qPCR as well as RNA-Seq", however this study confirms it as a factor in experiments

https://www.ncbi.nlm.nih.gov/pubmed/28160600?dopt=Abstract

## Transposons

### Cross-species BovB transposon transfers

Or "How a quarter of the cow genome came from snakes" http://phenomena.nationalgeographic.com/2013/01/01/how-a-quarter-of-the-cow-genome-came-from-snakes/

Source http://www.pnas.org/content/110/3/1012.full

### LINE1 important for embryonic development

Transposon activity can mutate DNA as it will insert itself into the genome. The genome has functions for keeping transposons inactive. However, evidence shows that the LINE1 is important for embryonic development.

https://www.ucsf.edu/news/2018/06/410781/not-junk-jumping-gene-critical-early-embryo


## Immunity

### VDJ Recombination

VDJ recombination is a process of somatic recombination (using "recombination signal sequences") that is done in immune cells. Different gene segments of class "V", class "D", and class "J" exons (sometimes to exons are referred to as "genes" themselves) are somatically rearranged into coherent genes that are then transcribed and immune diversity.

https://en.wikipedia.org/wiki/V(D)J_recombination


## Regulation

### Intron mediated enhancement (IME)

It has been shown that some intron sequences can enhance expression similar to how promoter sequences work https://en.wikipedia.org/wiki/Intron-mediated_enhancement

The first intron of the UBQ10 gene in Arabidopsis exhibits IME, and "the sequences responsible for increasing mRNA accumulation are redundant and dispersed throughout the UBQ10 intron" http://www.plantcell.org/content/early/2017/04/03/tpc.17.00020.full.pdf+html


## Non-ACGT letters in fasta files

The latest human genome, for example, downloaded from NCBI, contains a number of Non-ACGT letters in the form of IUPAC codes https://www.bioinformatics.org/sms/iupac.html These represent ambiguous bases.


Here is the incidence of non-ACGT IUPAC letters in the entire human genome GRCh38.p10 NC_000001-24

```
b: 2
k: 8
m: 8
r: 26
s: 5
w: 14
y: 35
```

Did you expect that in your bioinformatics software? Note that the mouse genome (GRCm38.p5) as far as I could tell does not contain any non-ACGT IUPAC letters


## Interesting gene names

* Tinman - https://en.wikipedia.org/wiki/Tinman_gene
* Sonic hedgehog (SHH) - https://en.wikipedia.org/wiki/Sonic_hedgehog
* Heart of glass (heg) - https://www.ncbi.nlm.nih.gov/pubmed/14680629
* Dracula (drc) - https://www.ncbi.nlm.nih.gov/pubmed/10985389
* Sleeping Beauty transposon - https://en.wikipedia.org/wiki/Sleeping_Beauty_transposon_system
* Skywalker protein - http://www.ebi.ac.uk/pdbe/entry/search/index?pubmed_id:27669036
* Time for coffee - http://www.plantcell.org/content/15/11/2719.abstract
* Wtf4 - https://www.sciencedaily.com/releases/2017/06/170620093209.htm
* Mothers against decapentaplegic - https://en.wikipedia.org/wiki/Mothers_against_decapentaplegic
* Saxophone (sax) - http://www.sdbonline.org/sites/fly/gene/saxophon.htm
* Beethovan (btv) - http://www.uniprot.org/uniprot/Q0E8P6
* Superman+kryptonite - https://en.wikipedia.org/wiki/Superman_(gene)
* Wishful thinking (wit) - https://www.wikigenes.org/e/gene/e/44096.html

Great illustrations of interesting biology, including information about gene names https://twitter.com/vividbiology

Many of the stories behind fly gene nomenclature is available at https://web.archive.org/web/20110716201703/http://www.flynome.com/cgi-bin/search?source=browse including the famous ForRentApartments dot com gene (just kidding but lol https://web.archive.org/web/20110716202150/http://www.flynome.com/cgi-bin/search?storyID=180)
