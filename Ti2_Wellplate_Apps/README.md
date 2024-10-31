# Wellplate applications on Ti2 microscope

> [!IMPORTANT]
> All the information below is related to **NIS-Elements version 6.10.01 + Patch 01** or newer.

## Sample Navigation features

| Feature                                                  | Hw requirements                                         | Minimal setup type                                                               |
| -------------------------------------------------------- | ------------------------------------------------------- | -------------------------------------------------------------------------------- |
| Automatic Wellplate type detection only                  | No special requirements                                 | ["Preview/Overview Objective + Z-Reference"](system_setup_overview_objective.md) |
| Automatic Wellplate type detection + *Overview functions | **Special condenser rings **at least for 4x objective** | ["Preview/Overview Objective + Z-Reference"](system_setup_overview_objective.md) |
| Full set of functions                                    | **Special condenser rings for all objectives            | ["Full"](system_setup_full.md)                                                   |

*Overview functions:
- Cell presence detection (CellPresence.ai), it is used for finding a place where to start the first Autofocus as well as for marking wells by "Cells present" label
- AI based Fast Autofocus (Cells.ai)

**Special condenser rings:
- [ELWD condenser](LW_AS_ELWD.md)
- [LWD condenser](LW_AS_LWD.md)

## Sample Navigation setups

There are three different setup types depending on the special condenser rings and used samples.

#### 1. I have a set of the special condenser rings for ELWD ([LW_AS_ELWD](LW_AS_ELWD.md)) or LWD ([LW_AS_LWD](LW_AS_LWD.md)) condenser and I am using wellplates with [one of the trained cell lines](#ai-functions-has-been-trained-for-these-cell-lines)
   - [Use **"Full" setup**](system_setup_full.md), it provides full functionality for Wellplate application, see the functions above.
         
#### 2. I **do not have** the full set of the special condenser rings, but I have just the rings for 4x objective which is used for plate detection and scanning overview     
   - [Use **"Preview/Overview Objective + Z-Reference" setup**](system_setup_overview_objective.md), a setup where Wellplate type detection works, but scanning Overview can fail due to Cells.ai or CellPresence.ai do not work correctly.  
  
#### 3. I do not have any special condenser ring
   - [Use **"Preview/Overview Objective + Z-Reference" setup**](system_setup_overview_objective.md), a setup where Wellplate type detection works for the most of wellplates, but scanning Overview can fail due to Cells.ai or CellPresence.ai do not work correctly.  
   - Use **"Z-Reference Only setup"** in case you are not able to set the system correctly even for wellplate type detection - 4x objective closed condenser ring or manual Aperture Stop setting. In case of this setup the Well Plate tab will not be present in ["Sample Navigation Control Panel usage"](sample_navigation.md).


### AI functions has been trained for these cell lines:  

> A431  
> BSC-1  
> CHOK1  
> Cos7  
> HeLa  
> HepG2  
> HT29  
> J774.1  
> Neuro2a  
> iPSC derived Neurons

<!--
# Other documents

A. [Sample Navigation Control Panel usage.](sample_navigation.md)

B. [How to use the built-in functions in your custom Jobs.](jobtasks_usage.md)

Sigi tu byl!

-->