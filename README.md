# Awesome Genome Analysis
A collection of papers on awesome genome analysis, e.g., architectures, chips, systems, and software.

## Architecture
Genome analysis architecture at top-tier conferences (e.g., HPCA, ASPLOS, ISCA, MICRO, PACT, etc).

| Year | Conf.      | Paper                                                                                                                                                        | Keywords | Affiliation | 
| :--: | :--------: | :----------------------------------------------------------------------------------------------------------------------------------------------------------: | :--: | :--: |
| 2014 | ISCA       | Race Logic: A Hardware Acceleration for Dynamic Programming Algorithms                                                                                       | Dynamic Programming | UCSB |
||||<br>
| 2018 | HPCA       | Searching for Potential gRNA Off-Target Sites for CRISPR/Cas9 Using Automata Processing Across Different Platforms                                           | gRNA Search, Automata | UVA  |
| 2018 | ASPLOS     | Darwin: A Genomics Co-processor Provides up to 15000X Acceleration on Long Read Assembly                                                                     | Long-Read Alignment | Stanford University |
| 2018 | ISCA       | GenAx: A Genome Sequencing Accelerator                                                                                                                       | Short-Read Alignment | UofM |
||||<br>
| 2019 | HPCA       | Darwin-WGA: A Co-processor Provides Increased Sensitivity in Whole Genome Alignments with High Speed                                                         | Whole Genome Alignment | Stanford University |
| 2019 | HPCA       | FPGA Accelerated INDEL Realignment in the Cloud                                                                                                              | INDEL Realignment | UCB |
| 2019 | MICRO      | GenCache: Leveraging In-Cache Operators for Efficient Sequence Alignment                                                                                     | Seeding Phase, Read Alignment | University of Utah |
| 2019 | MICRO      | MEDAL: Scalable DIMM-based Near Data Processing Accelerator for DNA Seeding Algorithm                                                                        | Seeding Phase, Read Alignment | UCSB |
||||<br>
| 2020 | ISCA       | Genesis: A Hardware Acceleration Framework for Genomic Data Analysis                                                                                         | Short-Read Analysis Framework | SNU |
| 2020 | MICRO      | SeedEx: A Genome Sequencing Accelerator for Optimal Alignments in Subminimal Space                                                                           | Extension Phase, Read Alignment | UofM |
| 2020 | MICRO      | GenASM: A High-Performance, Low-Power Approximate String Matching Acceleration Framework for Genome Sequence Analysis                                        | Extension Phase, Read Alignment | ETHZ |
| 2020 | PACT       | Helix: Algorithm / Architecture Co-design for Accelerating Nanopore Genome Base-calling                                                                      | Nanopore Base-calling | Indiana University Bloomington |
||||<br>
| 2021 | HPCA       | EXMA: A Genomics Accelerator for Exact-Matching                                                                                                              | Seeding Phase, Read Alignment | Indiana University Bloomington |
| 2021 | ISCA       | Accelerated Seeding for Genome Sequence Alignment with Enumerated Radix Trees                                                                                | Seeding Phase, Read Alignment | UofM |
| 2021 | ISCA       | Sieve: Scalable In-situ DRAM-based Accelerator Designs for Massively Parallel k-mer Matching                                                                 | K-mer Matching | UVA |
| 2021 | MICRO      | SquiggleFilter: An Accelerator for Portable Virus Detection                                                                                                  | Targeted Sequencing | UofM |
| 2021 | PACT       | Ultra efficient acceleration for de novo genome assembly via near-memory computing                                                                           | De Novo Assembly | UCSD |
||||<br>
| 2022 | ASPLOS     | GenStore: a high-performance in-storage processing system for genome sequence analysis                                                                       | Read Alignment | ETHZ |
| 2022 | ASPLOS     | ProSE: the architecture and design of a protein discovery engine                                                                                             | Protein Discovery | Duke |
| 2022 | ISCA       | SeGraM: a universal hardware accelerator for genomic sequence-to-graph and sequence-to-sequence mapping                                                      | Sequence-to-Graph Alignment | ETHZ |
| 2022 | ISCA       | BioHD: an efficient genome sequence search platform using HyperDimensional memorization                                                                      | Genome Sequence Search | UCI |
| 2022 | ISCA       | EDAM: Edit Distance tolerant Approximate Matching Content Addressable Memory                                                                                 | Targeted Sequencing | Technion-Israel Institute of Technology |
| 2022 | MICRO      | BEACON: Scalable Near-Data-Processing Accelerators for Genome Analysis near Memory Pool with the CXL Support                                                 | Genome Analysis, CXL | UCSB |
| 2022 | MICRO      | GenPIP: In-Memory Acceleration of Genome Analysis via Tight Integration of Basecalling and Read Mapping                                                      | Nanopore Base-calling, Read Alignment | ETHZ |
||||<br>
| 2023 | HPCA       | NvWa: Enhancing Sequence Alignment Accelerator Throughput via Hardware Scheduling                                                                            | Read Alignment | ICT, CAS |
| 2023 | ISCA       | GenDP: A Framework of Dynamic Programming Acceleration for Genome Sequencing Analysis                                                                        | Dynamic Programming Framework, Read Alignment | UofM |
| 2023 | MICRO      | Swordfish: A Framework for Evaluating Deep Neural Network-based Basecalling using Computation-In-Memory with Non-Ideal Memristors                            | Nanopore Base-calling | ETHZ |
| 2023 | MICRO      | DASH-CAM: Dynamic Approximate Search Content Addressable Memory for Genome Classification                                                                    | Targeted Sequencing | Bar-Ilan University |
| 2023 | MICRO      | CASA: An Energy-Efficient and High-Speed CAM-based SMEM Seeding Accelerator for Genome Alignment                                                             | Seeding Phase, Read Alignment | THU |
| 2023 | MICRO      | GMX: Instruction Set Extensions for Fast, Scalable, and Efficient Genome Sequence Alignment                                                                  | Extension Phase, Read Alignment | BSC |
||||<br>
| 2024 | HPCA       | TALCO: Tiling Genome Sequence Alignment Using Convergence of Traceback Pointers                                                                              | Extension Phase, Read Alignment | UCSD |
| 2024 | ASPLOS     | Harp: Leveraging Quasi-Sequential Characteristics to Accelerate Sequence-to-Graph Mapping of Long Reads                                                      | Sequence-to-Graph Alignment | THU |
| 2024 | ISCA       | QUETZAL: Vector Acceleration Framework For Modern Genome Sequence Analysis                                                                                   | Dynamic Programming Framework, Read Alignment | BSC |
| 2024 | ISCA       | BLESS: Bandwidth and Locality Enhanced SMEM Seeding Acceleration for DNA Sequencing                                                                          | Seeding Phase, Read Alignment | KAIST |
| 2024 | ISCA       | MegIS: High-Performance, Energy-Efficient, and Low-Cost Metagenomic Analysis with In-Storage Processing                                                      | Metagenomic Analysis | ETHZ |
||||<br>
| 2025 | ISCA       | LightNobel: Improving Sequence Length Limitation in Protein Structure Prediction Model via Adaptive Activation Quantization                                  | Protein Structure Prediction | KAIST |
| 2025 | ISCA       | NMP-PaK: Near-Memory Processing Acceleration of Scalable De Novo Genome Assembly                                                                             | De Novo Assembly | University of Colorado |


## Chip and EDA
Genome analysis chip or EDA at top-tier conferences (e.g., ISSCC, DAC, etc).

| Year | Conf.      | Paper                                                                                                                                                        | Keywords | Affiliation | 
| :--: | :--------: | :----------------------------------------------------------------------------------------------------------------------------------------------------------: | :--: | :--: |
| 2020 | ISSCC      | A Fully Integrated Genetic Variant Discovery SoC for Next-Generation Sequencing                                                                              | Short-Read Analysis | NTU |
| 2020 | DAC        | PIM-Assembler: A Processing-in-Memory Platform for Genome Assembly                                                                                           | De Novo Assembly | Arizona State University |
||||<br>
| 2023 | ISSCC      | A Fully Integrated End-to-End Genome Analysis Accelerator for Next-Generation Sequencing                                                                     | Short-Read Analysis | NTU |
| 2023 | DAC        | Invited: Accelerating Genome Analysis via Algorithm-Architecture Co-Design                                                                                   | Genome Analysis Survey | ETHZ |
| 2023 | DAC        | ASMCap: An Approximate String Matching Accelerator for Genome Sequence Analysis Based on Capacitive Content Addressable Memory                               | Extension Phase, Read Alignment | THU |
| 2023 | DAC        | MeG2: In-Memory Acceleration for Genome Graphs Analysis                                                                                                      | Sequence-to-Graph Alignment | HUST |
| 2023 | DAC        | UpPipe: A Novel Pipeline Management on In-Memory Processors for RNA-seq Quantification                                                                       | RNA Sequence Quantification | National Cheng Kung University |
||||<br>
| 2025 | DAC        | AutoRE: Bayesian-Optimization-based Automatic Reliability Enhancement Tool for Flow-based Microfluidic Biochips                                              | Flow-based Microfluidic Biochips | CUHK |
| 2025 | DAC        | DANN: Diffractive Acoustic Neural Network for in-sensor computing system target at multi-biomarker diagnosis                                                 | Multi-Biomarker Diagnosis | HKU |

## HPC System
Genome analysis systems at top-tier conferences (e.g., PPoPP, SC, etc).

| Year | Conf.      | Paper                                                                                                                                                        | Keywords | Affiliation | 
| :--: | :--------: | :----------------------------------------------------------------------------------------------------------------------------------------------------------: | :--: | :--: |
| 2006 | SC         | Locality and Parallelism Optimization for Dynamic Programming Algorithm in Bioinformatics                                                                    | Dynamic Programming | ICT, CAS |
||||<br>
| 2015 | SC         | HipMer: an extreme-scale de novo genome assembler                                                                                                            | De Novo Assembly | UCB |
||||<br>
| 2018 | PPoPP      | High-performance genomic analysis framework with in-memory computing                                                                                         | Short-Read Genome Analysis | ICT, CAS |
| 2018 | SC         | Extreme scale de novo metagenome assembly                                                                                                                    | De Novo Assembly | Intel |
| 2018 | SC         | Optimizing high-performance distributed memory parallel hash tables for DNA k-mer counting                                                                   | K-mer Counting | Georgia Tech |
||||<br>
| 2020 | SC         | Distributed many-to-many protein sequence alignment using sparse matrices                                                                                    | Protein Sequence Alignment | Lawrence Berkeley National Laboratory |
| 2020 | SC         | SegAlign: a scalable GPU-based whole genome aligner                                                                                                          | Whole Genome Alignment | Stanford |
||||<br>
| 2021 | PPoPP      | Asynchrony versus bulk-synchrony for a generalized N-body problem from genomics                                                                              | N-body Problem | UCB |
| 2021 | SC         | Accelerating large scale de novo metagenome assembly using GPUs                                                                                              | De Novo Assembly | Lawrence Berkeley National Laboratory |
| 2021 | SC         | FastZ: accelerating gapped whole genome alignment on GPUs                                                                                                    | Whole Genome Alignment | Purdue University |
| 2021 | SC         | High-throughput virtual screening of small molecule inhibitors for SARS-CoV-2 protein targets with deep fusion models                                        | Proteinligand Binding Affinity Prediction | Lawrence Livermore National Laboratory |
||||<br>
| 2022 | SC         | Extreme-Scale Many-Against-Many Protein Similarity Search                                                                                                    | Protein Search | Lawrence Berkeley National Laboratory |
||||<br>
| 2023 | PPoPP      | High-Performance and Scalable Agent-Based Simulation with BioDynaMo                                                                                          | Agent-based modeling | ETHZ |
| 2023 | SC         | Space Efficient Sequence Alignment for SRAM-Based Computing: X-Drop on the Graphcore IPU                                                                     | Extension Phase, Read Alignment | Simula Research Laboratory |
||||<br>
| 2024 | PPoPP      | AGAThA: Fast and Efficient GPU Acceleration of Guided Sequence Alignment for Long Read Mapping                                                               | Extension Phase, Read Alignment | Seoul National University |
| 2024 | PPoPP      | FastFold: Optimizing AlphaFold Training and Inference on GPU Clusters                                                                                        | Protein Structure Prediction | National University of Singapore |
| 2024 | SC         | Rapid GPU-Based Pangenome Graph Layout                                                                                                                       | Pangeonme Graph Layout | Cornell University |

## Software
Genome analysis baseline software at top-tier journals and conferences (e.g., Bioinformatics, NeurIPS, etc).

**Short-Read Genome Analysis**

| Year | Journal         | Paper                                                                                                                                                        | Keywords | Affiliation | 
| :--: | :--------: | :----------------------------------------------------------------------------------------------------------------------------------------------------------: | :--: | :--: |
| 2010 | arXiv           | Aligning sequence reads, clone sequences and assembly contigs with BWA-MEM                                                                                   | Read Alignment | Broad Institute | 
| 2010 | Genome Research | The Genome Analysis Toolkit: A MapReduce framework for analyzing next-generation DNA sequencing data                                                         | End-to-End Pipeline | Broad Institute | 
||||<br>
| 2022 | Bioinformatics  | BWA-MEME: BWA-MEM emulated with a machine learning approach                                                                                                  | Read Alignment, Learned Index | KAIST  |
| 2018 | Nature Biotechnology | A universal SNP and small-indel variant caller using deep neural networks                                                                               | Variant Calling | Google LLC |

**Long-Read Genome Analysis**

| Year | Journal         | Paper                                                                                                                                                        | Keywords | Affiliation | 
| :--: | :--------: | :----------------------------------------------------------------------------------------------------------------------------------------------------------: | :--: | :--: |
| 2021 | Genome Biology  | SquiggleNet: real-time, direct classification of nanopore signals                                                                                            | Targeted Sequencing | UofM |
| 2020 | BIBM            | An End-to-end Oxford Nanopore Basecaller Using Convolution-augmented Transformer                                                                             | Base-calling | NUDT |
| 2018 | Bioinformatics  | Minimap2: pairwise alignment for nucleotide sequences                                                                                                        | Read Alignment | Broad Institute | 
| 2016 | Bioinformatics  | Minimap and miniasm: fast mapping and de novo assembly for noisy long sequences                                                                              | Assembly | Broad Institute | 
| 2017 | Genome Research | Fast and accurate de novo genome assembly from long uncorrected reads                                                                                        | Polishing | University of Zagreb |
||||<br>
| 2022 | Nature Biotechnology | DeepConsensus improves the accuracy of sequences with a gap-aware sequence transformer                                                                  | Polishing | Google LLC | 
| 2022 | Nature Computational Science | Accelerating minimap2 for long-read sequencing applications on modern CPUs                                                                      | Long-Read Alignment | Intell Lab |
| 2023 | Scientific Reports | Efficient end-to-end long-read sequence mapping using minimap2-fpga integrated with hardware accelerated chaining                                         | Long-Read Alignment | University of New South Wales |
| 2025 | Bioinformatics  | Embed-Search-Align: DNA sequence alignment using Transformer models                                                                                          | Transformer, Nanopore Sequencing | UCLA |


## Future System
Future genome analysis systems at top-tier journals (e.g., Nature, Science, etc).

| Year | Journal         | Paper                                                                                                                                                        | Keywords | Affiliation | 
| :--: | :--------: | :----------------------------------------------------------------------------------------------------------------------------------------------------------: | :--: | :--: |
| 2021 | Nature Materials  | Random access DNA memory using Boolean search in an archival file storage system                                                                             | DNA Storage | MIT |
| 2023 | Nature            | DNA-based programmable gate arrays for general-purpose DNA computing                                                                                         | DNA Computing | SJTU |
| 2024 | Nature            | Parallel molecular data storage by printing epigenetic bits on DNA                                                                                           | DNA Storage | PKU |


# Contribute
This is an active repository, and your contributions are always welcome! Do not hesitate to create pull requests.
