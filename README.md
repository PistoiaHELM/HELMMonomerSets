# HELM Monomer Sets #


This repository contains the monomer sets and file format definition that the HELM project uses. 

The HELM project recommends that all HELM users adopt HELMCoreLibrary as the core of their monomer sets even if they then add monomers to their own copy. This will increase interoperability of HELM across organisations. 

The HELMCoreLibrary was developed by analyising public datasets with particular help from Evan Bolton of PubChem and Anna Gaulton and Patricia Bento of EMBL-EBI. 



### Schema ###

The recommended JSON schema is stored here. Please help us keep HELM as interoperable as possible by using this format in your tools. 

### Other Monomer Sets ###

Currently the HELM demo tools use the monomerLib2.0 library. This contains a limited number of monomers that were originally used internally by Pfizer. 

The Ionis set was used internally by Ionis and  is included since it contains a useful range of nucleotide monomers useful to users before the core monomer set was developed. 



All monomer sets are available as .json files. JSON is the recommended format. However, we recognise that a SQLlite db version and sd file may be useful, so have included them in the packs. 
