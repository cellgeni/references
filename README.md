- [Fruit Fly](#fruit-fly)
  * [BDGP6](#bdgp6)
- [Human](#human)
  * [2020A](#2020a)
  * [2020A Full](#2020a-full)
  * [2020A plus Plasmodium_Falciparum.EPr1.37](#2020a-plus-plasmodium-falciparumepr137)
  * [2020A plus GCA_000149715.2_TGGT1_genomic](#2020a-plus-gca-0001497152-tggt1-genomic)
  * [Gencode v19 Full](#gencode-v19-full)
  * [Gencode v37 Full](#gencode-v37-full)
  * [GRCh38-1.2.0](#grch38-120)
  * [GRCh38-3.0.0](#grch38-300)
  * [GRCh38-3.0.0 plus 3D7](#grch38-300-plus-3d7)
  * [hg19-1.2.0](#hg19-120)
  * [hg19-3.0.0](#hg19-300)
  * [T2T](#t2t)
- [Human with Covid](#human-with-covid)
  * [GRCh38 Plus SARSCoV2](#grch38-plus-sarscov2)
- [Human & Mouse](#human---mouse)
  * [GRCh38-3.1.0](#grch38-310)
- [Malaria](#malaria)
  * [3D7](#3d7)
- [Mouse](#mouse)
  * [2020A](#2020a-1)
  * [2020A Full](#2020a-full-1)
  * [1.2.0](#120)
  * [2.1.0](#210)
  * [3.0.0](#300)
- [Toxoplasma Gondii](#toxoplasma-gondii)
  * [gt1_gca_00149715](#gt1-gca-00149715)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>


# Fruit Fly
## BDGP6
<br>**STAR version** 2.7.9a
<br>**Path:**
	
```
/nfs/cellgeni/STAR/fruit_fly/BDGP6/index
```
<br>**Gene Count:** 23882
<br>**Genome sequence total length:** 137567484
<br>**Chromosome Names:** 2L, 2R, 3L, 3R, 4, mitochondrion_genome, X, Y
<br>**Chromosome Lenght:**
| Chromosome | Length |
|------|-----------|
| 2L | 23513712 |
| 2R | 25286936 |
| 3L | 28110227 |
| 3R | 32079331 |
| 4 | 1348131 |
| mitochondrion_genome | 19524 |
| X | 23542271 |
| Y | 3667352 |

<br>**Build Command:**

```
STAR   --runMode genomeGenerate      --runThreadN 4   --genomeDir STAR   --genomeFastaFiles /lustre/scratch117/cellgen/cellgeni/TIC-starsolo/tic-1484/fasta/Drosophila_melanogaster.BDGP6.32.dna.primary_assembly.fa --sjdbGTFfile /lustre/scratch117/cellgen/cellgeni/TIC-starsolo/tic-1484/gene_annotation/Drosophila_melanogaster.BDGP6.32.105.chr.gtf   --sjdbOverhang 100
```

# Human
## 2020A

**STAR version** 2.7.7a
<br>**Path:**

```
/nfs/cellgeni/STAR/human/2020A/index
```
<br>**Gene Count:** 36601
<br>**Genome sequence total length:** 3099750718
<br>**Chromosome Names:** chr1, chr10, .., chr2, chr20, .., KI270728.1, KI270727.1, ...
<br>**Chromosome Lenght:**
| Chromosome | Length |
|------------|-----------|
| chr1       | 248956422 |
| chr10      | 133797422 |
| chr11      | 135086622 |
| chr12      | 133275309 |
| chr13      | 114364328 |
| chr14      | 107043718 |
| chr15      | 101991189 |
| chr16      | 90338345  |
| chr17      | 83257441  |
| chr18      | 80373285  |

<br>Please see <em>/nfs/cellgeni/STAR/human/2020A/index/Log.out</em> for more information/Chromosomes
<br>**Build Command:**

```
STAR   --runMode genomeGenerate   --runThreadN 4   --genomeDir STARsolo   --genomeFastaFiles GRCh38_v32_modified.fa      --sjdbGTFfile GRCh38_v32_filtered.gtf
```

## 2020A Full
<br>**STAR version:** 2.7.7a
<br>**Path:**

```
/nfs/cellgeni/STAR/human/2020A-full/index
```
<br>**Gene Count:** 60668
<br>**Genome sequence total length:** 3099750718
<br>**Chromosome Names:** chr1, chr10, .. , chr2, chr20, .., KI270728.1, KI270727.1, KI270442.1, ...
<br>**Chromosome Lenght:**
| Chromosome | Length |
|------------|-----------|
| chr1       | 248956422 |
| chr10      | 133797422 |
| chr11      | 135086622 |
| chr12      | 133275309 |
| chr13      | 114364328 |
| chr14      | 107043718 |
| chr15      | 101991189 |
| chr16      | 90338345  |
| chr17      | 83257441  |
| chr18      | 80373285  |

<br>Please see <em>/nfs/cellgeni/STAR/human/2020A-full/index/Log.out</em> for more information/Chromosomes
<br>**Build Command:**

```
STAR   --runMode genomeGenerate   --runThreadN 4   --genomeDir STAR   --genomeFastaFiles GRCh38_v32_modified.fa      --sjdbGTFfile GRCh38_v32_modified.gtf
```
## 2020A plus Plasmodium_Falciparum.EPr1.37
<br>**STAR version:** 2.7.9a_2021-06-25 
<br>**Path:**

```
/nfs/cellgeni/STAR/human/2020A_plus_Pf_3D7/index
```
<br>**Gene Count:** 42294
<br>**Genome sequence total length:** 3123083557
<br>**Chromosome Names:** chr1, ch10, .., chr2, chr20, .., KI270728.1, KI270727.1, ...
<br>**Chromosome Lenght:**
| Chromosome | Length |
|------------|-----------|
| chr1       | 248956422 |
| chr10      | 133797422 |
| chr11      | 135086622 |
| chr12      | 133275309 |
| chr13      | 114364328 |
| chr14      | 107043718 |
| chr15      | 101991189 |
| chr16      | 90338345  |
| chr17      | 83257441  |
| chr18      | 80373285  |

<br>Please see <em>/nfs/cellgeni/STAR/human/2020A_plus_Pf_3D7/index/Log.out</em> for more information/Chromosomes
<br>**Build Command:**

```
STAR   --runMode genomeGenerate      --runThreadN 16   --genomeDir index   --genomeFastaFiles combo.fa      --sjdbGTFfile combo.gtf
```
## 2020A plus GCA_000149715.2_TGGT1_genomic
<br>**STAR version:** 2.7.9a_2021-06-25
<br>**Path:**

```
/nfs/cellgeni/STAR/human/2020A_plus_Tg_GT1/index
```
<br>**Gene Count:** 45238
<br>**Genome sequence total length:** 3164812953
<br>**Chromosome Names:** chr1, chr10, chr11, chr12, ...
<br>**Chromosome Lenght:**
| Chromosome | Length |
|------------|-----------|
| chr1       | 248956422 |
| chr10      | 133797422 |
| chr11      | 135086622 |
| chr12      | 133275309 |
| chr13      | 114364328 |
| chr14      | 107043718 |
| chr15      | 101991189 |
| chr16      | 90338345  |
| chr17      | 83257441  |
| chr18      | 80373285  |

<br>Please see <em>/nfs/cellgeni/STAR/human/2020A_plus_Tg_GT1/index/Log.out</em> for more information/Chromosomes
<br>**Build Command:**

```
STAR   --runMode genomeGenerate      --runThreadN 16   --genomeDir index   --genomeFastaFiles combo.fa      --sjdbGTFfile combo.gtf
```
## Gencode v19 Full
<br>**STAR version:** 2.7.10a_alpha_220818
<br>**Path:**

```
/nfs/cellgeni/STAR/human/Gencode_v19_full/index
```
<br>**Gene Count:** 63568
<br>**Genome sequence total length:** MISSING INFO HERE
<br>**Chromosome Names:** chr1, chr2, chr3, ...
<br>**Chromosome Lenght:** 3234834689
| Chromosome | Length |
|------------|-----------|
| chr1       | 249250621 |
| chr2       | 243199373 |
| chr3       | 198022430 |
| chr4       | 191154276 |
| chr5       | 180915260 |
| chr6       | 171115067 |
| chr7       | 159138663 |
| chr8       | 146364022 |
| chr9       | 141213431 |
| chr10      | 135534747 |

<br>Please see <em>/nfs/cellgeni/STAR/human/Gencode_v19_full/index/Log.out</em> for more information/Chromosomes
<br>**Build Command:**

```
/opt/STAR-2.7.10a_alpha_220818/source/STAR   --runMode genomeGenerate      --runThreadN 16   --genomeDir index   --genomeFastaFiles GRCh37.p13.genome.fa      --sjdbGTFfile gencode.v19.chr_patch_hapl_scaff.annotation.gtf
```
## Gencode v37 Full
<br>**STAR version:** 2.7.10a_alpha_220818
<br>**Path:**

```
/nfs/cellgeni/STAR/human/Gencode_v37_full/index
```
<br>**Gene Count:** 60710
<br>**Genome sequence total length:** 3099750718
<br>**Chromosome Names:** chr,1, chr2, chr3, chr4, ...
<br>**Chromosome Lenght:**
| Chromosome | Length |
|-------|-----------|
| chr1  | 248956422 |
| chr2  | 242193529 |
| chr3  | 198295559 |
| chr4  | 190214555 |
| chr5  | 181538259 |
| chr6  | 170805979 |
| chr7  | 159345973 |
| chr8  | 145138636 |
| chr9  | 138394717 |
| chr10 | 133797422 |

<br>Please see <em>/nfs/cellgeni/STAR/human/Gencode_v37_full/index/Log.out</em> for more information/Chromosomes
<br>**Build Command:**

```
/opt/STAR-2.7.10a_alpha_220818/source/STAR   --runMode genomeGenerate      --runThreadN 16   --genomeDir index   --genomeFastaFiles Gencode_v37_primary.fa      --sjdbGTFfile Gencode_v37_primary.gtf  
```
## GRCh38-1.2.0
<br>**STAR version:** 2.7.7a
<br>**Path:**

```
/nfs/cellgeni/STAR/human/GRCh38-1.2.0/index
```
<br>**Gene Count:** 33694
<br>**Genome sequence total length:** 3099750718
<br>**Chromosome Names:** 1, 10, 11, 12, 13
<br>**Chromosome Lenght:**
| Chromosome | Length |
|------------|-----------|
| 1  | 248956422 |
| 10 | 133797422 |
| 11 | 135086622 |
| 12 | 133275309 |
| 13 | 114364328 |
| 14 | 107043718 |
| 15 | 101991189 |
| 16 | 90338345  |
| 17 | 83257441  |
| 18 | 80373285  |

<br>Please see <em>/nfs/cellgeni/STAR/human/GRCh38-1.2.0/index/Log.out</em> for more information/Chromosomes
<br>**Build Command:**

```
STAR   --runMode genomeGenerate   --runThreadN 4   --genomeDir STAR   --genomeFastaFiles Homo_sapiens.GRCh38.dna.primary_assembly.fa      --sjdbGTFfile Homo_sapiens.GRCh38.84.filtered.gtf   --sjdbOverhang 90
```
## GRCh38-3.0.0
<br>**STAR version:** 2.7.7a
<br>**Path:**

```
/nfs/cellgeni/STAR/human/GRCh38-3.0.0/index
```
<br>**Gene Count:** 33538
<br>**Genome sequence total length:** 3099750718
<br>**Chromosome Names:** 1, 10, 11, 12, 13, ...
<br>**Chromosome Lenght:**
| Chromosome | Length |
|------------|-----------|
| 1  | 248956422 |
| 10 | 133797422 |
| 11 | 135086622 |
| 12 | 133275309 |
| 13 | 114364328 |
| 14 | 107043718 |
| 15 | 101991189 |
| 16 | 90338345  |
| 17 | 83257441  |
| 18 | 80373285  |

<br>Please see <em>/nfs/cellgeni/STAR/human/GRCh38-3.0.0/index/Log.out</em> for more information/Chromosomes
<br>**Build Command:**

```
STAR   --runMode genomeGenerate   --runThreadN 4   --genomeDir STAR   --genomeFastaFiles Homo_sapiens.GRCh38.dna.primary_assembly.fa      --sjdbGTFfile Homo_sapiens.GRCh38.93.filtered.gtf   --sjdbOverhang 100
```
## GRCh38-3.0.0 plus 3D7
<br>**STAR version:** 2.7.9a
<br>**Path:**

```
/nfs/cellgeni/STAR/human/GRCh38-3.0.0_plus_3D7/index
```
 **Gene Count:** 39231
<br>**Genome sequence total length:** 3123083557
<br>**Chromosome Names:** 1, 10, 11, 12
<br>**Chromosome Lenght:**
| Chromosome | Length |
|------------|-----------|
| 1  | 248956422 |
| 10 | 133797422 |
| 11 | 135086622 |
| 12 | 133275309 |
| 13 | 114364328 |
| 14 | 107043718 |
| 15 | 101991189 |
| 16 | 90338345  |
| 17 | 83257441  |
| 18 | 80373285  |

<br>Please see <em>/nfs/cellgeni/STAR/human/GRCh38-3.0.0_plus_3D7/index/Log.out</em> for more information/Chromosomes
<br>**Build Command:**

```
STAR   --runMode genomeGenerate      --runThreadN 4   --genomeDir STAR   --genomeFastaFiles combo.fa      --sjdbGTFfile combo.gtf
```
## hg19-1.2.0
**No STAR index built yet**
<br> **Path:**

```
/nfs/cellgeni/STAR/human/hg19-1.2.0
```
## hg19-3.0.0
**No STAR index built yet**
<br> **Path:**

```
/nfs/cellgeni/STAR/human/hg19-3.0.0
```
## T2T
<br> **STAR version:** 2.7.10a_alpha_220818
<br> **Path:**

```
/nfs/cellgeni/STAR/human/T2T/index
```
 **Gene Count:** 37274
<br> **Genome sequence total length:** 3117292070
<br> **Chromosome Names:** chr1, chr2, chr3, ...
<br> **Chromosome Lenght:**
| Chromosome | Length |
|------------|-----------|
| chr1 | 248387328 |
| chr2 | 242696752 |
| chr3 | 201105948 |
| chr4 | 193574945 |
| chr5 | 182045439 |
| chr6 | 172126628 |
| chr7 | 160567428 |
| chrX | 154259566 |
| chr9 | 150617247 |
| chr8 | 146259331 |

<br>Please see <em>/nfs/cellgeni/STAR/human/T2T/index/Log.out</em> for more information/Chromosomes
<br> **Build Command:**

```
/opt/STAR-2.7.10a_alpha_220818/source/STAR   --runMode genomeGenerate      --runThreadN 4   --genomeDir STARsolo   --genomeFastaFiles T2T_with_mito.fa      --sjdbGTFfile T2T_v2_filtered.gtf 
```
# Human with Covid
## GRCh38 Plus SARSCoV2
<br> **STAR version:** 2.7.9a
<br> **Path:**

```
/nfs/cellgeni/STAR/human_covid/GRCh38_plus_SARSCoV2/index
```
 **Gene Count:** 33552
<br> **Genome sequence total length:** 3099780621
<br> **Chromosome Names:** 1, 10, 11, 12, ...
<br> **Chromosome Lenght:**
| Chromosome | Length |
|------------|-----------|
| 1  | 248956422 |
| 10 | 133797422 |
| 11 | 135086622 |
| 12 | 133275309 |
| 13 | 114364328 |
| 14 | 107043718 |
| 15 | 101991189 |
| 16 | 90338345  |
| 17 | 83257441  |
| 18 | 80373285  |

<br>Please see <em>/nfs/cellgeni/STAR/human_covid/GRCh38_plus_SARSCoV2/index/Log.out</em> for more information/Chromosomes
<br> **Build Command:**

```
STAR   --runMode genomeGenerate      --runThreadN 4   --genomeDir STAR   --genomeFastaFiles human_covid_genome.fa      --sjdbGTFfile human_covid_genes.gtf   --sjdbOverhang 100
```
# Human & Mouse
## GRCh38-3.1.0
<br>**STAR version:** 2.7.9a 
<br>**Path:**

```
/nfs/cellgeni/STAR/human_mouse/GRCh38-3.1.0/index
```
 **Gene Count:** 61078
<br>**Genome sequence total length:** 5830622492
<br>**Chromosome Names:** 1, 10, 11, 12, ...
<br>**Chromosome Lenght:**
| Chromosome | Length |
|------------|-----------|
| 1  | 248956422 |
| 10 | 133797422 |
| 11 | 135086622 |
| 12 | 133275309 |
| 13 | 114364328 |
| 14 | 107043718 |
| 15 | 101991189 |
| 16 | 90338345  |
| 17 | 83257441  |
| 18 | 80373285  |

<br>Please see <em>/nfs/cellgeni/STAR/human_mouse/GRCh38-3.1.0/index/Log.out</em> for more information/Chromosomes
<br>**Build Command:**

```
STAR   --runMode genomeGenerate      --runThreadN 4   --genomeDir STAR   --genomeFastaFiles combined.fa      --sjdbGTFfile combined_filtered.gtf   --sjdbOverhang 100
```
# Malaria
## 3D7
<br>**STAR version:** 2.7.9a_2021-06-25
<br>**Path:**

```
/nfs/cellgeni/STAR/malaria/3D7/index
```
 **Gene Count:** 5693
<br>**Genome sequence total length:** 23332839
<br>**Chromosome Names:** Pf3D7_01_v3, Pf3D7_02_v3, Pf3D7_03_v3, ...
<br>**Chromosome Lenght:**
| Chromosome | Length |
|------------|-----------|
| Pf3D7_01_v3 | 640851  |
| Pf3D7_02_v3 | 947102  |
| Pf3D7_03_v3 | 1067971 |
| Pf3D7_04_v3 | 1200490 |
| Pf3D7_05_v3 | 1343557 |
| Pf3D7_06_v3 | 1418242 |
| Pf3D7_07_v3 | 1445207 |
| Pf3D7_08_v3 | 1472805 |
| Pf3D7_09_v3 | 1541735 |
| Pf3D7_10_v3 | 1687656 |

<br>Please see <em>/nfs/cellgeni/STAR/malaria/3D7/index/Log.out</em> for more information/Chromosomes
<br>**Build Command:**

```
STAR   --runMode genomeGenerate      --runThreadN 16   --genomeDir index   --genomeFastaFiles ensembl_37_genome-3D7_Jan16v3.fa      --genomeSAindexNbases 11   --sjdbGTFfile Plasmodium_falciparum.EPr1.37.gtf
```
# Mouse
## 2020A
<br>**STAR version:** 2.7.7a
<br>**Path:**

```
/nfs/cellgeni/STAR/mouse/2020A/index
```
 **Gene Count:** 32285
<br>**Genome sequence total length:** 2730871774
<br>**Chromosome Names:** chr1, chr10, chr11, ... 
<br>**Chromosome Lenght:**
| Chromosome | Length |
|------------|-----------|
| chr1  | 195471971 |
| chr10 | 130694993 |
| chr11 | 122082543 |
| chr12 | 120129022 |
| chr13 | 120421639 |
| chr14 | 124902244 |
| chr15 | 104043685 |
| chr16 | 98207768  |
| chr17 | 94987271  |
| chr18 | 90702639  |

<br>Please see <em>/nfs/cellgeni/STAR/mouse/2020A/index/Log.out</em> for more information/Chromosomes
<br>**Build Command:**

```
STAR   --runMode genomeGenerate   --runThreadN 4   --genomeDir STAR   --genomeFastaFiles mm10_vM23_modified.fa      --sjdbGTFfile mm10_vM23_filtered.gtf   --sjdbOverhang 100
```
## 2020A Full
<br>**STAR version:** 2.7.9a
<br>**Path:**

```
/nfs/cellgeni/STAR/mouse/2020A-full/index
```
 **Gene Count:** 55421
<br>**Genome sequence total length:** 2730871774
<br>**Chromosome Names:** chr1, chr10, chr11, ...
<br>**Chromosome Lenght:**
| Chromosome | Length |
|------------|-----------|
| chr1  | 195471971 |
| chr10 | 130694993 |
| chr11 | 122082543 |
| chr12 | 120129022 |
| chr13 | 120421639 |
| chr14 | 124902244 |
| chr15 | 104043685 |
| chr16 | 98207768  |
| chr17 | 94987271  |
| chr18 | 90702639  |

<br>Please see <em>/nfs/cellgeni/STAR/mouse/2020A-full/index/Log.out</em> for more information/Chromosomes
<br>**Build Command:**

```
STAR   --runMode genomeGenerate      --runThreadN 4   --genomeDir index   --genomeFastaFiles mm10_vM23_modified.fa      --sjdbGTFfile mm10_vM23_modified.gtf
```
## 1.2.0
<br>**STAR version:** 2.7.9a
<br>**Path:**

```
/nfs/cellgeni/STAR/mouse/1.2.0/index
```
 **Gene Count:** 27998
<br>**Genome sequence total length:** 2730871774
<br>**Chromosome Names:** 1, 10, 11, ...
<br>**Chromosome Lenght:**
| Chromosome | Length |
|------------|-----------|
| 1  | 195471971 |
| 10 | 130694993 |
| 11 | 122082543 |
| 12 | 120129022 |
| 13 | 120421639 |
| 14 | 124902244 |
| 15 | 104043685 |
| 16 | 98207768  |
| 17 | 94987271  |
| 18 | 90702639  |

<br>Please see <em>/nfs/cellgeni/STAR/mouse/1.2.0/index/Log.out</em> for more information/Chromosomes
<br>**Build Command:**

```
STAR   --runMode genomeGenerate      --runThreadN 4   --genomeDir STAR   --genomeFastaFiles Mus_musculus.GRCm38.dna.primary_assembly.fa      --sjdbGTFfile Mus_musculus.GRCm38.84.filtered.gtf   --sjdbOverhang 90
```
## 2.1.0
<br>**STAR version:** 2.7.9a
<br>**Path:**

```
/nfs/cellgeni/STAR/mouse/2.1.0/index
```
 **Gene Count:** 28692
<br>**Genome sequence total length:** 2730871774
<br>**Chromosome Names:** 1, 10, 11, ...
<br>**Chromosome Lenght:**
| Chromosome | Length |
|------------|-----------|
| 1  | 195471971 |
| 10 | 130694993 |
| 11 | 122082543 |
| 12 | 120129022 |
| 13 | 120421639 |
| 14 | 124902244 |
| 15 | 104043685 |
| 16 | 98207768  |
| 17 | 94987271  |
| 18 | 90702639  |

<br>Please see <em>/nfs/cellgeni/STAR/mouse/2.1.0/index/Log.out</em> for more information/Chromosomes
<br>**Build Command:**

```
STAR   --runMode genomeGenerate      --runThreadN 4   --genomeDir STAR   --genomeFastaFiles Mus_musculus.GRCm38.dna.primary_assembly.fa      --sjdbGTFfile Mus_musculus.GRCm38.84.filtered.gtf   --sjdbOverhang 90
```
## 3.0.0
<br>**STAR version:** 2.7.9a
<br>**Path:**

```
/nfs/cellgeni/STAR/mouse/3.0.0/index
```
 **Gene Count:** 31053
<br>**Genome sequence total length:** 2730871774
<br>**Chromosome Names:** 1, 10, 11, ...
<br>**Chromosome Lenght:**
| Chromosome | Length |
|------------|-----------|
| 1  | 195471971 |
| 10 | 130694993 |
| 11 | 122082543 |
| 12 | 120129022 |
| 13 | 120421639 |
| 14 | 124902244 |
| 15 | 104043685 |
| 16 | 98207768  |
| 17 | 94987271  |
| 18 | 90702639  |

<br>Please see <em>/nfs/cellgeni/STAR/mouse/3.0.0/index/Log.out</em> for more information/Chromosomes
<br>**Build Command:**

```
STAR   --runMode genomeGenerate      --runThreadN 4   --genomeDir STAR   --genomeFastaFiles Mus_musculus.GRCm38.dna.primary_assembly.fa      --sjdbGTFfile Mus_musculus.GRCm38.93.filtered.gtf   --sjdbOverhang 90
```
# Toxoplasma Gondii
## gt1_gca_00149715

<br>**STAR version:** 2.7.9a
<br>**Path:**

```
/nfs/cellgeni/STAR/Toxoplasma_gondii/gt1_gca_00149715/index
```
 **Gene Count:** 8637
<br>**Genome sequence total length:** 65062235
<br>**Chromosome Names:** KE387274.1, KE387275.1, KE387276.1, ...
<br>**Chromosome Lenght:**
| Chromosome | Length |
|------------|-----------|
| KE387274.1 | 6945667 |
| KE387275.1 | 384772  |
| KE387276.1 | 6795584 |
| KE387277.1 | 4721207 |
| KE387278.1 | 4666718 |
| KE387279.1 | 4652972 |
| KE387280.1 | 4225262 |
| KE387281.1 | 859182  |
| KE387282.1 | 43610   |
| KE387283.1 | 2730344 |

<br>Please see <em>/nfs/cellgeni/STAR/Toxoplasma_gondii/gt1_gca_00149715/index/Log.out</em> for more information/Chromosomes
<br>**Build Command:**

```
STAR   --runMode genomeGenerate      --runThreadN 4   --genomeDir STAR   --genomeFastaFiles GCA_000149715.2_TGGT1_genomic.fna      --genomeSAindexNbases 11   --sjdbGTFfile GCA_000149715.2_TGGT1_genomic.gtf   --sjdbOverhang 100
```
