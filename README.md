## Consensus sequences for U.S. H5N1 clade 2.3.4.4b

### BioProjects

| BioProject | Description |
| --- | --- |
| **[PRJNA1102327](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA1102327)** | U.S. H5N1 clade 2.3.4.4b genotype B3.13 immediate releases related to emergence and spread in dairy cattle. |
| **[PRJNA1122849](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA1122849)** | U.S. H5N1 clade 2.3.4.4b immediate releases related to peridomestic animals. |
| **[PRJNA1134696](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA1134696)** | Viral sequencing of US dairy milk. |
| **[PRJNA1219588](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA1219588)** | U.S. H5N1 clade 2.3.4.4b genotype D1.1 immediate releases related to emergence in dairy cattle. |
| **[PRJNA1207547](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA1207547)** | U.S. Influenza A Surveillance in Wildlife. |
| **[PRJNA980729](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA980729)** | US HPAI Sequencing. |

This repository aims to provide consensus sequences, variant calls and depth information for the SRA data associated with BioProjects listed above. The repository checks for new data every 24 hours and updates the consensus sequences, variant calls and depth information accordingly. Additionally, the repository updates mapping of consensus genomes to the respective GenBank sequences by sample name every 24 hours.

All the data generated from **23rd May 2024** uses the genbank genome [A/cattle/Texas/24-008749-003/2024(H5N1)](https://www.ncbi.nlm.nih.gov/nuccore/?term=A/cattle/Texas/24-008749-003/2024) as a reference. The reference genome is stored in [./reference/](./reference). Minimum depth was set at 1, minimum quality at 20, and the consensus threshold at 50%.

> [!NOTE]
> Prior to **23rd May 2024** Consensus genomes for 8 segments were generated with `EPI_ISL_19032063` (source: GISAID) as a reference using [iVar v1.4.2](https://github.com/andersen-lab/ivar). Minimum depth was set at 1, minimum quality at 20, and the consensus threshold at 50%.

The consensus genomes are in [./fasta/](./fasta).

The SRA metadata is stored in [./metadata/SraRunTable_automated.csv](./metadata/SraRunTable_automated.csv)

The mapping of consensus genomes to the respective GenBank sequences by sample name is in [./metadata/genbank_mapping.tsv](./metadata/genbank_mapping.tsv)

The variant calls are in [./variants/](./variants).

The depth information is in [./depth/](./depth).

The pipeline used to generate the consensus genomes is in [gp201/flusra](https://github.com/gp201/flusra)

For NextStrain-style formatted version of the genomes and associated metadata,  please see [https://github.com/moncla-lab/avian-flu-USDA-cattle/](https://github.com/moncla-lab/avian-flu-USDA-cattle/).

### Data usage

We have shared this data with the hope that people will download and use it, as well as scrutinize it so we can improve the data quality. Please contact us if you have any questions or comments.

Please refer to the [NCBI usage policies]( https://www.ncbi.nlm.nih.gov/home/about/policies/) for more details.

---

We gratefully acknowledge the authors, originating and submitting laboratory of the sequences from GISAID's EpiFlu™ Database we used as references for our genome assemblies. The [list](./acknowledgements/gisaid_acknowledge_table_assemby_reference_sequences.xls) is provided in [./acknowledgements](./acknowledgements).
