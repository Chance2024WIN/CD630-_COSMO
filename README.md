2.	Define each  parameter running Cosmo with clostridium diffcile and RNA seq data 
1) minimum CDS coverage =  1
2) min IGR coverage = 2
3) maximum FD between adjacent CDSs/genes = 5.0
4) max FD between IGR and flanking CDSs = 10.0
5) output file name given by user = Wildtype_control.csv 
6) Genome name in GTF file = NC_009089
7) Size of genome in GTF file = 4290252
8) Input bam file = Wildtype_1_control.bam 
9) GTF file name = NC_009089.1.gtf
Next Step: Run COSMO on Your Clostridium difficile Data
Script : python user_input.py -D 1 -d 2 -F 5.0 -f 10.0 -o Wildtype_1_control.csv NC_009089.1 4290252 Wildtype_1_control_fixed.bam NC_009089.1.gtf
