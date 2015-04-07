# GREAT_functional_enrichment_analysis
Rashedul  
Monday, April 06, 2015  

The genomic coordinates of 34 top selected cgi of our study were converted to bed file using a text editor. 

Then the bed file was fed on [GREAT](http://bejerano.stanford.edu/great/public/html/). The Human: GRCh37 genome assembly and whole genome background were used. GREAT gave 54 genes at FDR 0.05 that are associated with genomic regions. On the other hand, Bioconductor package "IlluminaHumanMethylation450kGO" predicted 20 top enriched genes. Among the 20 genes 16 genes are common in both the enrichment analysis methods. The the gene that are not common are: ANKRD30BL, TTC7B, ZNRD1-AS1, FAM71E2. **So the most important 16 genes are: **

```
RBM47
NEDD1
ZNF471
TMEM247
HIST3H3
CNTN2
WNT7A
TBC1D2
ATP11A
DIAPH3
ZAP70
CLCC1
ZNF540
TRPM4
ZNRD1
KIF19
OBSCN
```

#### GREAT output

```
ALG10       (+320255)
ATP11A	     (+84642)
ATP6V1E2	     (+39342)
B3GNTL1	     (-14555)
BTBD17	     (+9962)
CALM1	     (+224309)
CHRNA9	     (+103017)
CLCC1	     (+163)
CNTN2	     (+26644)
COX6B2	     (-4418)
CPT1B	     (+459)
CWH43	     (+537747)
DIAPH3	     (+148)
FAM21C	     (-27104)
FBLN2	     (+305517)
FGFRL1	     (+46021)
GPR39	     (-159388)
GRID1	     (-34277)
HIST3H3	     (+184)
IFLTD1	     (+167979)
IFT140	     (+63056)
KANSL1	     (-50952)
KIF19	     (+25772)
KRAS	     (-134501)
LPA	     (-12867)
LRRC37A	     (-51379)
MCF2L	     (-194250)
METRNL	     (-13326)
MZT2A	     (-764764)
NEDD1	     (-199)
OBSCN	     (+7549)
PLG	     (-23000)
RBM47	     (+76412)
RNF212	     (+57526)
RPS6KA5	     (+439316)
SLC6A16	     (+159068)
SPATA31A7	     (-946410)
TBC1D2	     (-67)
TFAP2B	     (+31870)
TMEM131	     (+261233)
TMEM204	     (+15481)
TMEM247	     (+1029)
TMEM81	     (+14676)
TRIM11	     (+191161)
TRPM4	     (+8416)
WAPAL	     (+121060)
WNT7A	     (+25470)
ZAP70	     (+21098)
ZFAND4	     (-27767)
ZNF471	     (-87)
ZNF540	     (-2330)
ZNF728	     (-68111)
ZNF730	     (-45688)
ZNRD1	     (+35)
```
####Bioconductor package output: 

```
RBM47
NEDD1
ANKRD30BL
ZNF471
TMEM247
HIST3H3
CNTN2
WNT7A
TBC1D2
ATP11A
DIAPH3
#TTC7B
ZAP70
CLCC1
ZNF540
TRPM4
ZNRD1
KIF19
ZNRD1-AS1
OBSCN
FAM71E2
```