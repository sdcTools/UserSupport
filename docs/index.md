---
layout: default
title: ""
---

<a name="Application Course on Business Statistics">
# Application for Course on Tabular Data Protection in Business Statistics
Applications for the online course on **Tabular Data Protection in Business Statistics** are now open. <br>
The course will be held from 6th-8th Oct 2021 online.
This course shares content with the ESTP course on Statistical Disclosure Control, which was held in early 2021, but will focus deeper on the specifics of business statistics.
There will be limited spots to apply for and applicants who were refused for the latter course, will be given priority.<br>
Please apply for the course [**here**](ContactFormBusinessCourse.html) until 24th Sep 2021.

<a name="Membership">
# Request for membership User Group SDC
First make sure that you have a (free) github account. 
Then you have two options:
- Fill in [this form](ContactForm.html) 
- or add a comment to [this issue](https://github.com/sdcTools/UserSupport/issues/155).

<a name="News">
# News
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
