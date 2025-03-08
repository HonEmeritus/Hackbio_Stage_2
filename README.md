# Hackbio_Stage_2
Coding for Life Scientists
Three sections:

SECTION 1:
Calculate the difference in metabolic response (ΔM) between the DMSO treatment from the 24 hours treatment for the wild type and mutants
Generate a scatter plot showing the difference for ΔM for WT and Mutants
Fit a line that satifies a y-intercept of 0 and a slope of 1.
Using a residual cut off of your choice (calculated a the difference between the fitted line and each point) calculate the residual of each point on the scatter plot
Color metabolites that fall within +/- n of your residual grey. For example, if you have a cut-off of 0.3, color residual values that are within -0.3 and +0.3 grey
Color metabolites that fall outside this range salmon.
What are these metabolites. How do you explain the trends you see on either direction of the plot?
Pick any 6 metabolites that fall outside this range and generate a line plot that spans from their 0h treatment to their 8h and 24hr.

SECTION 2:
Transcriptomics
Codes will:
Generate a volcano plot. (Hint search for volcano plot online)
Determine the upregulated genes (Genes with Log2FC > 1 and pvalue < 0.01)
Determine the downregulated genes (Genes with Log2FC < -1 and pvalue < 0.01)

SECTION 3:
Microbiology 
codes will:
Plot all the growth curves of OD600 vs Time for the different Strains with the following instructions
For each strain, plot a growth curve of the the knock out (-) an knock in (+) strain overlaid on top of each other
Using your function from last stage, determine the time to reach the carrying capacity for each strain/mutant
Generate a scatter plot of the time it takes to reach carrying capacity for the knock out and the knock in strains
Generate a box plot of the time it takes to reach carrying capacity for the knock out and the knock in strains
Confirm if there a statistical difference in the time it takes the knock out strains to reach their maximum carrying capacity compared to the knock in strains
