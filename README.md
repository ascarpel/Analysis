# LArTPC Analysis 
Set of useful libraries and examples of macros for the dual-phase LArTPC analysis. Work is still in progress. for questions:<a href="mailto:andrea.scarpelli@cern.ch" target="_blank"> andrea.scarpelli@cern.ch </a>
## Prerequisites
The project requires ROOT 6.10: <a href="https://root.cern.ch/downloading-root" target="_blank">https://root.cern.ch/downloading-root</a> or a more recent version.
## Folder organization
A quick summary of the library contents
### DataStructure.hh
### Run.hh
### Geometry.hh
### Cuts.hh
### Efficiency.hh
## Getting Started
### Run as ROOT macro
To run a macro:
```
root -l loadLib.cc myMacro.cc
```
or
```
root -l loadLib.cc
root[0] .x myMacro.cc
```
### Run as compiled executable

