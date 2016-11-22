![alt text](../README_imgs/SAS9toViya.JPG "SAS 9 bridge to Viya")

# SAS Enterprise Miner Bridge To SAS Viya
This repository contains examples and documentation showing how to run SAS Viya programs from a SAS Enterprise Miner flow.  It is organized into two main directories of examples: "EM-14.1" for Enterprise Miner version 14.1 and earlier, and "EM-14.2" for examples using a new "SAS Viya" node in Enterprise Miner 14.2 and later.

## License

Copyright (c) 2016 by SAS Institute Inc., Cary, NC 27513 USA

Licensed under the Apache License, Version 2.0 (the "License"); 
you may not use this file except in compliance with the License. 
You may obtain a copy of the License at 

   http://www.apache.org/licenses/LICENSE-2.0 

Unless required by applicable law or agreed to in writing, software 
distributed under the License is distributed on an "AS IS" BASIS, 
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. 
See the License for the specific language governing permissions and 
limitations under the License.  

## Summary

This repository contains example diagrams and materials for using SAS Enterprise Miner to perform data mining.

The repository includes XML files (which represent SAS Enterprise Miner process flow diagrams) and accompanying PDF files 
to help guide you through the process flow diagrams.  In SAS Enterprise Miner 14.1 and prior, the SAS Code node is used to invoke the code that connects to SAS Viya and executes the specified code. In SAS Enterprise Miner 14.2, a new dedicated "SAS Viya" node is provided which offers special macros to do much of the work.  This repository contains examples for each.

##### These examples were tested in the following environment:

Windows Server 2008 R2 Enterprise

Dual Intel Xeon E5-2667 @ 2.9 GHz

128 GB RAM 

SAS 9.4 (TS1M3)

SAS Enterprise Miner 14.1 and 14.2

## Instructions

Download (and unzip) or clone this repository. The repository contains a directory for the SAS Code node examples (pre-14.2) and the SAS Viya node examples (14.2+). Each directory contains one or more example XML files (diagrams) and associated PDF documentation. 

To run these examples:

1. Create a new Project or open an existing project in SAS Enterprise Miner. 

2. Right-click on the Diagrams folder in the top left corner (or use the File menu) and select "Import Diagram from XML...". Select the XML file from one of the directories, and open the corresponding PDF document to learn more details about the example.

3. Define any data sources as necessary for the given example.

4. Edit the code in each code node to specify the appropriate SAS Viya and CAS server information.

5. Right-click on the last node and select "Run" to run the process flow diagram.

## Contributors

Jagruti Kanjia, Dominique Latour, Brett Wujek
