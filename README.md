# FNAL AI HEP Full Proposal

Modified from ECA templates: 

https://github.com/kpedro88/FNAL_ECA_Preproposal_Template 

https://github.com/kpedro88/FNAL_ECA_Proposal_Template

This repository facilitates the combination of user content with the requirements from the FOA for this specific call.

The call requires two separate files: one for the abstract and one for the main narrative with several attachments and appendices. You though must compile separately the `abstract-main.tex` and the `narrative-main.tex` to get each separate pdf. Each document has its own subfolder `narrative` and `abstract` where you must/can edit the following general files:

1. [content.tex](./content.tex): the actual proposal content
2. [packages.tex](./packages.tex): any additional packages used

Both documents access the main information `info.tex` file which you must edit with basics info (your name, email, proposal title, etc...)

For the main `narrative` you must also edit the following appendices:

1. [reference.bib](narrative/reference.bib): references
2. [facilities.tex](narrative/subsections/facilities.tex): facilities and other resources
3. [equipment.tex](narrative/subsections/equipment.tex): equipment
4. [dataplan.tex](narrative/subsections/dataplan.tex): data management plan
5. [resources.tex](narrative/subsections/resources.tex): computational resources
6. [recruitment.tex](narrative/subsections/recruitment.tex): recruitment and retention of students and early-stage investigators
10. [other.tex](narrative/subsections/other.tex): other attachments (e.g. letters of collaboration using the `\collabletter{}` command)

## Compilation

On overleaf just compile separately the two `narrative-main.tex` and `abstract-main.tex` documents.