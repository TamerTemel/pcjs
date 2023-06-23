---
layout: page
title: "PC-SIG Diskette Library (Disk #1051)"
permalink: /software/pcx86/sw/misc/pcsig/1000-1999/DISK1051/
machines:
  - id: ibm5170
    type: pcx86
    config: /machines/pcx86/ibm/5170/cga/1024kb/rev3/machine.xml
    diskettes: /machines/pcx86/diskettes.json,/disks/pcsigdisks/pcx86/diskettes.json
    autoGen: true
    autoMount:
      B: "PC-SIG Library Disk #1051"
    autoType: $date\r$time\rB:\rDIR\r
---

{% include machine.html id="ibm5170" %}

{% comment %}info_begin{% endcomment %}

## Information about "FINDATA CORPORATE PROFILE 1 OF 2 (1052)"

    FINDATA CORPORATE PROFILE is a well-documented, two-disk set of data on
    over 4,000 publicly-traded corporations.  It operates as a database
    within any system that reads dBase III files or can use its own built-in
    database system.  Corporate data supplied includes: ticker symbol, name,
    address, city, state, zip code, telephone, president's name, type of
    industry, industry code, stock exchange code, year of latest data,
    company's fiscal year, annual sales, after-tax profits, earnings per
    share, average number of shares outstanding, sales margin, the high and
    low stock market price, and the high and low price-to-earnings ratio.
{% comment %}info_end{% endcomment %}

{% comment %}samples_begin{% endcomment %}

## FILE1051.TXT

{% raw %}
```
Disk No: 1051
Program Title:  FINDATA CORPORATE PROFILE DATA (Disk 1 of 2)
PC-SIG Version:  1.3

FINDATA CORPORATE PROFILE is a well-documented, two-disk set of data on
over 5000 publicly-traded corporations.  It operates as a database
within either PC-FILE+ or dBase III, and also interfaces with either
PC-CALC or VisiCalc.

Corporate data supplied includes: ticker symbol, name, address, city,
state, zip code, telephone, president's name, type of industry, industry
code, stock exchange code, year of latest data, company's fiscal year,
annual sales, after-tax profits, earnings per share, average number of
shares outstanding, sales margin, stock market price, and
price-to-earnings ratio.  This comprehensive package places a mass of
data at your fingertips and uses the power and versatility of either
PC-FILE+ or DBase III to manipulate it.  The second disk in this set is
#1052.

Usage:  Business Applications.

Special Requirements:  PC-FILE+ or dBASE III, and a hard drive with at
least 1.5 MB of available space.

How to Start:  Type GO (press enter).

Suggested Registration:  $55.00, with quarterly updates available for
$45.00 per calendar quarter.

File Descriptions:

FLOP     BAT  Batch file to install files to floppy disks.
HARD     BAT  Batch file to install files to your hard drive.
PKXARC   COM  Unarchiving program to unarchive FINDATA.ARC.
FINDATA  ARC  Archived file containing data files.

PC-SIG
1030D E Duane Avenue
Sunnyvale, CA   94086
(408) 730-9291
(c) Copyright 1988,89 PC-SIG, Inc.

```
{% endraw %}

## FINDATA.DOC

{% raw %}
```



                            FINDATA CORPORATE PROFILES
                           "THE BOOK THAT PRINTS ITSELF"


                         A DATABASE CONTAINING GEOGRAPHIC,
                           INDUSTRIAL AND FINANCIAL DATA
                      ON OVER 5,000 PUBLICLY TRADED COMPANIES


                            FINDATA IS A TRADEMARK OF 
                               COMP U PRINT COMPANY
                             12595 NW CORNELL ROAD # C
                                PORTLAND, OR 97229

                                  COPYRIGHT 1988

                                ALL RIGHTS RESERVED

                             TELEPHONE: (503) 646-3386












      DISCLAIMER

      Comp  U Print Company has used due care and caution in the preparation
      of  the  FINDATA  CORPORATE  PROFILES. The information herein has been
      obtained  from actual company annual reports and press releases. These
      sources  are  believed to be accurate and reliable, but because of the
      possibility   of   human   and   mechanical  error,  the  accuracy  or
      completeness of the FINDATA CORPORATE PROFILES is NOT guaranteed.





















                  FINDATA CORPORATE PROFILES - REGISTRATION FORM
      If  you  use  the  FINDATA  CORPORATE  PROFILES  and find them useful.
      please  become  a registered owner. With your registration fee of only
      $75.00,  you  will  receive  the latest version of the updated FINDATA
      CORPORATE  PROFILES (the registered version contains profiles on 6,000
      public  corporations)  and a loose-leaf manual. The manual in addition
      to  the  program  instructions,  contains a complete list of all 6,000
      corporations  in the database with their TICKER, COMPANY NAME, and SIC
      CODE.  Also,  registered  owners of the FINDATA CORPORATE PROFILES may
      purchase  quarterly  updates of the corporate profiles for only $50.00
      per  update.  Updates  are  produced  for  months  ending March, June,
      September, and December of each year.

      To  register,  complete the following form and send it along with your
      check for $75.00 to:

                               Comp U Print Company
                              1295 NW CORNELL ROAD #C
                                PORTLAND, OR 97229

      ---------------------------------------------------------------------

          Name:                                                       

          Company Name:                                               

          Purchase Order Number:                                      

          Address:                                                    

          City:                     State:                Zip:        

          Telephone Number:                                           

      ---------------------------------------------------------------------

      Note:  The Registration fee of $75.00 includes all costs for handling,
      shipping and state sales tax.

      Or  if  you  would  like  to  become  a  registered owner through your
      company,  send us your company purchase order and we will bill you for
      the $75.00 registration fee.

      If  you  have  any questions before becoming a registered owner of the
      FINDATA CORPORATE PROFILES, please call us. Our telephone number is:

                                  (503) 641-4133













      COMP U PRINT COMPANY SHAREWARE CONCEPT

      This  is the Shareware version of the FINDATA CORPORATE PROFILES. This
      version  of our manual and the diskettes enclosed can be freely copied
      and shared with others.

      If  you  use  the  FINDATA CORPORATE PROFILES and like it, we ask that
      you  register.  Registration  costs only $75.00. The FINDATA CORPORATE
      PROFILES  are  update  every quarter. Only registered owners may order
      quarterly  updates.  Quarterly  updates costs only $50.00 per quarter.
      The  FINDATA  CORPORATE  PROFILES  are updated on months ending March,
      June, September and December of each year.

      Registration  allows  us to continue to improve and update the product
      and  still  keep  the  cost of good software and databases reasonable.
      Please support us if you use the FINDATA CORPORATE PROFILES.












































                     FINDATA CORPORATE PROFILES - USERS MANUAL

                                 TABLE OF CONTENTS


      DESCRIPTION                                           PAGE NUMBER

      1. Introduction to FINDATA                                      1

      2. Equipment Supplied                                           2

      3. hardware Requirements                                        2

      4. Database Installation - on PC-FILE+                          2

      5. Importing the Corporate Profiles                           2-4

      6. Finding a Corporate Profile                                  4

      7. Creating and Producing Reports                               4

      8. Producing FINDATA Reports                                    5

      9. Creating Labels                                            5-6

      10. Using FINDATA with dBASEIII                                 6

      11. Purchasing FINDATA updates                                  6
































      Introduction to FINDATA                                    Page:  1
      The   FINDATA  CORPORATE  PROFILES  comes  complete  with  a  database
      containing  information on over 5,000 publicly traded companies and an
      evaluation   copy  of  PC-FILE+.  PC-FILE+  is  a  shareware  database
      management  system  from  Buttonware  Inc.  COMP  U  PRINT  CO.  is  a
      registered  owner  of  PC-FILE+  and, as such, can share this software
      with  our customers. There is no charge to our customers for providing
      them with a copy of this software package. 

      FINDATA CORPORATE PROFILES - Data Elements

      Field Name                                       type      Width
      TICK  (ticker symbol)                            char      10
      NAME  (company name)                             char      30
      ADDRESS                                          char      30
      CITY                                             char      20
      STATE  (state code)                              char      02
      ZIP                                              char      05
      TELEPHONE                                        char      14
      PRESIDENT (CEO, president or invest. cont.)      char      20
      INDUSTRY  (industry description)                 char      40
      SIC CODE  (SEC industry code)                    char      04
      EXCH CODE  (NY, AMEX, OTC, TORONTO, FOREIGN)     char      01
      YEAR  (year of the latest financial data)        char      02
      FYEAR  (company's calendar year)                 char      02
      SALES  (annual sales)                            numb      10
      PROFIT  (after taxes and extra credit)           numb      10
      EPSHARE  (earnings per share)                    numb      06
      SHARES  (average shares outstanding)             numb      08
      MARGIN  (sales margin)                           numb      07
      HIGH    (1988 high market price)                 numb      06
      LOW     (1988 low market price)                  numb      06
      HIGH EPS  (price/earnings ration of 89 high)     numb      06

                                 Total fields = 21
                             Total record length = 240


      Note:  Insurance  companies  do not report gross income in their press
      releases;  therefore,  we  have  substituted net profit before capital
      gains for annual sales in insurance company profiles.



















      Equipment Supplied                                         Page: 2
      FINDATA  CORPORATE  PROFILES  is delivered on a set of four diskettes.
      These  disks  are prepared in IBM PC DOS Version 3.2 format. The disks
      contain the following items:

             1. FINDATA1.DBF     FINDATA.DOC, READ.ME          
             2. FINDATA2.DBF
             3. FINDATA3.DBF
             4. FINDATA4.DBF, FINDATA.HDR, PCFILE+ .RPT (Report files)


      Note:  FINDATA  CORPORATE  PROFILES  are  in  dBASEIII format and can,
      therefore,  be  used  directly  with  that  system as well as with any
      system that can read dBASEIII formatted files.

      Hardware Requirements
      The  FINDATA  CORPORATE PROFILES run on an IBM XT or AT or compatible.
      the  system  requires  256K  RAM, and a fixed hard drive with at least
      1.75 megabytes of available space.

      Database Installation - on PC-FILE+
      The  data  on  the  FINDATA  disks  1,2,3, and 4 contain the CORPORATE
      PROFILES.  The information is structured in dBASEIII format, which can
      be  imported into the PC-FILE+ Header included on disk number 1, i.e.,
      Findata.hdr.  the FINDATA CORPORATE PROFILE data elements must be read
      into the PC-FILE+ file structure as follows:

              Create a directory on your hard drive for the Corporate Data.
               . Type MD\FINDATA
             . Copy all 5 FINDATA floppy disks to your hard drive.
               . Type CD\FINDATA
               . Type COPY A:*.*
               . Repeat the COPY command for the other 4 disks

      Importing the Corporate Profiles into the PC-FILE+ Structure
      The  PC-FILE+  header  (Findata.hdr)  on disk number 1 has been copied
      onto  your  hard  drive.  Next, you must import the Corporate Profiles
      into the PC-FILE+ header. This can be accomplished as follows:

             . Type PCF to execute PC-FILE+. PC-FILE+ will ask the
               following:
             . Which drive for the database?
               . Type C
             . Indicate and existing database or give a new database name.
               . Move the cursor to FINDATA and press (F10)
             . The PC-FILE+ main menu will be displayed as follows:
               F1 A - Add a new record
               F2 F - Find a record
               F8 U - Utilities











      FINDATA file import (cont.)                                 Page: 3

               . Press (F8) for the Utilities program and the following 
                 screen will appear.

             . C. Clone (change the database definition)
             . D. Duplicate records (find and list)
             . E. Export the current database
             . I. Import a PC-FILE+ database or other file
             . M. Maintenance - Copy, Delete or Rename a file
             . N. Name of field, mask, constant or calc
             . P. Profile files (set up configuration)
             . S. Smart Keys (modify)
             . U. Undelete records
             . Q. quit utilities return to main menu

               . Type I to import a database
             The system will ask:
             . PC-FILE+ database or other file (F/O)
               . Type O for other
             . Which drive contains the file to be imported (A-Z)
               . Type C for the C drive or hit enter
             . Which path? \FINDATA
               . Press enter or type a name if you have FINDATA on another
                 directory.
             . A list of files on your directory will appear.
               . Move the cursor (enter or arrow keys) to Findata1.dbf and
                 press (F10) and the following screen will appear.
             . B.  dBASE.DBF files
             . C. PC-CALC 
             . D. DIF (visicalc)
             . F. Fixed length
             . M. Mail merge (comma delimited)
             . T. Text editor (standard data format)

               . Type B for dBASE.DBF files
             . Import a dBASE11 of dBASEIII file (2/3)
               . Type 3
             . Append to existing data or overwrite existing data (A/O)
               . Type A to append Findata1.dbf to Findata.hdr
             . Import all records or selected records (A/S)
               . Type A for all records
      The system will show you the first record in findata1.dbf and ask
             . Import Y,N,X, or Q?
               . Type X for automatic import of all files
      The  above  procedure  will  create  a  FINDATA  database  file in the
      PC-FILE+ structure and name that database FINDATA.DTA.

      After  all  of the records from FINDATA1.DBF have been appended to the
      PC-FILE+  header, the system will say, Import complete. Press enter to
      return  to  the Utilities menu and type I to import a database. Repeat
      the   procedure  described  above  to  append  the  remaining  FINDATA
      databases    to    FINDATA.DTA    (Findata2.dbf,   Findata3.dbf,   and
      Findata4.dbf.






      Findata File Import (cont.)                                 Page: 4

      Note:    After  you  have  created the PC-FILE+ database file from the
      dBASEIII  file  Findata.dbf,  you  have  created  a  data  file called
      Findata.dta.  the remaining files must be appended to Findata.dta. the
      Findata  files  are  sorted alphabetically and will remain that way if
      they are appended in order.

      Finding a Corporate Profile
      The  FINDATA  CORPORATE  PROFILES  have  been loaded into the PC-FILE+
      structure  and  an  index  file has been automatically created for you
      called  FINDATA.INX.  Now  lets  see  if  you  can  display a selected
      record.  From  the  main menu press (F5) and the FIND selection screen
      will appear.

             . Simple search:
               . You fill in the blanks
             . Complex search:
               . You can type in a formula to FIND a Company
             : S (simple search), C (complex search), Q (quit)
               . Type S and the selection screen will appear
               . Type in the name of any company in the database in the
                 NAME field; for example ATLANTIC RICHFIELD, press (F10),
                 and a Corporate Profile will appear in about 2 seconds.

      Note:  All  character fields have been typed in upper case. Therefore,
      you  must  type in CAPITAL LETTERS the information necessary to FIND a
      Corporate  Profile.  Also,  all  of the files in each record have been
      indexed,  this  will allow you to search for selected companies in any
      of  the  fields  in  a  record.  For  example, you can FIND all of the
      companies in a selected SIC CODE.

      Creating and Producing Reports
      Reports can be created using the Main Menu REPORT command (F6).
      PC-FILE+  has  a very good report generator which lets the user design
      simple  reports  by just choosing the fields that the user wants to be
      printed  or  by  painting  complex  reports on the computer screen. We
      have designed two reports for you as follows:

             . BOOK.RPT - lists all of the fields in the database. This
               report is in the format of a reference book and can be used
               as a stock market reference book.
             . SALES.RPT - is a one line per company report which lists the
               following fields; COMPANY NAME, STATE, SIC CODE SALES,
               PROFIT and EARNINGS PER SHARE, for each company selected
               by the user.
             . PRICE.RPT - is a one line per company report which lists the
               following fields: Tick (Ticker symbol) NAME (Company Name)  
               HIGH (1988 High market price) LOW (1988 Low market price)   
               HIGH PER (1988 High Price/Earnings Ratio LOW PER (1988 Low  
               Price/Earnings Ratio.









      Producing Reports                                          Page: 5
      To  produce either of the above reports, from the Main Menu press (F6)
      and the following screen will appear:
             . Which report format? (leave Blank to CREATE or MODIFY a 
               format), type a name or number, or select with cursor keys.
               [1]  BOOK
               [2]  SALES
               [3[  PRICE
             . Move the cursor to BOOK and press (F10) to load the book 
               report. the following screen will appear.

                                    Report Menu

             .  Output  to  Printer,  screen,  or  Disk         PROFILES/S/D
      [PROFILES]
             . Number of copies                        1-9       [1]
             . Do detail lines                         Y/N       [N]
             . Do Subtotals                            Y/N       [N]
             . Left margin extra spaces                0-99     [04]
             . Page length (in lines)                           [66]
             . Type size (normal/compressed)           N/C       [C]
             . Remove blank lines and spaces           Y/N       [N]
             . Print all or Selected records           A/S       [S]

      Move  the  cursor and fill in the report screen as shown above and the
      BOOK  report  will  start  to  print.  Note:  the  BOOK  report  is in
      compressed  format.  Also,  the left margin is set to 4 spaces for use
      with  an  Epson  printer  to center the report. You may wish to change
      this margin to center the report on your printer.

      Press  (F10)  when the report menu is completed. Since you have chosen
      to  print  only  selected  records, the search screen will appear. The
      criteria  is the same here as in the FIND command. try a simple search
      such  as  under the field NAME type ATLANTIC. This will produce a BOOK
      report with all company names starting with the NAME ATLANTIC.

      To  produce  the  SALES  report,  follow  the procedure above with the
      following changes:

             . Move the cursor to SALES and press (F10)
             . Select the normal (N) type size for the SALES report

      Creating Labels
      The  PC-FILE+  report  Generator  can  also  be  programmed to produce
      mailing  labels.  This  can  easily  be  done  through  the use of the
      Freeform  command  in the report (F6) selection from the main menu. We
      have  produced  a label program for you that develops 1 up labels. The
      labels produced by this program will appear as the one shown below:

               ROBERT E. WYCOFF
               ATLANTIC RICHFIELD COMPANY
               515 SOUTH FLOWER STREET
               LOS ANGELES , CA 90071







      Mailing labels (cont.)                                      Page: 6

      To  produce  a  set of selected mailing labels, use the procedure that
      was  outlined  above  for  printing the BOOK report with the following
      changes:

             . Left Margin (set to preference)         [0]
             . Remove Blank Lines                      [Y]
             . Type size (normal/compressed)           [N]

      Note:  This  program  is  designed to print on 1-1/2 by 4 inch mailing
      labels.  this  requires 6 blank lines after each label. If you wish to
      produce  smaller  labels,  it  will  be  necessary to modify the label
      program as follows:

             . From the Main Menu:
               . Press (F6) Reports
             . A list of previously designed reports will appear
               . press (F10) on the BLANK report to MODIFY a report
             . The next screen will give you a choice of report types
               . Type C for commands
               . Press Enter to EDIT a program
               . Move the cursor to LABEL and press (F10)
             . The LABEL program will appear
               . Move the cursor down to the last detail line, i.e. /6.
                 This instructs the program to skip (/) six (6) spaces.
               . Change the number 6 to skip less spaces to correspond with
                 your smaller labels and press (F10)


      FINDATA CORPORATE PROFILES - Purchasing quarterly updates
      The  FINDATA  CORPORATE  PROFILES  are updated daily. Complete updated
      CORPORATE  PROFILES are available each quarter, i.e., month end March,
      June,  September  and  December. The updates can be purchased directly
      from   COMP   U   PRINT   COMPANY   for   $50  per  quarterly  update.























```
{% endraw %}

## GO.TXT

{% raw %}
```
╔═════════════════════════════════════════════════════════════════════════╗
║    Disk No 1051 THE FINDATA CORPORATE PROFILE DATABASE (Disk 1 of 2)    ║
╠═════════════════════════════════════════════════════════════════════════╣
║ To copy the documentation to your printer, insert disk number 1052 into ║
║ drive A: and type MANUAL (press enter)                                  ║
║                                                                         ║
║ To install the program on a floppy disk system, type: FLOP (press enter)║
║                                                                         ║
║ To install the program on a hard disk system, type: HARD (press enter)  ║
║                                                                         ║
║ PLEAS NOTE: You must have a copy of either PC-FILE+ or dBASE III        ║
║ in order to look thru these database files.                             ║
╚═════════════════════════════════════════════════════════════════════════╝
```
{% endraw %}

{% comment %}samples_end{% endcomment %}

### Directory of PC-SIG Library Disk #1051

     Volume in drive A has no label
     Directory of A:\

    FILE1051 TXT      1563   9-08-89   8:52a
    FINDATA  ARC    312601   9-05-89   8:50a
    FLOP     BAT       948   5-26-88  12:35p
    GO       BAT        38  10-19-87   3:56p
    GO       TXT      1002   3-09-89  11:20a
    HARD     BAT       372   5-26-88  12:37p
    MANUAL   BAT       126   5-26-88   2:14p
    PKXARC   COM     12242   4-27-87
            8 file(s)     328892 bytes
                           29696 bytes free