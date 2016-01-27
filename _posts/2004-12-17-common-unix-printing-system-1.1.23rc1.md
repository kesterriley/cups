---
title: Common UNIX Printing System 1.1.23rc1
layout: post
---

<P>The first release candidate for version 1.1.23 of the Common
- The lpr man page did not document the "-U" option (Issue #998)
- The scheduler no longer sends the page-set option when
- Fixed a debug message in the imagetops filter (Issue #1012)
- The lprm man page listed the "-" option in the wrong
- The hpgltops filter contained two buffer overflows
- The lppasswd command did not protect against file
- The "lpc status" command used the wrong resource path
- The httpWait() function did not handle signal
- The USB backend used the wrong size status variable
- The scheduler did not delete classes from other
- The IPP backend now logs the remote print job ID at