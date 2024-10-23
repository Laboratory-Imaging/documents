# Wellplate applications in NIS-Elements software

## There are three different setup types depending on the special condenser rings and used samples.

1. I have a set of the special condenser rings for ELWD ([LW_AS_ELWD](LW_AS_ELWD.md)) or LWD ([LW_AS_LWD](LW_AS_LWD.md)) condenser and I am using wellplates with [one of the trained cell lines](#ai-functions-has-been-trained-for-these-cell-lines)
   - [Use **"Full" setup**](system_setup_full.md)  
         
2. I **do not have** the full set of the special condenser rings, but I have just the rings for 4x objective which is used for plate detection and scanning overview     
   - [Use **"Preview/Overview Objective + Z-Reference" setup**, a setup where Wellplate type detection works, but scanning Overview can fail due to Cells.ai or CellPresence.ai do not work correctly.](system_setup_overview_objective.md)  
  
3. I do not have any special condenser ring
   - [Use **"Preview/Overview Objective + Z-Reference" setup**, a setup where Wellplate type detection can work only with a precise brightness setting and scanning Overview can fail due to Cells.ai or CellPresence.ai do not work correctly.](system_setup_overview_objective.md)  
   - Use **"Z-Reference Only setup"** in case you are not able to set the system correctly even for wellplate type detection - 4x objective closed condenser ring or manual Aperture Stop setting. In case of this setup the Well Plate tab will not be present in ["Sample Navigation Control Panel usage"](sample_navigation.md).


## AI functions has been trained for these cell lines:  
- A431
- BSC-1
- CHOK1
- Cos7
- HeLa
- HepG2
- HT29
- J774.1
- Neuro2a
- iPSC derived Neurons

<!--
# Other documents

A. [Sample Navigation Control Panel usage.](sample_navigation.md)

B. [How to use the built-in functions in your custom Jobs.](jobtasks_usage.md)
-->