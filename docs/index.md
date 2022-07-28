---
layout: default
title: ""
---
<a name="Membership">
# Request for membership User Group SDC
Make sure that you have a (free) GitHub account, then fill in [this form](ContactForm.html). <br>

# User Group Workshop, September 20, 2022, Paris
The Statistical Disclosure Control (SDC) team of the Centre of Excellence for Statistical Methods and Tools (STACE) invites you to participate in a one-day User Workshop on practical implementation of SDC in statistical production and dissemination, on the 20th of September 2022, taking place in Paris, at INSEE.

The aim of the Workshop is to stimulate knowledge sharing, discussions and interactions between SDC users. You are invited to give short presentations on special problems, work in progress, interesting examples from your institute’s experience regarding SDC implementation. 

You might also consider combining your attendance of the SDC Workshop with taking part in the international, research oriented, conference on Privacy in Statistical Databases 2022 which will be held during 21-23 of September in Paris (see [here](https://crises-deim.urv.cat/psd2022/index.php) for more information).

More details on registration and organization:
  
- Deadlines
    - Submission of abstracts: **extended** to the 15-th of July 2022
    - Selection results: 31-st of July 2022
    - Publishing the Workshop agenda: 15-th of August 2022

- Forms
    - **Abstract** submission [form](AbstractForm_UserWorkshop.html). *Closed*.
    - **Registration** [form](RegistrationFormWorkshop2022.html) <br>
      Note that registration is mandatory for all participants due to limited attendance: first come first served, with preference for authors of presentations.
      No registration fee will be required. *Closed*.
 
 - List of accepted abstracts [pdf](Abstracts_W2022.pdf)
  
 - Preliminary Agenda [pdf](draft_agenda_W2022.pdf)
  
 - Venue <br>
    **INSEE** <br>
    Room WHITE-RC-B-257 (ground floor) <br>
    88 avenue Verdier, 92120 Montrouge <br>
    Access by Metro Line 4 (20 minutes from center of Paris) + 10 minutes walk. 

 <br>
  
# User Group meeting 2022
The 2022 SDC User Group meeting took place online on February 25. There were 36 participants from 18 different countries. There were presentations by the developers teams on the status quo of the different SDC tools, a discussion on the pros and cons of the different LP-solvers needed for some of the approaches in &tau;-argus and a presentation of a new initiative by INSEE to write an R-wrapper for &tau;-argus called `rtauargus` (see [here](https://github.com/sdcTools/rtauargus) for the sources).
<br>

<a name="News">
# News
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

<a name="Support">
# UserSupport
Check out [the wiki](https://github.com/sdcTools/UserSupport/wiki) 
and [the issues](https://github.com/sdcTools/UserSupport/issues) 
for more details and discussion.

<a name="Releases">
# Releases
Find out about the latest releases of the tools [here](Releases.md)

<a name="Statistics">
# Statistics
Find out about the download statistics of the tools [here](Statistics.md)
