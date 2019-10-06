# TS1015_CEL-Seq2_pipeline


#These data and scripts are supplement to Say, T. E., & Degnan, S. M. (2019). Interdependent photo- and chemosensory systems regulate larval settlement in a marine sponge. bioRxiv, 519512. doi:10.1101/519512

#Samples were prepared according to the CEL-Seq2 protocol (Hashimshony et al., 2016). CEL-Seq2 reads were processed using a publicly available pipeline (https://github.com/yanailab/CEL-Seq-pipeline). This folder contains additional supplementary data, specifcally the files and scripts used to process the sequences obtained by CEL-Seq2. 

#Note, the final output of all of the samples and the read counts from the two lanes (demultiplexed and mapped using the same CEL-Seq pipeline) compiled into the counting reports used for downstream analyses.

"ampQue1_ERCC92_trimmed.fa" - Location of fasta file used to generate bowtie2 index for read mapping. This file is too large to be uploaded to github but has previously been published online in Sogabe, Shunsuke et al. (2019). File available from: Pluripotency and the origin of animal multicellularity, Dryad, Dataset, https://doi.org/10.5061/dryad.hp2fr73

"Aqu2.1_lncRNAs_ERCC_trimmed.gff3" - Gene coordinate file for the Aqu2.1 gene models

"CEL-Seq_barcode_sheet.tab" - Barcode index file used in the demultiplexing step

"TS1015_UMI_L001_config" - Configuration file for the CEL-Seq pipeline (L001)

"TS1015_UMI_L002_config_2016.02.07" - Configuration file for the CEL-Seq pipeline (L002). This has bee

"S1015_SampleSheet_L002.tab" - sample sheet file (L002) used as the input for the demultiplexing

"TS1015_SampleSheet.tab" - sample sheet file (L001) used as the input for the demultiplexing




References


Hashimshony, T., Senderovich, N., Avital, G., Klochendler, A., de Leeuw, Y., Anavy, L., . . . Yanai, I. (2016). CEL-Seq2: sensitive highly-multiplexed single-cell RNA-Seq. Genome Biology, 17(1), 1-7. doi:10.1186/s13059-016-0938-8

Sogabe, S., Hatleberg, W. L., Kocot, K. M., Say, T. E., Stoupin, D., Roper, K. E., . . . Degnan, B. M. (2019). Pluripotency and the origin of animal multicellularity. Nature, 570(7762), 519-522. doi:10.1038/s41586-019-1290-4
