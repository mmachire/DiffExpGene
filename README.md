# DiffExpGene

This package takes in the gff3, bam, and bai files to out put both the normalized gene count matrix and a data frame of the position information of the differentially expressed genes. I've included some test data - it is just some of the data that I've used for my analysis, but cropped. There are two functions, the Gene_Count_Martix function and the Genes_of_Tnterest function. 

To run the gene count function, run Gene_Count_Matrix("gff3 file","bamfile1","baifile1","bamfile2","baifile2"...) 

To get the genes of interest, run Genes_of_Interes("gff3file",the gene count matrix (out put from Gene_count_matrix),n) where n is the number of clusters. 

I've included examples of what the outputs should look like. 

After you have the genes of interest, you need to switch environments and move to Julia 1.4.1 
