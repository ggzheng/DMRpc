Here provides R scripts to perform DMR analyses using DMRpc. 

For annotation data, you can download it at the Illumnina website. The Illumina EPIC annotation data can be found at the Illumnina website: https://support.illumina.com/array/array_kits/infinium-methylationepic-beadchip-kit/downloads.html. We used "Infinium MethylationEPIC v1.0 B4 Manifest File (CSV Format)" and saved it as "MethylationEPIC_v_1_0_B4.csv".

Before you run the DMRpc R script, you should save these three files under this: MethylationEPIC_v_1_0_B4.csv, regions_genic.csv, regions_intergenic.csv. The two files regions_genic.csv and regions_intergenic.csv are available under the same directory, which  are pre-define genoic regions annoated with and without genes based the EPIC annotation file.
