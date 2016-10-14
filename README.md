# The Problem
We extract a large volume of pathology reports from GP patient management systems, that each use different formatting standards (or none!). Translating between any given pathology report from one of ~20 (!) different laboratories, needless to say, introduces various inconsistencies.

We need to pull out relevant information from the pathology reports in a standardized manner - everything from disease name, assay type to the result (frequently multiple in the one record) - in order to perform productive and meaningful analyses on it.

# Solution
The solution should parse the raw text into four to five variables indicating disease, assay, test result, specimen type and specimen site. We are quite comfortable with a command line style utility.

We anticipate that the solution may need to take advantage of a reasonable amount of computing power.

Some exploration of disease ontologies may be useful in order to improve the accuracy of the system.

Our current system is written in the statistical package STATA - however, we are open to other systems, particularly Python or R.
