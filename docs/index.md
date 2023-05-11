---
layout: default
title: ""
---

# <img src="Info.png" style="float: left; margin-right: 10px; width: 30px" />[New official release &tau;-argus](#News)
 
<a name="Events"> 
 
# Upcoming event

## Workshop on Statistical Disclosure Control of Census-data 
  
  _May 23, 2023, online_
  
 - [Invitation](WCensusSDC2023/Invitation_SDC_Census_Workshop.pdf){:target="_blank"}
 - Registration:  closed
 - [Agenda](WCensusSDC2023/Agenda_WorkshopCensusSDC2023.pdf){:target="_blank"}

# Previous Events
An overview of events organized by the UserSupport on SDCTools group can be found [here](PreviousEvents.md).
 
<br>

<a name="News">
# News

**April 26, 2023**<br>
The official release of [&tau;-argus version 4.2.4 (build 2)](https://github.com/sdcTools/tauargus/releases/tag/v4.2.4.2){:target="_blank"} is now available. the bugs found by Vito Klop&#269;i&#269; are fixed. 
 
**April 14, 2023**<br>
Thanks to the testing of the [&tau;-argus TEST version 4.2.4](https://github.com/sdcTools/tauargus/releases/tag/v4.2.4-TEST){:target="_blank"} by Vito Klop&#269;i&#269;, a bug was found that needed to be fixed before officially releasing this version. As a result, the official release did not take place on April 1, 2023 (as intended), but will take place in the week of April 24, 2023.
 
**March 15, 2023**<br> 
The R-packages `ptable` and `cellKey` are now officially available on CRAN. The official releases of these packages will henceforth be made available not only from the GitHub repositories on [sdcTools](https://github.com/sdcTools){:target="_blank"}, but also from CRAN: [ptable](https://cran.r-project.org/web/packages/ptable){:target="_blank"} and [cellKey](https://cran.r-project.org/web/packages/cellKey){:target="_blank"}. Developers versions of the packages will still only be available through the GitHub repositories on [sdcTools](https://github.com/sdcTools){:target="_blank"}.
 
**March 10, 2023** <br>
NEW TEST RELEASE: A new release for testing is uploaded: [&tau;-argus version 4.2.4](https://github.com/sdcTools/tauargus/releases/tag/v4.2.4-TEST){:target="_blank"}.
The main new features to be tested are:
- Save and read recode files, including recode files for tree-based hierarchical variables
- Keep status (optionally) with tabular input made additive

Additional information on the new features can be found in the `Version history` section of the `ReleasenoteTauArgus4.2.4.pdf`.

Obviously, other tests are welcome as well, e.g. making sure that older features are still working as before.

Feedback is welcome until Marh 25. I intend to make the release official on April 1.
  
**July 29, 2022** <br>
NEW RELEASE: [Version 4.2.3 build 1 of &tau;-argus](https://github.com/sdcTools/tauargus/releases/tag/v4.2.3){:target="_blank"} is now available. The main change is that it is now possible to use the improved ptables produced by the [ptable R package](https://github.com/sdcTools/ptable){:target="_blank"} (version 0.4.0 and higher). This is important for users of CKM for frequency count tables of the census 2021.
  
Note that previous versions of &tau;-argus (version 4.2.2 and lower) will apply the new ptables incorrectly without issuing a warning!
  
**March 18, 2022** <br>
NEW RELEASE: [Version 4.2.2 build 1 of &tau;-argus](https://github.com/sdcTools/tauargus/releases/tag/v4.2.2.1){:target="_blank"} is now available. The main improvement in this version is in the Modular approach, where the engine was partly rewritten to improve memory management and stability. Additionally, for some instances of (sub)tables with infeasible suppression problems, &tau;-argus no longer crashes but produces an error message and will stop calculation. Additionally some bugs were fixed (spaces in directory names are now allowed, cell keys are correctly saved in CKM for frequency count tables, etc.). 
  
**January 14, 2022: new build of version 5.1.6 of &mu;-argus released** <br>
IMPORTANT NOTE:  
&mu;-Argus version 5.1.6 build 1 sometimes did not save the report file properly. This is now fixed in build 2. Moreover, the "undo"-actions for TRS have been improved.
This new build can be found [here](https://github.com/sdcTools/muargus/releases/tag/v5.1.6b2){:target="_blank"}.
  
**June 7, 2021** <br>
NEW RELEASE: [Version 5.1.6 build 1  of &mu;-argus](https://github.com/sdcTools/muargus/releases/tag/v5.1.6b1){:target="_blank"} is now available. This version contains some updates concerning Targeted Record Swapping (TRS). In the report file some information on the number of (non)-swapped households and swapped records is included and the lay-out of the report file concerning TRS-info has changed slightly. Moreover, in the `%TEMP%` directory a log-file will be saved with the IDs of households for which no donor household could be found based on the used similarity variables.
  
From this release onwards, only a 64 bit compiled executable of &mu;-argus will be made available.
  
**April 7, 2021** <br>
A Windows 64 bit compiled release of version [5.1.5 build 3 of &mu;-argus](https://github.com/sdcTools/muargus/releases/tag/5.1.5.3){:target="_blank"} is now available. This version is able to deal with larger datasets when applying Targeted Record Swapping as compared to the 32 bit release.

**January 22, 2021** <br>
NEW RELEASE: [Version 5.1.5 build 3 of &mu;-argus](https://github.com/sdcTools/muargus/releases/tag/5.1.5.3){:target="_blank"} is now available. This version includes Targeted Record Swapping. The GUI for using this method is still under development, but the basic functionality of TRS is now available.

**August 14, 2020** <br>
Small issue with the latest release (4.2.0 build 5) of &tau;-argus when installed in a directory that contains spaces (e.g., `C:\Program Files (x86)`). Two possible solutions: 
- Install in a directory _without_ spaces<br>
or
- Replace the `ArgusLib.jar` in the `lib`-subdirectory of your &tau;-argus installation, by the one in [this zipfile](https://github.com/sdcTools/UserSupport/files/5074573/ArgusLib.zip)

The next release will be able to deal with directories with spaces again.

**June 5, 2020** <br>
NEW RELEASE: Version 4.2.0 build 5 of &tau;-argus is now available. This version includes noise addition using the Cell Key Method for frequency count tables as well as magnitude tables.

<br>

<a name="Support">
# UserSupport
Check out [the wiki](https://github.com/sdcTools/UserSupport/wiki){:target="_blank"} 
and [the issues](https://github.com/sdcTools/UserSupport/issues){:target="_blank"} 
for more details and discussion.

Have a look at [the FAQ](https://github.com/sdcTools/UserSupport/wiki/FAQ){:target="_blank"} for frequently asked questions.

<br>

<a name="Releases">
# Releases
Find out about the latest releases of the tools [here](Releases.md)

<br>

<a name="Statistics">
# Statistics
Find out about the download statistics of the tools [here](Statistics.md)
<br>
 
