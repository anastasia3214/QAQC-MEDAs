# QAQC-MEDAs
This repository contains a Python/Jupyter Notebook script for performing Quality Assurance (QA) and Quality Control (QC) procedures on meteo-oceanographic datasets collected by two elastic beacons deployed in Bacoli and the Gulf of Naples, in the Southern Tyrrhenian Sea.\n
The datasets were acquired using Meteorological stations MaxiMet Gill Instrumentation; the SEACAT Profiler CTD SBE 19plus V2; the MicroCAT C-T-(P)-ODO Recorder (Serial Interface, Memory, Integral Pump) SBE 37-SMP-ODO; and the WorkHorse Sentinel ADCP.\n
\n
The procedure consists of the following steps:\n
1 - Uniformated datetime\n 
2 - Identification of faulty values\n
3 - Duplicate test (research on rows and columns)\n
4 - Frozen profiles test\n
5 - Range test\n
6 - Spike test\n
7 - Adding missing values\n
The datasets are saved in Excel format.\n
\n
\n
Requirements\n
\n
pandas version 2.3.2\n
datetime version 3.11.13\n
numpy version 1.26.4\n
matplotlib version 3.10.6\n
seaborn version 0.13.2\n
glob version 3.11.13\n
re version 2.2.1\n
os version 3.11.13\n
defaultdict version 3.11.13\n
scipy version 1.16.1\n
math version 3.11.13
Path version 3.11.13
