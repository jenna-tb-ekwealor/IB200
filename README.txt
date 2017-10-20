################################################################################
README for ftp://ftp.ncbi.nlm.nih.gov/genomes/
Last updated:  March 14, 2016
################################################################################

********** Many directories under ftp://ftp.ncbi.nlm.nih.gov/genomes/ **********
*********               were moved on 02-DEC-2015                     **********

Assembled genome sequence and annotation data for RefSeq genome assemblies is 
now being provided under:
     ftp://ftp.ncbi.nlm.nih.gov/genomes/refseq
 
On 02 December 2015 the old directories and files listed below were moved as 
indicated.

Moved to ftp://ftp.ncbi.nlm.nih.gov/genomes/archive/old_refseq/
The content of these directories will not be updated.
  Aedes_aegypti
  Anopheles_gambiae
  Arabidopsis_lyrata
  Arabidopsis_thaliana
  ASSEMBLY_BACTERIA
  Bacteria
  Bacteria_DRAFT
  Branchiostoma_floridae
  Caenorhabditis_elegans
  Chloroplasts
  CLUSTERS
  Drosophila_melanogaster
  Drosophila_pseudoobscura
  Fungi
  Medicago_truncatula
  MITOCHONDRIA
  Physcomitrella_patens
  PLANTS
  Plasmids
  Populus_trichocarpa
  Protozoa
  Sorghum_bicolor

Moved to ftp://ftp.ncbi.nlm.nih.gov/genomes/archive/
  old_genomeID2nucGI

Moved to ftp://ftp.ncbi.nlm.nih.gov/genomes/GENOME_REPORTS/
  IDS

********************************************************************************

================================================================================
NOTIFICATION OF CHANGE: 

August 21, 2014 & August 3, 2015  
-----------------------------------
Assembled genome sequence and annotation data is now comprehensively provided 
in three new directories: all, genbank, and refseq. 

Data are provided for all current assemblies available in NCBI's Assembly 
resource (www.ncbi.nlm.nih.gov/assembly) using standardized file names. The 
initial August 2014 release, and the February & August 2015 updates, include 
various data formats including fasta, GenBank and GenPept flat file, and GFF. 
RepeatMasker results are provided for eukaryotic genomes. A file with 
md5checksums is also provided for each assembly.
================================================================================

=======================
Background Information:
=======================
The genomes FTP site provides sequence, annotation, and meta-data for all 
sequenced and assembled genomes that are available in NCBI's Assembly resource 
in addition to select additional project-oriented datasets.  Annotation data is 
provided when available for assemblies that have been submitted to the 
International Sequence Nucleotide Database Collaboration (INSDC) including 
NCBI's GenBank database.  RefSeq genomes are a subset of the genomes available 
in INSDC and all include annotation, except for some viruses. RefSeq annotation 
content originates from NCBI's prokaryotic, eukaryotic, organelle, or viral 
annotation pipelines, or is propagated from the GenBank submission.


Available by anonymous FTP at:

        ftp://ftp.ncbi.nlm.nih.gov/genomes/

Please refer to README files and the FTP FAQ for additional information:
       http://www.ncbi.nlm.nih.gov/genome/doc/ftpfaq/


=====================
Directory structure:
=====================
Comprehensive reports of sequence and annotation data for assembled genomes 
(that are available in NCBI's Assembly resource) are provided in three 
directory areas:

Genome sequence and annotation data:
------------------------------------
1) all:     content is the union of GenBank and RefSeq assemblies. 
            Subdirectories are provided per assembly accession and version.
            [This directory is not suitable for browsing because it holds many 
            thousands of entries.] Only subdirectories for "latest" assemblies
            are refreshed when annotation is updated or when software updates
            are released, so new file formats or improvements to existing 
            formats are not available for non-latest assemblies.
2) genbank: content includes primary submissions of assembled genome sequence 
            and associated annotation data, if any, as exchanged among members 
            of the International Nucleotide Sequence Database Collaboration, 
            of which NCBI's GenBank database is a member. The GenBank directory 
            area includes genome sequence data for a larger number of organisms 
            than the RefSeq directory area; however, some assemblies are 
            unannotated. The sub-directory structure includes:
            a. archaea
            b. bacteria
            c. fungi
            d. invertebrate
            e. other -  this directory includes synthetic genomes
            f. plant
            g. protozoa
            h. vertebrate_mammalian
            i. vertebrate_other
3) refseq:  content includes assembled genome sequence and RefSeq annotation 
            data. All prokaryotic and eukaryotic RefSeq genomes have annotation. 
            RefSeq annotation data may be calculated by NCBI annotation  
            pipelines or propagated from the GenBank submission. The RefSeq 
            directory area includes fewer organisms than the GenBank directory
            area because not all genome assemblies are selected for the RefSeq
            project. 
            Sub-directories include:
            a. archaea
            b. bacteria
            c. fungi
            d. invertebrate
            e. plant
            f. protozoa
            g. vertebrate_mammalian
            h. vertebrate_other 
            i. viral
            j. mitochondrion [Content of the mitochondrion, plasmid and plastid
            k. plasmid     directories is from the RefSeq release FTP site. See 
            l. plastid     ftp://ftp.ncbi.nlm.nih.gov/refseq/release/README]

See ftp://ftp.ncbi.nlm.nih.gov/genomes/all/README.txt for a more detailed
description of the organization of these directories, the data provided per 
assembly and a description of the files.


Additional directories:
-----------------------
Meta-data related to the Assembly and Genome resources are available here:

1) ASSEMBLY_REPORTS: content consists of two summary reports as well as a 
     separate report for each assembly, conveying meta-data for GenBank and 
     RefSeq genome assemblies and associated sequence and other identifiers. 
     The two summary report files include meta-data details of either all the 
     GenBank assemblies or all the RefSeq assemblies. 
          assembly_summary_genbank.txt
          assembly_summary_refseq.txt
     These summary files provide a ftp path that can be used to retrieve the 
     sequence and annotation data.  
     Reports are provided by the Assembly resource:
          www.ncbi.nlm.nih.gov/assembly/

2) GENOME_REPORTS:  content consists of summary reports of genome sequencing 
     projects, associated annotation statistics, and some defined reference 
     datasets within the RefSeq project. Reports are provided by the Genomes 
     resource:
          www.ncbi.nlm.nih.gov/genomes/

Several directories are also provided for other data groups including:
     INFLUENZA: sequence and annotation of INSDC influenza viruses
     HUMAN_MICROBIOM: sequence, annotation, and meta-data from the Human 
          Microbiome Project (HMP)
     MapView: sequence and non-sequence map data available in the Map Viewer 
          resource (www.ncbi.nlm.nih.gov/mapview/)
     TARGET: sequence data from the RefSeq rRNA project
     TOOLS: select genomic tools
     Viruses: sequence and annotation of RefSeq viral genomes

The following directories will be removed in 2016:
---------------------------------------------------
Genus_species directories: existing data will be archived to directories 
                           within the /genomes/archive/old_refseq/ path.

________________________________________________________________________________
National Center for Biotechnology Information (NCBI)
National Library of Medicine
National Institutes of Health
8600 Rockville Pike
Bethesda, MD 20894, USA
tel: (301) 496-2475
fax: (301) 480-9241
e-mail: info@ncbi.nlm.nih.gov
________________________________________________________________________________
