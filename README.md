# Mixed-Signal Physical Design VSD

This repository documents my work during the VSD Mixed-Signal Physical Design internship track.

---

## Repository Structure

### Week 1 - Mixed-Signal Physical Design Fundamentals

| Section | Description |
|----------|-------------|
| [IEEE Report](./Week1_Task/Report/Week1_Task_Report.pdf) | Final IEEE-format report submitted for Week 1 |
| [LaTeX Source](./Week1_Task/Source/main.tex) | Source code of the report |
| [Screenshots](./Week1_Task/Screenshots/) | Layout and flow screenshots |

---

### Week 2 - AI-Assisted Mixed-Signal Flow Generation

| Section                                            | Description                                                                                   |
| -------------------------------------------------- | --------------------------------------------------------------------------------------------- |
| [Prompts](./Week2_Task/Prompts/)                   | AI-assisted repository analysis, macro studies, configuration studies and flow investigations |
| [Codex Prompts](./Week2_Task/Codex_Prompts/)       | Low-token Codex-ready prompts for reproducing each stage of the mixed-signal flow             |
| [Generated Files](./Week2_Task/Generated_Files/)   | AI-generated Verilog, configuration and support files                                         |
| [Commands](./Week2_Task/Commands/)                 | Tool commands, execution logs and flow runs                                                   |
| [Errors and Fixes](./Week2_Task/Errors_and_Fixes/) | Debugging history, issues encountered and fixes attempted                                     |
| [Screenshots](./Week2_Task/Screenshots/)           | Layout, floorplanning, routing and verification screenshots                                   |
| [Observations](./Week2_Task/Observations/)         | Technical findings, investigations and conclusions                                            |

#### Week 2 Progress Index

| Study                        | Link                                             				|
| ---------------------------- | ------------------------------------------------------------------------------ |
| Repository Analysis          | [01_Repo_Analysis](./Week2_Task/Prompts/01_Repo_Analysis.md)                	|
| Required Input Files         | [02_Required_Input_Files](./Week2_Task/Prompts/02_Required_Input_Files.md)  	|
| AMUX2_3V Macro Study         | [03_AMUX2_3V_Macro_Study](./Week2_Task/Prompts/03_AMUX2_3V_Macro_Study.md)  	|
| Macro File Inspection        | [04_Macro_File_Inspection](./Week2_Task/Prompts/04_Macro_File_Inspection.md)	|
| IO Placement Study           | [05_IO_Placement_Study](./Week2_Task/Prompts/05_IO_Placement_Study.md) 	|
| OpenLane Configuration Study | [06_OpenLane_Config_Study](./Week2_Task/Prompts/06_OpenLane_Config_Study.md)	|
| GDS Integration Study        | [07_GDS_Integration_Study](./Week2_Task/Prompts/07_GDS_Integration_Study.md)	|

#### Codex Prompt Library

| Prompt                                  	| Link                                                        		          				|
| --------------------------------------------- | ------------------------------------------------------------------------------------------------------------- |
| Codex Prompt 01 - Repository Analysis   	| [01_Repo_Analysis](./Week2_Task/Codex_Prompts/Codex_Prompt_01_Repo_Analysis.md) 				|
| Codex Prompt 02 - Analog Macro Analysis       | [02_Macro_Study](./Week2_Task/Codex_Prompts/Codex_Prompt_02_Macro_Study.md)     			   	|
| Codex Prompt 03 - OpenLane Config Generation  | [03_OpenLane_Config_Generation](./Week2_Task/Codex_Prompts/Codex_Prompt_03_OpenLane_Config_Generation.md)	|
| Codex Prompt 04 - PDN Hook Generation 	| [04_PDN_Hook_Generation](./Week2_Task/Codex_Prompts/Codex_Prompt_04_PDN_Hook_Generation.md) 	           	|
| Codex Prompt 05 - Macro Pin Access Debug 	| [05_Macro_Pin_Access_Debug](./Week2_Task/Codex_Prompts/Codex_Prompt_05_Macro_Pin_Access_Debug.md)		|
| Codex Prompt 06 - Power Connectivity Debug 	| [06_Power_Connectivity_Debug](./Week2_Task/Codex_Prompts/Codex_Prompt_06_Power_Connectivity_Debug.md) 	|

#### Error and Debug History

| Error 		   	| Link 													|
|-------------------------------|-------------------------------------------------------------------------------------------------------|
| Macro Pin Access Failure 	| [01_Macro_Pin_Access](./Week2_Task/Errors_and_Fixes/Error_01_Macro_Pin_Access.md)			|
| Power Connectivity Warnings 	| [02_Power_Connectivity](./Week2_Task/Errors_and_Fixes/Error_02_Power_Connectivity_Warnings.md) 	|

#### Command Logs

| Command Log 			    | Link 														|
|-----------------------------------|-------------------------------------------------------------------------------------------------------------------|
| Environment and Design Inspection | [01_Environment_and_Design_Inspection](./Week2_Task/Commands/Command_Log_01_Environment_and_Design_Inspection.md)	|
| GDS Integration Investigation     | [02_GDS_Investigation](./Week2_Task/Commands/Command_Log_02_GDS_Investigation.md) 				|

#### Observations

| Document 			| Link 														|
|-------------------------------|---------------------------------------------------------------------------------------------------------------|
| Week 2 Status Summary 	| [Week2_Status_Summary](./Week2_Task/Observations/Week2_Status_Summary.md)					|

---

### Week 3 - AI-Assisted Verification and Debugging

| Section | Description |
|----------|-------------|
| [Prompts](./Week3_Task/Prompts/) | Verification and debugging prompts |
| [Generated Files](./Week3_Task/Generated_Files/) | Additional generated files |
| [Commands](./Week3_Task/Commands/) | Verification commands |
| [Errors and Fixes](./Week3_Task/Errors_and_Fixes/) | Issues encountered and fixes |
| [Screenshots](./Week3_Task/Screenshots/) | Verification screenshots |
| [Observations](./Week3_Task/Observations/) | Final observations and comparison |

---

## Reference Repository

https://github.com/praharshapm/vsdmixedsignalflow

---

## Tools and Technologies

- SKY130 PDK
- OpenLane
- OpenROAD
- Magic
- KLayout
- Verilog
- LibreLane
- ChatGPT

---

## Author

**Chinmaya Sharma**

B.Tech Electronics and VLSI Engineering '28,  
IIIT Delhi
