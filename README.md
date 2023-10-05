# Run3Jetvalidationframework

command to run the jet validation framework: **bash runtest.sh**

Please download your desired ESD data from the alimonitor page and put the data file in the same directory as the framework scripts. This is to ensure an easy execution of the full framework.
In any case, ensure the path to the data file in the **config_input.sh** is correctly specified.

The Run 3 task parameters are provided to the framework by the  Run 3 configuration json file. The updated json file in use by me (dpl-config-old.json) is provided here. 
One can easily obtain this json file by simply running the standalone jet validation QA task in O2Physics (PWGJE/Tasks/jetvalidationqa.cxx).


The corresponding jet validation QA task in AliPhysics can be found here: 
PWGJE/EMCALJetTasks/UserTasks/AliAnalysisTaskEmcalJetValidation.cxx
PWGJE/EMCALJetTasks/UserTasks/AliAnalysisTaskEmcalJetValidation.h

**NOTE**: In order to run the Jet O2 Validation Framework, make sure you have working builds of AliPhysics and O2Physics. 
