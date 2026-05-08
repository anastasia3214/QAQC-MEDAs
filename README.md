# QAQC-MEDAs
This repository contains a Python/Jupyter Notebook script for performing Quality Assurance (QA) and Quality Control (QC) procedures on meteo-oceanographic datasets collected by two elastic beacons deployed in Bacoli and the Gulf of Naples, in the Southern Tyrrhenian Sea. 
The datasets were acquired using Meteorological stations MaxiMet Gill Instrumentation; the SEACAT Profiler CTD SBE 19plus V2; the MicroCAT C-T-(P)-ODO Recorder (Serial Interface, Memory, Integral Pump) SBE 37-SMP-ODO; and the WorkHorse Sentinel ADCP.

The procedure consists of the following steps:
1 - Uniformated datetime 
2 - Identification of faulty values
3 - Duplicate test (research on rows and columns)
4 - Frozen profiles test
5 - Range test
6 - Spike test
7 - Adding missing values
The datasets are saved in Excel format.


Requirements

pandas version 2.3.2
datetime version 3.11.13
numpy version 1.26.4
matplotlib version 3.10.6
seaborn version 0.13.2
glob version 3.11.13
re version 2.2.1
os version 3.11.13
defaultdict version 3.11.13
scipy version 1.16.1
math version 3.11.13
Path version 3.11.13
