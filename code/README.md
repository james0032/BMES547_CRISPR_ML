Code
-----

This directory should contain the processing scripts required to convert the raw information into 
a set of processed data files that are then visualized. Code in this directory MUST HAVE UNIT-TESTS! 
Any code which is gernalizable to multiple projects should be re-factored out and placed in the global src/tools
directory. Processing should be designed such that a single command runs all analysis without human input. Parameters should
be saved as yaml files and imported by the script.

Notes to place in this file:
  - How to run the analysis.
  - The function of each script.
  - Note anytime functions have been re-factored into the main tool repository.
  
---------------------