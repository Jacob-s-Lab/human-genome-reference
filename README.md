# HumanGenome
這是一份探討參考序列的專案，包含參考序列的內容組成、發展過程及各版本的差異介紹。我們定期關注Illumina, DRAGEN, GATK等從事定序分析的團隊，研究其使用的參考序列及社群文章，以提供參考序列的最新資訊    
Here is the repo for the human genome reference files and other related files
More information can be found [Reference genomes and Gene models impact on variant interpretation](https://bioinfo-diag.fr/wp-content/uploads/2019/10/BioinfoDiag_2019_EAY.pdf)

## Brief introduction
人類參考序列的建立始於2003年Human Genome Project完成的第一個人類全基因體定序，此後隨定序技術的精進與不同基因體計畫的進行，參考序列的解析度也隨之增加、並推出新版本，這些版本的差異，除了主要版本--GRCh37/hg19及GRCh38/hg38的差異外，版本內部也有些微差異，例如alternative contig及decoy sequence等額外序列。    
There are SO MANY different versions of human genome reference files for different research purposes. 
In general, there are several factors contributed to the version of reference genome including official release versions, alternative contigs, decoy sequence. 

### Release Version
參考序列的建立與維護主要由 Genome Reference Consortium (https://www.ncbi.nlm.nih.gov/grc)負責，目前研究常用的版本為GRCh37及GRCh38兩版，而主要版本內也存在patch形式的小幅度序列更新，如2013更新的GRCh37.p13以及2019年更新的GRCh38.p13版序列；如同前面所述，版本內部差異主要在alternative contig及decoy sequence，以下將簡單介紹兩名詞與相關資訊。       
Human genome reference is maintained by [Genome Reference Consortium] (https://www.ncbi.nlm.nih.gov/grc)
Currently, two major releases GRCh37 and GRCh38 are widely adopted by many international genome projects.  
Some regional fixes known as patches are also avalaible after each major assembly has been released.

### Alternative contigs
"alternative contig"指的是DNA序列與主要染色體相似的片段，雖然"alternative"常被認為和變異相關，但在分析族群資料時，常可以發現族群特有、不同於參考序列的片段，因此需獨立出來陳列於參考序列中，一方面減少定序分析時，誤把此序列當作致病變異的可能，一方面也可擴充序列資訊，讓參考序列更具有"全人類"的代表性與適用性。    
Here, I collected different versions of human genome

### Decoy
decoy是已知無意義DNA序列，其產生過程可能和反轉錄病毒感染人體時，會將病毒序列鑲嵌至人類序列的特性；根據研究證實，將deccoy sequence納入可有效提升分析精準度，以下網址為illumina針對decoy的處理參考：
https://support.illumina.com/content/dam/illumina-support/help/Illumina_DRAGEN_Bio_IT_Platform_v3_7_1000000141465/Content/SW/Informatics/Dragen/HandlingDecoyContigs_fDG.htm
Colons can be used to align columns.

| Tables        | Source           | Name  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |


### Broad Institute
Reference on [GCP] (https://console.cloud.google.com/storage/browser/gcp-public-data--broad-references;tab=objects?prefix=)

### Illumina

### DRAGEN

### PacBio
