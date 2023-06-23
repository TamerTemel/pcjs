---
layout: page
title: "PC-SIG Diskette Library (Disk #1222)"
permalink: /software/pcx86/sw/misc/pcsig/1000-1999/DISK1222/
machines:
  - id: ibm5170
    type: pcx86
    config: /machines/pcx86/ibm/5170/cga/1024kb/rev3/machine.xml
    diskettes: /machines/pcx86/diskettes.json,/disks/pcsigdisks/pcx86/diskettes.json
    autoGen: true
    autoMount:
      B: "PC-SIG Library Disk #1222"
    autoType: $date\r$time\rB:\rDIR\r
---

{% include machine.html id="ibm5170" %}

{% comment %}info_begin{% endcomment %}

## Information about "PHAMPHLET"

    PAMPHLET is a printing utility for HP LaserJets that creates 5-1/2" x
    8-1/2" mini-booklets or pamphlets.
    
    PAMPHLET divides any ASCII file into mini-pages, and then prints them in
    landscape (sideways) mode, two-up on a single sheet.  A second pass
    through the printer to print the opposite side and -- VOILA!  You have a
    mini book.  Page arrangement is automatically determined by the program
    so the resultant sheets are in correct order.  Just fold down the middle
    and staple to form useful little pamphlets, booklets, or documentation
    manuals.  PAMPHLET is also great for parents wanting to create
    personalized story books for their children.
    
    Users can select from any of 25 resident fonts, upload additional soft
    fonts, place page breaks, automatically number pages, underline, and
    more.  There is even a built-in editor, and a configuration for using
    the program with European metric A4 paper size.
{% comment %}info_end{% endcomment %}

{% comment %}samples_begin{% endcomment %}

## A4.DOC

{% raw %}
```
3800 7340
5 85
91 171
7.0

The top 4 lines are the only ones used by the program.  You may
add comments from this position on.

This file is my answer to a number of European and Far Eastern
requests for PAMPHLET to use A4 paper size.  I have tried a
number of ways to implement this change but have been
unsuccessful because of the need for a specific A4 tray which
automatically sets the printer's paper definition.  Soft
selecting A4 and manual paper feeding have not worked in my
experiments.  My thanks to those of you who have sent A4 paper
for comparison.  It has helped, even though I couldn't use it
directly.  The above 7 numbers are the only ones needed by the
program to determine pamphlet page and center line positioning.
You may modify them but the format MUST be as above.  Lines 1,2
and 3 MUST contain 2 integer numbers (ie no decimal point) which
are separated by a space.  Line 4 contains but one number which
may or not have a decimal point.

To use this file, rename it to A4.DAT or create a file of at
least the top 4 mandatory lines and name it A4.DAT. The program
will look for a file named A4.DAT on initialization. It will look
first on the default directory (the directory where you are when
you run the program) and then in the directory you have setup and
saved as a font directory location (screen 2).  If not found, the
program will use the default values noted.


The first line --

  first number  -- Default 3800
                horizontal point location of the center line.
                Higher numbers move the line to the right.  A4
                paper should require around 4050.

  second number -- Default 7340
                length of the center line in points.  A4 paper
                may require a smaller number.

The second line -- Default 5 85
                Left (5) and Right (85) margin definitions of the
                left side pamphlet page.  The numbers represent
                lineprinter sized characters (16.66 cpi).  The
                difference between margins should be 80
                characters.  A4 paper may require adding
                approximately 3 to each of these numbers.

The third line -- Default 91 171
                Left (91) and Right (171) margin definitions of
                the right side pamphlet page.  The numbers
                represent lineprinter sized characters (16.66
                cpi).  The difference between margins should be
                80 characters.  A4 paper may require adding
                approximately 7 to each of these numbers.

The fourth line  -- Default 7.4
                Printable page length in inches (remember we are
                in landscape mode).  A top margin of approx 1/2
                inch is automatically generated by the program.
                Adjust this number for an appropriate bottom
                margin.  A4 paper should be around 7.1 or 7.2.
                The pamphlet program is able to print 2 pages
                side by side by "fooling the printer" and not
                printing beyond the printer's physical bottom
                line before resetting the margin and printing the
                other side.  If you set this number too large,
                the printer will eject the paper before printing
                of the right side pamphlet page is complete.

Known (and still to be corrected) bugs using this method of page
definition.  The automatic title page option is not yet aligned.
It is a fairly simplistic title and most users don't use it.
Screen 2 automatic font selection using the function keys will
incorrectly display the lines per page (unless you have a page
length of 7.4 inches).  It will correctly display once you step
through using the enter or arrow keys.

I hope this fix will work for you.  I'd appreciate hearing the
values that work best for your configuration.

Sincerely,



Martin
```
{% endraw %}

## FILE1222.TXT

{% raw %}
```
Disk No: 1222
Program Title: PAMPHLET version 3.1
PC-SIG version: 1

PAMPHLET is a printing utility for HP LaserJets that creates 5-1/2" x
8-1/2" mini-booklets or pamphlets.

PAMPHLET divides any ASCII file into mini-pages, and then prints them in
landscape (sideways) mode, two-up on a single sheet.  A second pass
through the printer to print the opposite side and---VOILA!  You have a
mini book.  Page arrangement is automatically determined by the program
so the resultant sheets are in correct order.  Just fold down the middle
and staple to form useful little pamphlets, booklets, or documentation
manuals.  PAMPHLET is also great for parents wanting to create
personalized story books for their children.

Users can select from any of 25 resident fonts, upload additional soft
fonts, place page breaks, automatically number pages, underline, and
more.  There is even a built-in editor, and a configuration for using
the program with European metric A4 paper size.

Usage:  Laser Printer Utility.

Special Requirements:  HP LaserJet II.

How to Start:  Type GO (press enter).

Suggested Registration:  $25.00

File Descriptions:

PAMPHLET EXE  Main Program.
PAMPHINS EXE  Installation program.
OLDVERS  EXE  Previous PAMPHLET Program version.
PAMPH31  DOC  Documentation.
A4       DOC  A4 paper Documentation.
README   1ST  Latest release notes.

PC-SIG
1030D E. Duane Avenue
Sunnyvale Ca. 94086
(408) 730-9291
(c) Copyright 1989 PC-SIG, Inc.

```
{% endraw %}

## GO.TXT

{% raw %}
```
╔═════════════════════════════════════════════════════════════════════════╗
║                   <<<<  Disk No 1222 PAMPHLET  >>>>                     ║
╠═════════════════════════════════════════════════════════════════════════╣
║ To start the program, type PAMPHLET (press enter)                       ║
║                                                                         ║
║ To copy the documentation to your printer, type MANUAL (press enter)    ║
╚═════════════════════════════════════════════════════════════════════════╝
```
{% endraw %}

{% comment %}samples_end{% endcomment %}

### Directory of PC-SIG Library Disk #1222

     Volume in drive A has no label
     Directory of A:\

    A4       DOC      3994   4-17-88   1:38p
    FILE1222 TXT      1496  12-09-88  10:28a
    GO       BAT        38   1-18-88   1:38p
    GO       TXT       540  11-16-88  10:27a
    MANUAL   BAT       174  11-16-88  10:28a
    OLDVERS  EXE     86565   3-13-88  10:58a
    PAMPH31  DOC     34949   4-17-88   1:28p
    PAMPHINS EXE     22144   3-12-88   8:31p
    PAMPHLET EXE     83216   5-15-88   2:25p
    README   1ST     11348   4-25-88   6:26p
           10 file(s)     244464 bytes
                           71680 bytes free