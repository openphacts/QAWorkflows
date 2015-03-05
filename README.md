# QAWorkflows
Workflows for the testing the data and filters from the Open PHACTS API

Target comparison(2):
	- Target information:
	Compares Target Information from 1.4 with Develop. Needs a list of uniprot accession numbers and writes a csv file with the merged result of selected colums. 
	TODO: Target Information batch calls. 

	- Target pharmacology:
	Compares Target Pharmacology Counts from 1.4, Develop and the Chembl knime nodes. Starts with the list of Targets in Chembl 20 (taken from ftp://ftp.ebi.ac.uk/pub/databases/chembl/ChEMBLdb/releases/chembl_20/chembl_uniprot_mapping.txt). 
	TODO: Compare content of Target Pharmacology calls, add filters. 

	- EC classification:
	Retrieves all proteins classified with the given EC code from Develop (1.4 can be joined in as well). The output file can be used to compare if all targets for a given class are returned (currently only data for EC1 available). 
	TODO: add filters. Add checking for the classification of a given protein. 

	- Chembl classification: 
	Retrieves all proteins classified with the given Chembl class from Develop. 
	TODO: needs testset to compare against. 

	TODO:
	- GO classification
	- Classifications of compounds for Target
	- Target class pharmacology with filters

