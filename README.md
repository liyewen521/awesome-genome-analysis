# Awesome Genome Analysis
A collection of papers on awesome genome analysis, e.g., architectures, systems, and algorithms.

- [Architecture](#architecture)
- [HPC System](#system)
- [Algorithm](#algorithm)
- [Future System](#future-system)

## Architecture
Genome analysis architecture at top-tier conferences (e.g., HPCA, ASPLOS, ISCA, MICRO, ISSCC, DAC, etc).

| Year | Conf.      | Paper                                                                                                                                                        | Affiliation |
| ---- | ---------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---- |
| 2018 | HPCA       | Searching for Potential gRNA Off-Target Sites for CRISPR/Cas9 Using Automata Processing Across Different Platforms                                           | UVA  |
| 2018 | ASPLOS     | Darwin: A Genomics Co-processor Provides up to 15000X Acceleration on Long Read Assembly                                                                     | Stanford University |
| 2018 | ISCA       | GenAx: A Genome Sequencing Accelerator                                                                                                                       | UofM |
||||<br>
| 2019 | HPCA       | Darwin-WGA: A Co-processor Provides Increased Sensitivity in Whole Genome Alignments with High Speed                                                         | Stanford University |
| 2019 | HPCA       | FPGA Accelerated INDEL Realignment in the Cloud                                                                                                              | UCB  |
| 2019 | MICRO      | GenCache: Leveraging In-Cache Operators for Efficient Sequence Alignment                                                                                     | University of Utah |
| 2019 | MICRO      | MEDAL: Scalable DIMM-based Near Data Processing Accelerator for DNA Seeding Algorithm                                                                        | UCSB  |
||||<br>
| 2020 | ISCA       | Genesis: A Hardware Acceleration Framework for Genomic Data Analysis                                                                                         | SNU |
| 2020 | MICRO      | SeedEx: A Genome Sequencing Accelerator for Optimal Alignments in Subminimal Space                                                                           | UofM  |
| 2020 | MICRO      | GenASM: A High-Performance, Low-Power Approximate String Matching Acceleration Framework for Genome Sequence Analysis                                        | ETHZ |
| 2020 | ISSCC      | A Fully Integrated Genetic Variant Discovery SoC for Next-Generation Sequencing                                                                              | NTU  |
| 2020 | DAC        | PIM-Assembler: A Processing-in-Memory Platform for Genome Assembly                                                                                           | Arizona State University  |
||||<br>
| 2021 | HPCA       | EXMA: A Genomics Accelerator for Exact-Matching                                                                                                              | Indiana University Bloomington |
| 2021 | ISCA       | Accelerated Seeding for Genome Sequence Alignment with Enumerated Radix Trees                                                                                | UofM  |
| 2021 | ISCA       | Sieve: Scalable In-situ DRAM-based Accelerator Designs for Massively Parallel k-mer Matching                                                                 | UVA |
| 2021 | MICRO      | SquiggleFilter: An Accelerator for Portable Virus Detection                                                                                                  | UofM  |
||||<br>
| 2022 | ASPLOS     | GenStore: a high-performance in-storage processing system for genome sequence analysis                                                                       | ETHZ |
| 2022 | ASPLOS     | ProSE: the architecture and design of a protein discovery engine                                                                                             | Duke  |
| 2022 | ISCA       | SeGraM: a universal hardware accelerator for genomic sequence-to-graph and sequence-to-sequence mapping                                                      | ETHZ |
| 2022 | ISCA       | BioHD: an efficient genome sequence search platform using HyperDimensional memorization                                                                      | UCI  |
| 2022 | ISCA       | EDAM: Edit Distance tolerant Approximate Matching content addressable memory                                                                                 | Technion-Israel Institute of Technology |
| 2022 | MICRO      | BEACON: Scalable Near-Data-Processing Accelerators for Genome Analysis near Memory Pool with the CXL Support                                                 | UCSB |
| 2022 | MICRO      | GenPIP: In-Memory Acceleration of Genome Analysis via Tight Integration of Basecalling and Read Mapping                                                      | ETHZ |
||||<br>
| 2023 | HPCA       | NvWa: Enhancing Sequence Alignment Accelerator Throughput via Hardware Scheduling                                                                            | ICT, CAS |
| 2023 | ISCA       | GenDP: A Framework of Dynamic Programming Acceleration for Genome Sequencing Analysis                                                                        | UofM  |
| 2023 | MICRO      | Swordfish: A Framework for Evaluating Deep Neural Network-based Basecalling using Computation-In-Memory with Non-Ideal Memristors                            | ETHZ |
| 2023 | MICRO      | DASH-CAM: Dynamic Approximate SearcH Content Addressable Memory for genome classification                                                                    | Bar-Ilan University  |
| 2023 | MICRO      | CASA: An Energy-Efficient and High-Speed CAM-based SMEM Seeding Accelerator for Genome Alignment                                                             | THU |
| 2023 | MICRO      | GMX: Instruction Set Extensions for Fast, Scalable, and Efficient Genome Sequence Alignment                                                                  | BSC |
| 2023 | ISSCC      | A Fully Integrated End-to-End Genome Analysis Accelerator for Next-Generation Sequencing                                                                     | NTU |
| 2023 | DAC        | Invited: Accelerating Genome Analysis via Algorithm-Architecture Co-Design                                                                                   | ETHZ |
| 2023 | DAC        | ASMCap: An Approximate String Matching Accelerator for Genome Sequence Analysis Based on Capacitive Content Addressable Memory                               | THU |
| 2023 | DAC        | MeG2: In-Memory Acceleration for Genome Graphs Analysis                                                                                                      | HUST |
| 2023 | DAC        | UpPipe: A Novel Pipeline Management on In-Memory Processors for RNA-seq Quantification                                                                       | National Cheng Kung University |
||||<br>
| 2024 | HPCA       | TALCO: Tiling Genome Sequence Alignment Using Convergence of Traceback Pointers                                                                              | UCSD |
| 2024 | ASPLOS     | Harp: Leveraging Quasi-Sequential Characteristics to Accelerate Sequence-to-Graph Mapping of Long Reads                                                      | THU  |
| 2024 | ISCA       | QUETZAL: Vector Acceleration Framework For Modern Genome Sequence Analysis                                                                                   | BSC |
| 2024 | ISCA       | BLESS: Bandwidth and Locality Enhanced SMEM Seeding Acceleration for DNA Sequencing                                                                          | KAIST |
| 2024 | ISCA       | MegIS: High-Performance, Energy-Efficient, and Low-Cost Metagenomic Analysis with In-Storage Processing                                                      | ETHZ |


## HPC System
Genome analysis systems at top-tier conferences (e.g., PPoPP, SC, etc).

| Year | Conf.      | Paper                                                                                                                                                        | Affiliation |
| ---- | ---------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---- |
| 2018 | PPoPP      | High-performance genomic analysis framework with in-memory computing                                                                                         | ICT, CAS  |
| 2018 | SC         | Extreme scale de novo metagenome assembly                                                                                                                    | Intel |
| 2018 | SC         | Optimizing high performance distributed memory parallel hash tables for DNA k-mer counting                                                                   | Georgia Tech |
||||<br>
| 2020 | SC         | Distributed many-to-many protein sequence alignment using sparse matrices                                                                                    | Lawrence Berkeley National Laboratory |
| 2020 | SC         | SegAlign: a scalable GPU-based whole genome aligner                                                                                                          | Stanford  |
||||<br>
| 2021 | PPoPP      | Asynchrony versus bulk-synchrony for a generalized N-body problem from genomics                                                                              | UCB |
| 2021 | SC         | Accelerating large scale de novo metagenome assembly using GPUs                                                                                              | Lawrence Berkeley National Laboratory |
| 2021 | SC         | FastZ: accelerating gapped whole genome alignment on GPUs                                                                                                    | Purdue University |
| 2021 | SC         | High-throughput virtual screening of small molecule inhibitors for SARS-CoV-2 protein targets with deep fusion models                                        | Lawrence Livermore National Laboratory |
||||<br>
| 2022 | SC         | Extreme-Scale Many-Against-Many Protein Similarity Search                                                                                                    | Lawrence Berkeley National Laboratory |
||||<br>
| 2023 | PPoPP      | High-Performance and Scalable Agent-Based Simulation with BioDynaMo                                                                                          | ETHZ |
| 2023 | SC         | Space Efficient Sequence Alignment for SRAM-Based Computing: X-Drop on the Graphcore IPU                                                                     | Simula Research Laboratory |
||||<br>
| 2024 | PPoPP      | AGAThA: Fast and Efficient GPU Acceleration of Guided Sequence Alignment for Long Read Mapping                                                               | Seoul National University |
| 2024 | PPoPP      | FastFold: Optimizing AlphaFold Training and Inference on GPU Clusters                                                                                        | National University of Singapore  |

## Algorithm
Genome analysis algorithm at top-tier journals (e.g., Bioinformatics, NeurIPS, etc).

| Year | Journal         | Paper                                                                                                                                                        | Affiliation |
| ---- | ----------      | ------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---- |
| 2009 | Bioinformatics  | Fast and accurate short read alignment with Burrows-Wheeler transform                                                                                        | Wellcome Trust Sanger Institute |
| 2010 | Bioinformatics  | Fast and accurate long-read alignment with Burrows–Wheeler transform                                                                                         | Wellcome Trust Sanger Institute |
| 2010 | arXiv           | Aligning sequence reads, clone sequences and assembly contigs with BWA-MEM                                                                                   | Broad Institute |
| 2019 | NeurIPS         | LISA: Towards Learned DNA Sequence Search                                                                                                                    | MIT |
| 2022 | Bioinformatics  | BWA-MEME: BWA-MEM emulated with a machine learning approach                                                                                                  | KAIST  |

## Future System
Future genome analysis systems at top-tier journals (e.g., Nature, Science, etc).

| Year | Journal           | Paper                                                                                                                                                        | Affiliation |
| ---- | ----------        | ------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---- |
| 2021 | Nature Materials  | Random access DNA memory using Boolean search in an archival file storage system                                                                             | MIT |
| 2023 | Nature            | DNA-based programmable gate arrays for general-purpose DNA computing                                                                                         | SJTU |
| 2024 | Nature            | Parallel molecular data storage by printing epigenetic bits on DNA                                                                                           | PKU |


# Contribute
This is an active repository and your contributions are always welcome! Do not hesitate to create pull requests.
