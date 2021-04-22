# Elucidata Gene Discovery Project
 A gene is the basic physical and functional unit of heredity. Genes are made up of DNA. Some
genes act as instructions to make molecules called proteins. Scientists keep track of genes by
giving them unique names. During gene expression, the DNA is first copied into RNA. The RNA
can be directly functional or be the intermediate template for a protein that performs a function.
Ribonucleic acid (RNA) is a polymeric molecule essential in various biological roles in coding,
decoding, regulation and expression of genes. RNA and DNA are nucleic acids, and, along with
lipids, proteins and carbohydrates, constitute the four major macromolecules essential for all
known forms of life.
RNA-Seq (RNA sequencing), is a sequencing technique to reveal the presence and quantity of
RNA in a biological sample at a given moment.
We have the data here for an RNA-Seq experiment of a cancer tumor tissue sequenced at
different time points.
To reduce experimental errors, the cells of the tissue were replicated into three pools for the
tissue and each pool of cells was sequenced at the beginning(0hrs), 4hrs, 5hrs, 6hrs...12hrs.
As a result, we have measurements of each gene in 30 samples.
Files:-
1. gene_data_anomaly.csv - contains the normalized counts after RNA sequencing for
every gene for samples S1, S2,..., S30.
2. MetaData.csv - contains the time at which each sample was collected.
Due to an anomaly in the system, the data has missing values(NaNs) at certain data points.
This is a bottleneck for further processing of data and we need to deal with this missing data.
