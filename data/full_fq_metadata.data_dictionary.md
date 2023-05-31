1. **filename**: 
    - *Description*: This is a URL link to a .fastq file which contains the genetic sequencing data. These files are located in different directories corresponding to specific experimental setups 
and the genomic region sequenced.
    - *Data Type*: String (URL format)
    - *Example*: "https://ftp-trace.ncbi.nlm.nih.gov/ReferenceSamples/giab/data/AshkenazimTrio/analysis/MSSM_MsPAC_SVs_assemblies_06042019/HG002/MsPAC_assemblies/haplotype_2/chr1.fastq"
    - *Possible Values*: Any valid URL link to a .fastq file

2. **predicted_tech**: 
    - *Description*: This field specifies the technology or method used for the genetic sequencing.
    - *Data Type*: String
    - *Example*: "Assembly"
    - *Possible Values*: Any valid sequencing technology (e.g., "Assembly", "Illumina", "PacBio", etc.)

3. **metadata**: 
    - *Description*: This field provides additional information about the sequencing process and data. It is a JSON structure containing two key-value pairs. 
        - The first key, "tech", indicates the technology used, which is currently marked as "unimplemented parser".
        - The second key, "read_names", is a list that contains the names of individual reads or sequences in the .fastq file.
    - *Data Type*: JSON
    - *Example*: "{"tech": "unimplemented parser", "read_names": ["1.10000.176640.0_2.raw_contig.0.quivered", "1.10000.176640.0_2.raw_contig.2.quivered", 
"1.10000.176640.0_2.raw_contig.3.quivered", "1.10000.176640.0_2.raw_contig.4.quivered", "1.10000.176640.0_2.raw_contig.1.quivered"]}"
    - *Possible Values*: Any valid JSON structure as per the mentioned format.

