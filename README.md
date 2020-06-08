# amplibase
A docker image with tools installed for amplicon sequence analysis

This docker image contains the basic tools for amplicon sequence analysis and visulazition

   - Cutadapt (1.15-1)
   - VSEARCH (2.13.1)
   - NCBI-blast+ (2.6.0-1)
   - Bioperl (1.7.2-2)
   - MAFFT (7.310-1)
   - Fasttree (2.1.10-1)
   - R , with libraries: *
      * phyloseq (1.32.0) 
      * ggplot2 (3.3.0) 
      * plotly (4.9.0) 
      * RColorBrewer (1.1.2) 
      * plyr (1.8.6) 
      * dplyr (0.8.5) 
      * vegan (2.5.6)


# Building amplibase image
`
sudo docker build --rm -t "amplibase" -f amplibase .
`

# Pulling image from Docker hub
`docker pull abhijeetsingh1704/amplibase`
