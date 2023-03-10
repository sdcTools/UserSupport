---
layout: default
title: ""
---
 
<a name="Events"> 
# Events 
 
## Workshop on Statistical Disclosure Control of Census-data 
  
  _May 23, 2023, online_
  
 - Invitation
 - [Registration form](SDCWorkshopCensus2023.html)
 - Deadline
 - Agenda 
  
## User Group meeting 2023
The 2023 User Group meeting took place online, 10:00 - 12:30 C.E.T.,  on February the 23-rd. 
  
The meeting agenda and the slides of the presentations, as well as the minutes of the meeting are available [here](https://github.com/sdcTools/UserMeetings/tree/master/User%20Group%20Meeting%20%233%20-%2023.02.23).
There were 35 participants and five presentations concerning both the status/progress of the sdc-tools presented by developers and several practical solutions/applications presented by users. 
  
## User Group Workshop 2022

On September 20, 2022, a SDC Useer Group Workshop took place in Paris, at INSEE. Being a hybrid meeting, it was also possible to attend the workshop online. The workshop concentrated on practical implementations of SDC in statistical production and dissemination. There were 7 presentations given by different users coming from France, Germany, Ireland, Norway, Poland and Iceland. More details can be found here: [List of accepted abstracts (pdf)](Abstracts_W2022.pdf), [Agenda (pdf)](draft_agenda_W2022.pdf) and [Slides of presentations (pdf)](https://github.com/sdcTools/UserSupport/blob/master/docs/W2022/).

## User Group meeting 2022
The 2022 SDC User Group meeting took place online on February 25. There were 36 participants from 18 different countries. There were presentations by the developers teams on the status quo of the different SDC tools, a discussion on the pros and cons of the different LP-solvers needed for some of the approaches in &tau;-argus (see [slides](https://github.com/sdcTools/UserMeetings/tree/master/User%20Group%20Meeting%20%232%20-%2025.02.22)) and a presentation of a new initiative by INSEE to write an R-wrapper for &tau;-argus called `rtauargus` (see [here](https://github.com/sdcTools/rtauargus) for the sources).

<br>


<a name="News">
# News

**March 10, 2023** <br>
NEW TEST RELEASE: A new release for testing is uploaded: [&tau;-argus version 4.2.4](https://github.com/sdcTools/tauargus/releases/tag/v4.2.4-TEST).
The main new features to be tested are:
- Save and read recode files, including recode files for tree-based hierarchical variables
- Keep status (optionally) with tabular input made additive

Additional information on the new features can be found in the `Version history` section of the `ReleasenoteTauArgus4.2.4.pdf`.

Obviously, other tests are welcome as well, e.g. making sure that older features are still working as before.

Feedback is welcome until Marh 25. I intend to make the release official on April 1.
  
**July 29, 2022** <br>
NEW RELEASE: [Version 4.2.3 build 1 of &tau;-argus](https://github.com/sdcTools/tauargus/releases/tag/v4.2.3) is now available. The main change is that it is now possible to use the improved ptables produced by the [ptable R package](https://github.com/sdcTools/ptable) (version 0.4.0 and higher). This is important for users of CKM for frequency count tables of the census 2021.
  
Note that previous versions of &tau;-argus (version 4.2.2 and lower) will apply the new ptables incorrectly without issuing a warning!
  
**March 18, 2022** <br>
NEW RELEASE: [Version 4.2.2 build 1 of &tau;-argus](https://github.com/sdcTools/tauargus/releases/tag/v4.2.2.1) is now available. The main improvement in this version is in the Modular approach, where the engine was partly rewritten to improve memory management and stability. Additionally, for some instances of (sub)tables with infeasible suppression problems, &tau;-argus no longer crashes but produces an error message and will stop calculation. Additionally some bugs were fixed (spaces in directory names are now allowed, cell keys are correctly saved in CKM for frequency count tables, etc.). 
  
**January 14, 2022: new build of version 5.1.6 of &mu;-argus released** <br>
IMPORTANT NOTE:  
&mu;-Argus version 5.1.6 build 1 sometimes did not save the report file properly. This is now fixed in build 2. Moreover, the "undo"-actions for TRS have been improved.
This new build can be found [here](https://github.com/sdcTools/muargus/releases/tag/v5.1.6b2).
  
**June 7, 2021** <br>
NEW RELEASE: [Version 5.1.6 build 1  of &mu;-argus](https://github.com/sdcTools/muargus/releases/tag/v5.1.6b1) is now available. This version contains some updates concerning Targeted Record Swapping (TRS). In the report file some information on the number of (non)-swapped households and swapped records is included and the lay-out of the report file concerning TRS-info has changed slightly. Moreover, in the `%TEMP%` directory a log-file will be saved with the IDs of households for which no donor household could be found based on the used similarity variables.
  
From this release onwards, only a 64 bit compiled executable of &mu;-argus will be made available.
  
**April 7, 2021** <br>
A Windows 64 bit compiled release of version [5.1.5 build 3 of &mu;-argus](https://github.com/sdcTools/muargus/releases/tag/5.1.5.3) is now available. This version is able to deal with larger datasets when applying Targeted Record Swapping as compared to the 32 bit release.

**January 22, 2021** <br>
NEW RELEASE: [Version 5.1.5 build 3 of &mu;-argus](https://github.com/sdcTools/muargus/releases/tag/5.1.5.3) is now available. This version includes Targeted Record Swapping. The GUI for using this method is still under development, but the basic functionality of TRS is now available.

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
Check out [the wiki](https://github.com/sdcTools/UserSupport/wiki) 
and [the issues](https://github.com/sdcTools/UserSupport/issues) 
for more details and discussion.

Have a look at [the FAQ](https://github.com/sdcTools/UserSupport/wiki/FAQ) for frequently asked questions.

<br>

<a name="Releases">
# Releases
Find out about the latest releases of the tools [here](Releases.md)

<br>

<a name="Statistics">
# Statistics
Find out about the download statistics of the tools [here](Statistics.md)
<br>
