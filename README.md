# QAQC-MEDAs
This repository contains a Python/Jupyter Notebook script for performing Quality Assurance (QA) and Quality Control (QC) procedures on meteo-oceanographic datasets collected by two elastic beacons deployed in Bacoli and the Gulf of Naples, in the Southern Tyrrhenian Sea.<br>
The datasets were acquired using Meteorological stations MaxiMet Gill Instrumentation; the SEACAT Profiler CTD SBE 19plus V2; the MicroCAT C-T-(P)-ODO Recorder (Serial Interface, Memory, Integral Pump) SBE 37-SMP-ODO; and the WorkHorse Sentinel ADCP.<br>
<br>
The procedure consists of the following steps:<br>
1 - Uniformated datetime<br>
2 - Identification of faulty values<br>
3 - Duplicate test (research on rows and columns)<br>
4 - Frozen profiles test<br>
5 - Range test<br>
6 - Spike test<br>
7 - Adding missing values<br>
The datasets are saved in Excel format.<br>
<br>
<br>
## Requirements:<br>
pandas version 2.3.2<br>
datetime version 3.11.13<br>
numpy version 1.26.4<br>
matplotlib version 3.10.6<br>
seaborn version 0.13.2<br>
glob version 3.11.13<br>
re version 2.2.1<br>
os version 3.11.13<br>
defaultdict version 3.11.13<br>
scipy version 1.16.1<br>
math version 3.11.13<br>
Path version 3.11.13<br>
