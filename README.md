# make_annotation_tab
This automated script is designed specifically for creating an annotation table in tsv format following successfull completion of "filter_combine_reads". Please note, this is NOT "filter_combine_reads_v2". A second version of this script will be made for dealing with the differences that are detailed in "filter_combine_reads_v2". 

Input: 

"all_reads_info.tsv", output file from "filter_combine_reads"

Output:

"annotation_tab.tsv" = an annotation table for mapping to a phylogenetic tree.

Description:

Column headers are assigned, new column is created which contains the label (genus_species) and strain name for each instance, and "name" column is edited ("gi_" prefix is removed as for consistency with naming on newick string) 
