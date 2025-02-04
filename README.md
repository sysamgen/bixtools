# D3B Docker Image Build Instruction Hub

This repo contains build instructions that we use at the Center for Data-Driven Discovery in Biomedicine (D3B) and in the Kids First Data Resource Center (KFDRC). The most updated production images are stored in the [SBG docker registry](https://cavatica.sbgenomics.com/developer/docker). This requires a Cavatica login and individual images may require separate permission to access.

Legacy versions of some images are stored in the [KFDRC Dockerhub](https://hub.docker.com/u/kfdrc/). The images on Dockerhub are deprecated and will not be updated.

# Current Dockers
Below is a list of the current docker images the command to pull them.

image | version | pull command
------- | ------ | ------------
BIC-seq2 | 0.7.2 | docker pull pgc-images.sbgenomics.com/d3b-bixu/BIC-seq2:0.7.2
FusionCatcher | latest | docker pull pgc-images.sbgenomics.com/d3b-bixu/FusionCatcher:latest
LinkedSV | latest | docker pull pgc-images.sbgenomics.com/d3b-bixu/LinkedSV:latest
SVTyper | 0.7.1 | docker pull pgc-images.sbgenomics.com/d3b-bixu/SVTyper:0.7.1
THetA2 | 0.7.0 | docker pull pgc-images.sbgenomics.com/d3b-bixu/THetA2:0.7.0
THetA2 | 0.7.1 | docker pull pgc-images.sbgenomics.com/d3b-bixu/THetA2:0.7.1
VEP | r93.7 | docker pull pgc-images.sbgenomics.com/d3b-bixu/VEP:r93.7
VEP | r93 | docker pull pgc-images.sbgenomics.com/d3b-bixu/VEP:r93
VEP | r93_v2 | docker pull pgc-images.sbgenomics.com/d3b-bixu/VEP:r93_v2
VEP | r94 | docker pull pgc-images.sbgenomics.com/d3b-bixu/VEP:r94
VEP | r98 | docker pull pgc-images.sbgenomics.com/d3b-bixu/VEP:r98
VarDictJava | 1.5.8 | docker pull pgc-images.sbgenomics.com/d3b-bixu/VarDictJava:1.5.8
VarDictJava | fp_filter | docker pull pgc-images.sbgenomics.com/d3b-bixu/VarDictJava:fp_filter
add-strelka2-fields | 1.0.0 | docker pull pgc-images.sbgenomics.com/d3b-bixu/add-strelka2-fields:1.0.0
annoFuse | 0.1.8 | docker pull pgc-images.sbgenomics.com/d3b-bixu/annoFuse:0.1.8
annoFuse | 0.90.0 | docker pull pgc-images.sbgenomics.com/d3b-bixu/annoFuse:0.90.0
annovar | latest | docker pull pgc-images.sbgenomics.com/d3b-bixu/annovar:latest
arriba | 1.0.1 | docker pull pgc-images.sbgenomics.com/d3b-bixu/arriba:1.0.1
arriba | 1.1.0 | docker pull pgc-images.sbgenomics.com/d3b-bixu/arriba:1.1.0
arriba | latest | docker pull pgc-images.sbgenomics.com/d3b-bixu/arriba:latest
bcbio | variation_recall-0.2.4 | docker pull pgc-images.sbgenomics.com/d3b-bixu/bcbio:variation_recall-0.2.4
bed_tools | bedopsv2.4.36_plus_bedtools | docker pull pgc-images.sbgenomics.com/d3b-bixu/bed_tools:bedopsv2.4.36_plus_bedtools
bwa-bundle | 0.1.17 | docker pull pgc-images.sbgenomics.com/d3b-bixu/bwa-bundle:0.1.17
bwa-picard | broad | docker pull pgc-images.sbgenomics.com/d3b-bixu/bwa-picard:broad
bwa-picard | latest | docker pull pgc-images.sbgenomics.com/d3b-bixu/bwa-picard:latest
bwa | 0.7.15-r1140 | docker pull pgc-images.sbgenomics.com/d3b-bixu/bwa:0.7.15-r1140
bwa | 0.7.17-r1188 | docker pull pgc-images.sbgenomics.com/d3b-bixu/bwa:0.7.17-r1188
bwa | latest | docker pull pgc-images.sbgenomics.com/d3b-bixu/bwa:latest
canvas | 1.11.0 | docker pull pgc-images.sbgenomics.com/d3b-bixu/canvas:1.11.0
cellranger | 3.1 | docker pull pgc-images.sbgenomics.com/d3b-bixu/cellranger:3.1
cellranger | 5.0 | docker pull pgc-images.sbgenomics.com/d3b-bixu/cellranger:5.0
cellranger | 6.0 | docker pull pgc-images.sbgenomics.com/d3b-bixu/cellranger:6.0
cnvnator | v0.4.1 | docker pull pgc-images.sbgenomics.com/d3b-bixu/cnvnator:v0.4.1
codex2 | 3.8 | docker pull pgc-images.sbgenomics.com/d3b-bixu/codex2:3.8
consensus-merge | 1.0.0 | docker pull pgc-images.sbgenomics.com/d3b-bixu/consensus-merge:1.0.0
consensus-merge | 1.1.0 | docker pull pgc-images.sbgenomics.com/d3b-bixu/consensus-merge:1.1.0
controlfreec | 11.5 | docker pull pgc-images.sbgenomics.com/d3b-bixu/controlfreec:11.5
cutadapt | latest | docker pull pgc-images.sbgenomics.com/d3b-bixu/cutadapt:latest
fastqc | v0.11.9 | docker pull pgc-images.sbgenomics.com/d3b-bixu/fastqc:v0.11.9
freebayes | v1.3.1 | docker pull pgc-images.sbgenomics.com/d3b-bixu/freebayes:v1.3.1
freebayes | v1.3.2 | docker pull pgc-images.sbgenomics.com/d3b-bixu/freebayes:v1.3.2
gatk-picard | 4.0.1.2-2.8.3 | docker pull pgc-images.sbgenomics.com/d3b-bixu/gatk-picard:4.0.1.2-2.8.3
gatk-picard | 4.beta.1-2.8.3 | docker pull pgc-images.sbgenomics.com/d3b-bixu/gatk-picard:4.beta.1-2.8.3
gatk | 3.5-0-g36282e4 | docker pull pgc-images.sbgenomics.com/d3b-bixu/gatk:3.5-0-g36282e4
gatk | 3.6-0-g89b7209 | docker pull pgc-images.sbgenomics.com/d3b-bixu/gatk:3.6-0-g89b7209
gatk | 3.8 | docker pull pgc-images.sbgenomics.com/d3b-bixu/gatk:3.8
gatk | 3.8_ubuntu | docker pull pgc-images.sbgenomics.com/d3b-bixu/gatk:3.8_ubuntu
gatk | 4.0.1.0 | docker pull pgc-images.sbgenomics.com/d3b-bixu/gatk:4.0.1.0
gatk | 4.0.1.2 | docker pull pgc-images.sbgenomics.com/d3b-bixu/gatk:4.0.1.2
gatk | 4.0.12.0 | docker pull pgc-images.sbgenomics.com/d3b-bixu/gatk:4.0.12.0
gatk | 4.0.5.2 | docker pull pgc-images.sbgenomics.com/d3b-bixu/gatk:4.0.5.2
gatk | 4.1.1.0 | docker pull pgc-images.sbgenomics.com/d3b-bixu/gatk:4.1.1.0
gatk | 4.1.7.0R | docker pull pgc-images.sbgenomics.com/d3b-bixu/gatk:4.1.7.0R
gatk | 4.2.0.0R | docker pull pgc-images.sbgenomics.com/d3b-bixu/gatk:4.2.0.0R
gatk | 4.beta.1-3.5 | docker pull pgc-images.sbgenomics.com/d3b-bixu/gatk:4.beta.1-3.5
gatk | 4.beta.1 | docker pull pgc-images.sbgenomics.com/d3b-bixu/gatk:4.beta.1
gatk | 4.beta.5-tabix | docker pull pgc-images.sbgenomics.com/d3b-bixu/gatk:4.beta.5-tabix
gatk | 4.beta.5 | docker pull pgc-images.sbgenomics.com/d3b-bixu/gatk:4.beta.5
gatk | 4.beta.6-tabix | docker pull pgc-images.sbgenomics.com/d3b-bixu/gatk:4.beta.6-tabix
gatk | 4.beta.6 | docker pull pgc-images.sbgenomics.com/d3b-bixu/gatk:4.beta.6
gatk | latest | docker pull pgc-images.sbgenomics.com/d3b-bixu/gatk:latest
hotspots | 0.1.0 | docker pull pgc-images.sbgenomics.com/d3b-bixu/hotspots:0.1.0
kf_vcf2maf | v1.0.0 | docker pull pgc-images.sbgenomics.com/d3b-bixu/kf_vcf2maf:v1.0.0
kf_vcf2maf | v1.0.1 | docker pull pgc-images.sbgenomics.com/d3b-bixu/kf_vcf2maf:v1.0.1
kf_vcf2maf | v1.0.2 | docker pull pgc-images.sbgenomics.com/d3b-bixu/kf_vcf2maf:v1.0.2
kf_vcf2maf | v1.0.3 | docker pull pgc-images.sbgenomics.com/d3b-bixu/kf_vcf2maf:v1.0.3
lancet | 1.0.7 | docker pull pgc-images.sbgenomics.com/d3b-bixu/lancet:1.0.7
loompy | 2.0.16 | docker pull pgc-images.sbgenomics.com/d3b-bixu/loompy:2.0.16
lumpy-sv | 0.2.13 | docker pull pgc-images.sbgenomics.com/d3b-bixu/lumpy-sv:0.2.13
lumpy-sv | 0.3.0 | docker pull pgc-images.sbgenomics.com/d3b-bixu/lumpy-sv:0.3.0
manta | 1.4 | docker pull pgc-images.sbgenomics.com/d3b-bixu/manta:1.4
manta | 1.6.0 | docker pull pgc-images.sbgenomics.com/d3b-bixu/manta:1.6.0
peddy | v0.4.2 | docker pull pgc-images.sbgenomics.com/d3b-bixu/peddy:v0.4.2
peddy | v0.4.7 | docker pull pgc-images.sbgenomics.com/d3b-bixu/peddy:v0.4.7
picard-r | picard2.15.0-r.3.3.3 | docker pull pgc-images.sbgenomics.com/d3b-bixu/picard-r:picard2.15.0-r.3.3.3
picard-r | picard2.8.3-r3.3.3 | docker pull pgc-images.sbgenomics.com/d3b-bixu/picard-r:picard2.8.3-r3.3.3
picard | 2.14.0 | docker pull pgc-images.sbgenomics.com/d3b-bixu/picard:2.14.0
picard | 2.15.0 | docker pull pgc-images.sbgenomics.com/d3b-bixu/picard:2.15.0
picard | 2.17.4 | docker pull pgc-images.sbgenomics.com/d3b-bixu/picard:2.17.4
picard | 2.18.9 | docker pull pgc-images.sbgenomics.com/d3b-bixu/picard:2.18.9
picard | 2.18.9R | docker pull pgc-images.sbgenomics.com/d3b-bixu/picard:2.18.9R
picard | 2.8.3 | docker pull pgc-images.sbgenomics.com/d3b-bixu/picard:2.8.3
picard | latest | docker pull pgc-images.sbgenomics.com/d3b-bixu/picard:latest
pizzly | latest | docker pull pgc-images.sbgenomics.com/d3b-bixu/pizzly:latest
python | 2.7.13 | docker pull pgc-images.sbgenomics.com/d3b-bixu/python:2.7.13
sambamba | 0.6.3 | docker pull pgc-images.sbgenomics.com/d3b-bixu/sambamba:0.6.3
sambamba | 0.7.1 | docker pull pgc-images.sbgenomics.com/d3b-bixu/sambamba:0.7.1
samtools | 1.3.1 | docker pull pgc-images.sbgenomics.com/d3b-bixu/samtools:1.3.1
samtools | 1.6 | docker pull pgc-images.sbgenomics.com/d3b-bixu/samtools:1.6
samtools | 1.7-11-g041220d | docker pull pgc-images.sbgenomics.com/d3b-bixu/samtools:1.7-11-g041220d
samtools | 1.9 | docker pull pgc-images.sbgenomics.com/d3b-bixu/samtools:1.9
samtools | latest | docker pull pgc-images.sbgenomics.com/d3b-bixu/samtools:latest
seurat | latest | docker pull pgc-images.sbgenomics.com/d3b-bixu/seurat:latest
smoove | 0.2.5 | docker pull pgc-images.sbgenomics.com/d3b-bixu/smoove:0.2.5
soupx_R | 4.1.0_SoupX | docker pull pgc-images.sbgenomics.com/d3b-bixu/soupx_R:4.1.0_SoupX
speedseq | latest | docker pull pgc-images.sbgenomics.com/d3b-bixu/speedseq:latest
star | 2.6.1d | docker pull pgc-images.sbgenomics.com/d3b-bixu/star:2.6.1d
star | 2.7.5a | docker pull pgc-images.sbgenomics.com/d3b-bixu/star:2.7.5a
star | fusion-1.5.0 | docker pull pgc-images.sbgenomics.com/d3b-bixu/star:fusion-1.5.0
strelka | v2.9.10 | docker pull pgc-images.sbgenomics.com/d3b-bixu/strelka:v2.9.10
sv2 | latest | docker pull pgc-images.sbgenomics.com/d3b-bixu/sv2:latest
svaba | 1.1.0 | docker pull pgc-images.sbgenomics.com/d3b-bixu/svaba:1.1.0
velocyto | 0.17.17 | docker pull pgc-images.sbgenomics.com/d3b-bixu/velocyto:0.17.17
verifybamid | 1.0.1 | docker pull pgc-images.sbgenomics.com/d3b-bixu/verifybamid:1.0.1
verifybamid | 1.0.2 | docker pull pgc-images.sbgenomics.com/d3b-bixu/verifybamid:1.0.2
verifybamid | latest | docker pull pgc-images.sbgenomics.com/d3b-bixu/verifybamid:latest
zumis | 2.9.4 | docker pull pgc-images.sbgenomics.com/d3b-bixu/zumis:2.9.4
