# project1
it process the current variable as "file"
The workflow begins by taking user-defined input for chromosome selection from "standard_selection.tsv."

The rule all provides the final output file is named "file_filtered_sorted.bed."

Filtering and Merging
The filtering rule merges two BED files, "shuf.a.bed" and "shuf.b.bed," based on the specified chromosome selection.

Sorting and Organizing
The sorting rule utilizes an AWK command to organize the filtered data according to the specified chromosome order.

project3_vplot
it uses pandas to read the file alot name of each variable of each column #calculation- it takes center of 3rd and 4th and substract is center from initial and final point to obtain relative length.

it uses length and center of 10th and 11th line as output.
for same point repeating , calculate the frequency of repeating point gnuplot
use the matrix to obtain the grapth , by using mid point , length , and frequency.
