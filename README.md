# EllipsePlot
# Language: R
# Input: TXT
# Output: PREFIX
# Tested with: PluMA 1.1, R 4.0.0
# Dependency: microbiome_1.12.0, phyloseq_1.34.0, data.table_1.14.0, ggplot2_3.3.3

PluMA plugin to produce a two-dimensional plot of multiple datasets,
with a confidence ellipse for each set.

The plugin accepts as input a TXT file of filenames (one filename per line).
Each filename is assumed to be a dataset, that contains tab-delimited (x,y) points, 
one per line

The plugin will generate two files:
PREFIX.csv: data to be plotted
PREFIX.pdf: The actual plot
