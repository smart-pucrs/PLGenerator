===================================================================================================
Plan Library Generator (PLGenerator) -- Dataset
Version 1.0
===================================================================================================

# DESCRIPTION
---------------------------------------------------------------------------------------------------
 This directory contains the data generated for the paper
 “Evaluating the SBR Algorithm using Automatically Generated Plan Libraries”.
 by Giovani Farias et al.

 This extensive dataset was created using the PLGenerator (Plan Library Generator) with a varied
 number of parameters. The XML files represent the several plan libraries created based on these
 parameters and their names reflect the parameters values used in the PLGenerator. For example: 

 PL_TP10_D3_B1_3_F10_C2_FN1_SE0.0_DUP0.0.xml 

 represents a plan library 'PL_' generated with
 
 'TP10'   number of top-level plans (goals) = 10

 'D3'     depth = 3

 'B1_3'   minimum number of branches = 1 and maximum number of branches = 3

 'F10'    number of features = 10

 'C2'     feature status = 2

 'FN1'    features per node = 1

 'SE0.0'  sequential edges = 0

 'DUP0.0' duplication = 0

 To generate a plan library with the parameters above you must use the following commands

 java -jar PLGenerator.jar -g 10 -d 3 -b 1 -B 3 -F 10 -c 2 -f 2 -s 0 -D 0 -p output.xml
 
 or
 
 java -jar PLGenerator.jar -A 10 3 1 3 2 2 10 0 0 1 1 output.xml	


** NOTE: These plan libraries don't present minimum and maximum number of times that an 
observation of a plan node must be repeated because an older version of the PLGenerator was used 
to create these Dataset.
 
---------------------------------------------------------------------------------------------------

# REFERENCE
---------------------------------------------------------------------------------------------------
 For any reference to this generator or dataset please use:

 Giovani Farias et al.
 “Automatic Generation of Plan Libraries for Plan Recognition Performance Evaluation”.
 In: IEEE/WIC/ACM International Conference on Web Intelligence and Intelligent Agent Technology,
 WI-IAT 2015, Singapore, December 6-9, 2015 - Volume II. 2015, pp. 129–132.
 doi: 10.1109/WI- IAT.2015.55. url: http://dx.doi.org/10.1109/WI-IAT.2015.55.

 Giovani Farias et al.
 “Evaluating the SBR Algorithm using Automatically Generated Plan Libraries”.
 In: 5th Brazilian Conference on Intelligent System (BRACIS-16). Recife, Pernambuco, Brazil, 2016.
---------------------------------------------------------------------------------------------------

# CONTACT
---------------------------------------------------------------------------------------------------
 If you have any questions or suggestions please contact giovanifarias@gmail.com


