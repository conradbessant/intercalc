# intercalc
Tool for calculating possible background interference for a set of target peptides

intercalc.rb takes a list of target peptides in a particular TSV format and produces a new TSV file with an extra column containing the "interferent probability" for each peptide.

Two files are provided for testing: Target peptides in tagets.tsv Potential interfering peptides in background.tsv. The expected results obtained from these files are provided in correct_results.tsv.