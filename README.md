# CBT244
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 244 IS FROM PHILIP PECKSEN OF NFU MUTUAL INSURANCE IN     *   FILE 244
//*           STRATFORD UPON AVON, ENGLAND.  THIS FILE COMES FROM   *   FILE 244
//*           A TAPE BEING MADE AVAILABLE TO UK G.U.I.D.E.          *   FILE 244
//*           MEMBERS.  THIS PARTICULAR FILE HAS NEWER MATERIALS,   *   FILE 244
//*           AND IS AN ADDENDUM TO THE OLD UK G.U.I.D.E. TAPE      *   FILE 244
//*           FILE.                                                 *   FILE 244
//*                                                                 *   FILE 244
//*           THE OLD UK G.U.I.D.E. GOODIES FILE IS TOO LONG AND    *   FILE 244
//*           TOO OLD (IN MY OPINION) TO BE INCLUDED AT THIS TIME   *   FILE 244
//*           ON THE CBT TAPE.  THE MATERIALS FROM THAT TAPE ARE    *   FILE 244
//*           CURRENTLY INCLUDED IN THE CBT OVERFLOW TAPE.          *   FILE 244
//*                                                                 *   FILE 244
//*            ADDRESS:   PHILIP PECKSEN                            *   FILE 244
//*                       NFU MUTUAL INSURANCE                      *   FILE 244
//*                       TIDDINGTON ROAD                           *   FILE 244
//*                       STRATFORD UPON AVON                       *   FILE 244
//*                       WARKS CV37 7BJ                            *   FILE 244
//*                       ENGLAND                                   *   FILE 244
//*                                                                 *   FILE 244
//*            EMAIL:     PHILIP_PECKSEN@NFUMUTUAL.CO.UK            *   FILE 244
//*                                                                 *   FILE 244
//*            TELEPHONE:  +44-1-789-202111                         *   FILE 244
//*                                                                 *   FILE 244
//*                  GUIDE GOODIES      1993 'A'                    *   FILE 244
//*                  =============      ========                    *   FILE 244
//*                                                                 *   FILE 244
//*   THIS DATASET HAS BEEN BUILT UP FROM SEVERAL CONTRIBUTIONS     *   FILE 244
//*   COLLECTED OVER THE LAST FEW MONTHS TO FORM THE FIRST CUT OF   *   FILE 244
//*   A NEW GOODIES FILE.                                           *   FILE 244
//*                                                                 *   FILE 244
//*   WHERE MEMBER NAMES HAVE NOT CONFORMED TO THE REQUESTED        *   FILE 244
//*   FORMAT THE FIRST THREE CHARACTERS IN MOST CASES HAVE BEEN     *   FILE 244
//*   CHANGED TO 'ANN' SO BEWARE IF COMPILING PROGRAMS AS MEMBER    *   FILE 244
//*   NAMES WILL NEED ADJUSTING TO WHAT THE PROGRAM EXPECTS.  -     *   FILE 244
//*   SORRY BUT ITS THE ONLY WAY TO KEEP THE TAPE IN A SENSIBLE     *   FILE 244
//*   FORMAT.                                                       *   FILE 244
//*                                                                 *   FILE 244
//*   EACH COMPANY CONTRIBUTION HAS AN INDIVIDUAL 3 CHARACTER       *   FILE 244
//*   PREFIX AND AN INDEX MEMBER.  TO HELP EVALUATE THE DATASET     *   FILE 244
//*   ALL OF THE INDEX MEMBERS ARE COPIED INTO THIS MEMBER AS       *   FILE 244
//*   WELL.                                                         *   FILE 244
//*                                                                 *   FILE 244
//*   GOOD LUCK  --    PHILIP PECKSEN         SEPT 1993             *   FILE 244
//*                                                                 *   FILE 244
//*  -------------------------------------------------------------  *   FILE 244
//*    A01XXXXX          GOODIES DOCUMENTATION                      *   FILE 244
//*    --------          ---------------------                      *   FILE 244
//*    CONTRIBUTED  BY    DAVE THORBY                               *   FILE 244
//*                       LONDON ELECTRICITY                        *   FILE 244
//*                       +44-1-71-232 3045                         *   FILE 244
//*  -------------------------------------------------------------  *   FILE 244
//*                                                                 *   FILE 244
//*    A01CHECK         CHECKS IF A SPECIFIED JOB IS STILL RUNNING  *   FILE 244
//*    A01ENQ           TSO C.P. TO DISPLAY ENQUEUES                *   FILE 244
//*    A01INMRZ         I.D.T.F. RECEIVE PRE-PROCESSOR TO CHECK     *   FILE 244
//*                     FOR MIGRATED LOG D/S                        *   FILE 244
//*    A01IPLVO         TSO C.P. TO DISPLAY CURRENT IPL VOLUME      *   FILE 244
//*    A01IPLNV         DELETE DATA SETS CATALOGUED TO VOLUMES      *   FILE 244
//*                     WHICH NO LONGER EXIST                       *   FILE 244
//*    A01DSNWT         WAITS FOR A DATA SET TO BECOME AVAILABLE    *   FILE 244
//*                     WITHOUT RESERVING IT                        *   FILE 244
//*    A01CALL          TSO C.P. TO CALL A PROGRAM FROM THE         *   FILE 244
//*                     LINKLIST                                    *   FILE 244
//*    A01MOVIE         ISPF MOVING PICTURES  E.G. XMAS LOGON       *   FILE 244
//*                     MESSAGE                                     *   FILE 244
//*    A01TAPE          TAPE SCAN PROGRAM                           *   FILE 244
//*    A01EXTNT         ADD SECONDARY EXTENTS, CHANGE BLOCKSIZE,    *   FILE 244
//*                     REALLOCATE IN TRACKS                        *   FILE 244
//*    A01FREE          GET FREE SPACE FOR ALL ONLINE DASD          *   FILE 244
//*    A01GETAC         GET TSO USER'S CURRENT ACCOUNT CODE INTO    *   FILE 244
//*                     CLIST VARIABLE                              *   FILE 244
//*    A01HSMNC         CHECK DFHSM MCDS FOR UNCATALOGUED           *   FILE 244
//*                     MIGRATED DATA SETS                          *   FILE 244
//*    A01LIST          AVOID TSO ABEND S806 FOR                    *   FILE 244
//*                     LIST/ASM/CALC/COBOL/FORT/COPY/MERGE         *   FILE 244
//*    A01P0100         ISPF BASED IBM MANUAL MANAGEMENT PROGRAM    *   FILE 244
//*    A01PC100                "    INVOCATION CLIST                *   FILE 244
//*    A01PM00                 "    MESSAGE MEMBER                  *   FILE 244
//*    A01PM01                 "    MESSAGE MEMBER                  *   FILE 244
//*    A01PM02                 "    MESSAGE MEMBER                  *   FILE 244
//*    A01PM03                 "    MESSAGE MEMBER                  *   FILE 244
//*    A01PM04                 "    MESSAGE MEMBER                  *   FILE 244
//*    A01PM09                 "    MESSAGE MEMBER                  *   FILE 244
//*    A01PP010                "    PANEL                           *   FILE 244
//*    A01PP020                "    PANEL                           *   FILE 244
//*    A01PP030                "    PANEL                           *   FILE 244
//*    A01PP040                "    PANEL                           *   FILE 244
//*    A01PP050                "    PANEL                           *   FILE 244
//*    A01PP060                "    PANEL                           *   FILE 244
//*    A01PP070                "    PANEL                           *   FILE 244
//*    A01PP080                "    PANEL                           *   FILE 244
//*    A01PP090                "    PANEL                           *   FILE 244
//*    A01PP100                "    PANEL                           *   FILE 244
//*    A01PP110                "    PANEL                           *   FILE 244
//*    A01PP120                "    PANEL                           *   FILE 244
//*    A01PP130                "    PANEL                           *   FILE 244
//*    A01PP140                "    PANEL                           *   FILE 244
//*    A01PH010                "    TUTORIAL                        *   FILE 244
//*    A01PH020                "    TUTORIAL                        *   FILE 244
//*    A01PH030                "    TUTORIAL                        *   FILE 244
//*    A01PH040                "    TUTORIAL                        *   FILE 244
//*    A01PH050                "    TUTORIAL                        *   FILE 244
//*    A01PH060                "    TUTORIAL                        *   FILE 244
//*    A01PH070                "    TUTORIAL                        *   FILE 244
//*    A01PH080                "    TUTORIAL                        *   FILE 244
//*    A01PH090                "    TUTORIAL                        *   FILE 244
//*    A01PH100                "    TUTORIAL                        *   FILE 244
//*    A01PH101                "    TUTORIAL                        *   FILE 244
//*    A01PH110                "    TUTORIAL                        *   FILE 244
//*    A01PH120                "    TUTORIAL                        *   FILE 244
//*    A01PH130                "    TUTORIAL                        *   FILE 244
//*    A01P0200                "    FILE LISTING PROGRAM            *   FILE 244
//*    A01LOGOF         LOGOFF TSO FROM ISPF MAIN MENU              *   FILE 244
//*    A01SKEOF         RECOVER DATA FROM BEYOND END OF FILE        *   FILE 244
//*                     MARKS ON DASD                               *   FILE 244
//*    A01SMF           SCAN SMF FOR SELECTED RECORD TYPES          *   FILE 244
//*    A01SCAN          SCAN RECFM=VS/VBS DATA SETS FOR MISSING     *   FILE 244
//*                     SEGMENTS                                    *   FILE 244
//*    A01VERFY         ENSURE ALL VSAM DATA SETS ON A DISK ARE     *   FILE 244
//*                     PROPERLY CLOSED                             *   FILE 244
//*    A01PAGEL         DISPLAY LIST OF PAGE + SWAP DATA SETS       *   FILE 244
//*    A01RACXT         DISPLAY SPECIFIED USER'S DEFAULT RACF       *   FILE 244
//*                     GROUP + USER NAME                           *   FILE 244
//*    A01RCORE         REALTIME REPORT ON REAL STORAGE FRAMES      *   FILE 244
//*                     USED (C/F RMF)                              *   FILE 244
//*    A01VRGRP         SET CLIST VARIABLE TO CURRENT RACF          *   FILE 244
//*                     CONNECT GROUP                               *   FILE 244
//*    A01UT01          CREATE CONTROL CARD(S) FROM PARM            *   FILE 244
//*    A01WAIT          TSO C.P. TO WAIT A SPECIFIED LENGTH OF      *   FILE 244
//*                     TIME                                        *   FILE 244
//*    A01ZDOW          ISPF CLIST TO GET DAY OF WEEK               *   FILE 244
//*                                                                 *   FILE 244
//*  -------------------------------------------------------------  *   FILE 244
//*    A02XXXXX          GOODIES DOCUMENTATION                      *   FILE 244
//*    --------          ---------------------                      *   FILE 244
//*    CONTRIBUTED  BY    --                                        *   FILE 244
//*                            MIKE TEALE                           *   FILE 244
//*                            L.O.L.A.                             *   FILE 244
//*                            +44-1-81-366 6611 X285               *   FILE 244
//*  -------------------------------------------------------------  *   FILE 244
//*                                                                 *   FILE 244
//*    THIS LIBRARY CONTAINS THE FOLLOWING GOODIES:-                *   FILE 244
//*                                                                 *   FILE 244
//*     1. AN EDIT MACRO CALLED ZOOM WHICH WILL DISPLAY A JCL       *   FILE 244
//*        PROCEDURE WHILE EDITING JCL. THE CURSOR IS PLACED ON     *   FILE 244
//*        AN EXEC STATEMENT IN YOUR JOB AND THE ZOOM COMMAND       *   FILE 244
//*        ENTERED. THE JCL PROC WILL BE DISPLAYED VIA A BROWSE     *   FILE 244
//*        PANEL.                                                   *   FILE 244
//*                                                                 *   FILE 244
//*        MEMBER NAMES:   A02ZOOM                                  *   FILE 244
//*                                                                 *   FILE 244
//*     2. AN EDIT MACRO CALLED JOBC WHICH WILL GENERATE A JOB      *   FILE 244
//*        CARD.  THIS MACRO DISPLAYS AN ENTRY PANEL AND IS         *   FILE 244
//*        DOCUMENTED VIA TUTORIAL PANELS. THE JOB STANDARD IS      *   FILE 244
//*        FOR L.O.L.A.'S  SET UP BUT CAN BE CHANGED.               *   FILE 244
//*                                                                 *   FILE 244
//*        MEMBER NAMES:   JOBC,A02N021,A02N0211  -  EDIT MACROS    *   FILE 244
//*                        A02N021                -  ENTRY PANEL    *   FILE 244
//*                        A02MGN02               -  MESSAGES       *   FILE 244
//*                        A02N....               -  HELP PANELS    *   FILE 244
//*                                                                 *   FILE 244
//*     3. A PROGRAM CALLED Z7504 THAT WILL CONVERT AWKWARD         *   FILE 244
//*        CHARACTERS SUCH AS AMPERSANDS AND BRACKETS IN CLIST      *   FILE 244
//*        VARIABLES TO OTHER CHARACTERS SO THAT THE CLIST CAN      *   FILE 244
//*        COMPLETE NORMALLY. THIS WAS WRITTEN TO CATER FOR THE     *   FILE 244
//*        SITUATION WHERE SOMEONE ENTERS AN AMPERSAND IN AN ISPF   *   FILE 244
//*        PANEL VARIABLE AND WHEN THE CLIST TRIES TO DO ANYTHING   *   FILE 244
//*        WITH THE VARIABLE IT BLOWS UP.                           *   FILE 244
//*                                                                 *   FILE 244
//*        MEMBER NAMES:   A02Z7504           -  PROGRAM            *   FILE 244
//*                        A02SETUP,A02CLEAR  -  MACROS             *   FILE 244
//*                        A0JVARS            -  JCL TO             *   FILE 244
//*                                              ASSEMBLE/LINK      *   FILE 244
//*                                                                 *   FILE 244
//*     4. A PROGRAM CALLED Z3426 - A CPU SOAK PROGRAM TO MANAGE    *   FILE 244
//*        CPU RESOURCE. THIS PROGRAM AS IT STANDS REQUIRES ACF2    *   FILE 244
//*        BUT COULD BE CHANGED IF ACF2 IS NOT YOUR SECURITY        *   FILE 244
//*        PRODUCT.                                                 *   FILE 244
//*                                                                 *   FILE 244
//*        MEMBER NAMES:   A02Z3426           -  PROGRAM            *   FILE 244
//*                        A02SETUP,A02CLEAR  -  MACROS             *   FILE 244
//*                                       ALSO USES ACF2 MACROS     *   FILE 244
//*                        A02SOAK            -  JCL TO             *   FILE 244
//*                                              ASSEMBLE/LINK      *   FILE 244
//*                                                                 *   FILE 244
//*  -------------------------------------------------------------  *   FILE 244
//*    A03XXXXX          GOODIES DOCUMENTATION                      *   FILE 244
//*    --------          ---------------------                      *   FILE 244
//*    CONTRIBUTED  BY    DERBYSHIRE COUNTY COUNCIL                 *   FILE 244
//*                       C HAMPSHIRE                               *   FILE 244
//*                       +44-1-629 580000 X7764                    *   FILE 244
//*  -------------------------------------------------------------  *   FILE 244
//*                                                                 *   FILE 244
//*      NAME    -                     DESCRIPTION                  *   FILE 244
//*  ============================================================== *   FILE 244
//*    A03APSX1  -  LASER PRINTER HEADER-SEPARATOR PAGE.            *   FILE 244
//*    A03LPA01  -  SYS1.PARMLIB FOR IEFUJV/IKJEFLD                 *   FILE 244
//*    A03UJV    -  SMF EXIT IEFUJV (JOB CARD VALIDATION)           *   FILE 244
//*    A03UJVRR  -  REFRESH ROUTINE FOR SMF EXIT IEFUJV             *   FILE 244
//*    A03EFLD   -  IKJEFLD TSO LOGON EXIT                          *   FILE 244
//*    A03ITERM  -  FIND TERMINAL ID IN ISPF                        *   FILE 244
//*    A03X023   -  JES USER EXIT 023. - PREPARE OUTPUT FOR         *   FILE 244
//*                 LASER PRINTER                                   *   FILE 244
//*                                                                 *   FILE 244
//*    A03LLOW   -  ENSURES JOBS RUN IN CORRECT COMBINATION.        *   FILE 244
//*    A03LLOWP  -  UTALLOW DOCUMENTATION                           *   FILE 244
//*    A03LLOWR  -  JCL TO RUN UTALLOW.                             *   FILE 244
//*                                                                 *   FILE 244
//*  -------------------------------------------------------------  *   FILE 244
//*   A04XXXXX          GOODIES DOCUMENTATION                       *   FILE 244
//*   --------          ---------------------                       *   FILE 244
//*   CONTRIBUTED  BY    NICK VARLEY                                *   FILE 244
//*                      GE CAPITAL                                 *   FILE 244
//*                      +44-1-272 353555                           *   FILE 244
//*  -------------------------------------------------------------  *   FILE 244
//*                                                                 *   FILE 244
//*    A04VTOC          VTOC FIX FOR DFP V3 TO PREVENT PDS/E        *   FILE 244
//*                     FORMAT ASSUMED                              *   FILE 244
//*                                                                 *   FILE 244
//*  -------------------------------------------------------------  *   FILE 244
//*   A05XXXXX          GOODIES DOCUMENTATION                       *   FILE 244
//*   --------          ---------------------                       *   FILE 244
//*   CONTRIBUTED  BY    PAUL VOYNER                                *   FILE 244
//*                      WHITBREAD                                  *   FILE 244
//*                      +44-1-734 581166                           *   FILE 244
//*   ------------------------------------------------------------  *   FILE 244
//*                                                                 *   FILE 244
//*      REXX UTILITY TO CALL DISPLAY OF SYSTEM INFO (LAST          *   FILE 244
//*      IPL, MVS VERSION FMID CPU ID'S, AFP LIBS AND LINK LIST     *   FILE 244
//*                                                                 *   FILE 244
//*     A05DATEC    DATE CONVERSION ROUTINE                         *   FILE 244
//*     A05IPL      INVOCATION ROUTINE                              *   FILE 244
//*     A0505SYS    REXX                                            *   FILE 244
//*     A0505P001   PANEL DEF                                       *   FILE 244
//*                                                                 *   FILE 244
//*  -------------------------------------------------------------  *   FILE 244
//*    A06XXXXX          GOODIES DOCUMENTATION                      *   FILE 244
//*    --------          ---------------------                      *   FILE 244
//*    CONTRIBUTED  BY    BERNIE ROYLE                              *   FILE 244
//*                       WOOLWORTHS                                *   FILE 244
//*                       ROCHDALE 47301                            *   FILE 244
//*  -------------------------------------------------------------  *   FILE 244
//*                                                                 *   FILE 244
//*     A06DOCMS MEMBER EXPLAINING HOW TO RUN WHO DELETED DATASET   *   FILE 244
//*              REPORT PROGRAM.                                    *   FILE 244
//*                                                                 *   FILE 244
//*     A06CLOCK GENERAL PURPOSE DATE AND TIME PROGRAM USED IN      *   FILE 244
//*              DELETE REPROT PROGRAM.                             *   FILE 244
//*                                                                 *   FILE 244
//*     A06DELRP DELETED DATASET REPORT PROGRAM.                    *   FILE 244
//*                                                                 *   FILE 244
//*  -------------------------------------------------------------  *   FILE 244
//*    A07XXXXX          GOODIES DOCUMENTATION                      *   FILE 244
//*    --------          ---------------------                      *   FILE 244
//*    CONTRIBUTED  BY    KEVIN FERGESON                            *   FILE 244
//*                       CLEVELAND COUNTY COUNCIL                  *   FILE 244
//*                       +44-1-642 26310                           *   FILE 244
//*  -------------------------------------------------------------  *   FILE 244
//*                                                                 *   FILE 244
//*     A07BROWS    BROWSE                                          *   FILE 244
//*     A07CLSCR    CLEARSCR     CLEAR THE VDU SCREEN               *   FILE 244
//*     A07DATE     DATE TRANSLATE ROUTINE                          *   FILE 244
//*     A07DAY      TELL USER WHAT DAY A DATE WAS                   *   FILE 244
//*     A07EOJ      EOJ                                             *   FILE 244
//*     A07701DX    IEC701DX  CHANGE CONSOLE IDENTIFIER OF THE      *   FILE 244
//*                 TAPE MESSAGE                                    *   FILE 244
//*     A07176IX    IEF176IX  ISSUE STOP TO EXTERNAL WRITER         *   FILE 244
//*     A07000IX    IOS000IX  MAKE IOS000I A NON DELETE MESSAGE     *   FILE 244
//*                 FOR DASD                                        *   FILE 244
//*     A07REGEQ    REGISTER EQUATES                                *   FILE 244
//*     A07SV255    SVC255                                          *   FILE 244
//*     A07UTCPY    FRONT END FOR IEBCOPY                           *   FILE 244
//*     A07ZAP1     ALLOWS IPOUPDTE TO RUN AGAINST ANY PDS          *   FILE 244
//*     A07ZAP1A    ALLOWS CPPUPDTE TO RUN AGAINST ANY PDS          *   FILE 244
//*     A07ZAP2     MAKES IEBPTPCH PRINT ALPABETICALLY              *   FILE 244
//*     A07ZAP3     MAKES IEBPTPCH PRINT ALPABETICALLY -            *   FILE 244
//*                 OTHER RELEASES                                  *   FILE 244
//*     A07ZAP4     STOPS AN EXTERNAL WRITER AT 'WAITING FOR WORK'  *   FILE 244
//*     A07ZAP4     STOPS AN EXTERNAL WRITER AT 'WAITING FOR WORK'  *   FILE 244
//*                 MORE RELEASES                                   *   FILE 244
//*                                                                 *   FILE 244
//*     SMFSCAN CONSISTS OF THE FOLLOWING PROGRAMS :-               *   FILE 244
//*                                                                 *   FILE 244
//*     A07PARSE   SMFPARSE - PARSES SYSIN INPUT. THIS PROGRAM      *   FILE 244
//*                           IS THE MAIN ENTRY POINT. IT CALLS     *   FILE 244
//*                           SMFSCANT TO PRINT TITLES THEN IT      *   FILE 244
//*                           VALIDATES THE SYSIN DATA STREAM       *   FILE 244
//*                           AND THEN (IF ALL IS OK) LINKS TO      *   FILE 244
//*                           SMFSCANR.                             *   FILE 244
//*                                                                 *   FILE 244
//*     A07SCANT   SMFSCANT - PRINTS THE TITLE PAGES FOR SMFSCAN.   *   FILE 244
//*                           THIS PROGRAM WILL PRINT THE TITLE     *   FILE 244
//*                           DEPENDING AT WHAT STAGE THE PROGRAM   *   FILE 244
//*                           HAS GOT. IE SYSIN REPORT OR REPORT.   *   FILE 244
//*                           THIS PROGRAM LINKS TO DATE.           *   FILE 244
//*                                                                 *   FILE 244
//*     A07SCANR   SMFSCANR - PROCESS THE INPUT FILE AND PRODUCES   *   FILE 244
//*                           THE REPORT.  THIS PROGRAM ALSO LINKS  *   FILE 244
//*                           TO SMFSCANT AND DATE.                 *   FILE 244
//*                                                                 *   FILE 244
//*     SMFSCAN WILL PRODUCE A REPORT, FROM SMF TYPE 30 RECORDS,    *   FILE 244
//*     OF WHATEVER IS SPECIFIED IN THE SYSIN DATA STREAM.  USER    *   FILE 244
//*     INSTRUCTIONS ARE HELD IN THIS PDS AS MEMBER A07SMDOC.       *   FILE 244
//*                                                                 *   FILE 244
```
