# HARMONIE Virtual System Working Week

 - Date: 19 - 23 April  2021
 - [Google link](https://meet.google.com/aem-dubz-ihj)
 - [Notes](https://hirlam.org/trac/wiki/Meetings/System/Video_Meetings/2022) from previous meeting  
 - Markdown format [Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)  

## Participants

Name              | Institute  | ARR - DEP        |  Home       
---               | ---        | ---              | ---         
Roel Stappers     | MET Norway | Monday - Friday  | Grubbenvorst 
Daniel Santos     | DMI        | Monday - Friday  | Becerril     
Ulf Andrae        | SMHI       | Monday - Friday  | Norrköping   
Toon Moene        | KNMI       | Monday - Friday  | Maartensdijk 
Eoin Whelan       | METIE      | Monday - Friday  | Trim         
Bert van Ulft     | KNMI       | Monday - Friday  | Utrecht      


##  Agenda 

- CY43:
  - Testing for tagging 43h2.2
  - Review issues and Pending tasks
  - Workflow in GitHub (pull requests, user forks, ...)
  - Documentation
- CY46:
  - Status
  - Pysurfex validation
  - CMake (see [ticket](https://hirlam.org/trac/ticket/188) ) and OOPS
  - Sub-hourly cycling and scripting design
- CY48:
  - Status
  - Pending branches
  - Compilation in CCA and TEMS
- ACCORD Convergence actions: 
  - Questionaire
  - GIT solution
  - Bundle
  - Workflow, docs, training.  
- Revisit status of system priorities for 2021
- AOB

##  Priorities 2021 

   1. Davaii and mitrailllette for Harmonie if is possible outside MF 
   2. Bundling tool 
   3. Common work space (gitlab, docs ...)
   4. Cross families working weeks
   5. Subhourly cycling based in perl or rewrite in python (resources ???)- '''Implementation in cy46'''

##  General questions 

- How to control the namelist settings more effectively?
- Where and how to document model changes and spread the info ?
- Improve code modularity (for scripts) and use of package managers. Julia used as proof of concept- 
- Move to GitHub, gitlab the OpenSource software and how to treat the private areas for proprietary software
- pull request, feature codes, documentation and port to different code versions
- limits of free solutions
- Ideas for github actions that would be useful to run on each commit (e.g. unit tests).
- Clean up of [stale branches](https://github.com/Hirlam/Harmonie/branches/stale). Why are e.g. `SICE` and `POLYNOMES_ISBA_MF6` used in [43h2.1.target.1](   https://github.com/Hirlam/Harmonie/compare/harmonie-43h2.1.target.1) and [43h2.1.target.2](https://github.com/Hirlam/Harmonie/compare/harmonie-43h2.1.target.2) not the default in `develop`
- Better to remove the gridpp and titanlib forks?  
- Add more [labels](https://github.com/Hirlam/Harmonie/issues/labels) (like `Data assimilation`, `IASI`) See [pull request](https://github.com/Hirlam/Harmonie/pulls?q=is%3Apr+is%3Aclosed) so in the future we get overviews of  commits/pull request relevant for specific Harmonie components.  


### Monday  

9:30 - 10:30  Videomeeting on: Introduction to the Virtual System WW
- Status of different cycles and outcomes for HMG meeting
- SWW tasks organization

10:30 - 11:00 Coffee Break

11:00 - 12:00  Work

12:00 - 12:30 Progreses report

12:30 - 13:30 Launch break

13:30 - ...  Work
 
### Tuesday - Friday 

9:00 - 10:00 Previous day wrap-up video-meeting

10:00 - 10:30 Coffee Break

10:30 - 12:00 Work

12:00 - 12:30 Progress report

12:30 - 13:30 Launch break

13:30 - ... Work

## Meeting notes and tasks progress 

### CY43



### CY46

### CY48
