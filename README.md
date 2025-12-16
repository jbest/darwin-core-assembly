# darwin-core-assembly
A Jupyter notebook to read, filter, and reconstruct Darwin Core Archives

From notebook documentation:
Assemble a new Darwin Core Archive using data from another archive

This is based on a DwC-A exported from Symbiota

The process only uses the occurrences.csv and images.csv file for filtering

and creates a copy of the original meta.xml file.

All other files are ignored.

Intended for upload to BioSpex

Extract a DwC Archive file and put the contents in a directory named dwc_source in same path as this notebook

Create a directory called dwc_out to store output

To create the new DwC archive file, ZIP the contents of dwc_out (not the directory itself)
