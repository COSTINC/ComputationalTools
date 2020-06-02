# NRLcalc: *calculation of the Nucleosome Repeat Length*


External link: https://github.com/chrisclarkson/NRLcalc

Developed by Christopher Clarkson

## Description

Nucleosomes are positioned along the genome in a non-random and non-homogeneous way, which is critical for determining the DNA accessibility and maintaining fluid 3D genome organisation. A classical parameter characterising the nucleosome spacing is the nucleosome repeat length (NRL), defined as the average distance between the centres of adjacent nucleosomes. NRL can be defined genome-wide, locally for an individual genomic region or for a set of regions. Our analysis is based on the “phasogram” type of NRL calculation with NucTools. The idea of this method is to consider all mapped nucleosome reads within the genomic region of interest and calculate the distribution of the frequencies of the distances between nucleosome dyads (so-called phasogram). This distribution typically shows peaks corresponding to the prevailing distance between two nearest neighbour nucleosomes followed by the distances between next neighbours. The slope of the line resulting from the linear fit of the positions of the peaks then gives the NRL. When the analysis requires calculating just one or few NRLs the procedure described above can be easily done with a number of applications performing simple linear regression. The situation becomes more tricky if we have to perform a bulk calculation of many NRLs. The applet 'NRLcalc.R' solves this problem by providing a visual interface to load multiple phasograms and calculating NRLs for each of them in an interactive, user-friendly way. NLcalc is based on the R package shiny. It allows one to load multiple phasograms, adjust the smoothing of the signal, perform interactive peak calling for each plot, switch between different phasograms by using the 'Next' and 'Back' buttons, etc. The animated gif below demonstrates how the applet works.
## How to cite
Clarkson C.T., Deeks E.A., Samarista R., Mamayusupova H., Zhurkin V.B., Teif V.B. (2019) CTCF-dependent chromatin boundaries formed by asymmetric nucleosome arrays with decreased linker length. Nucleic Acids Res 47, 11181-11196. https://academic.oup.com/nar/article/47/21/11181/5609524
