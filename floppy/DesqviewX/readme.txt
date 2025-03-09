Serial: 000-06X-00009

Run INSTALL from the A: prompt with DISK1 in your A drive.

Select the ADVANCED install, then PARTIAL install so you can "Just Say NO"
when you are asked to install the QEMM 7.5 that shipped with DV/X v2.1; use
v8.03 (or v9 if you can find it) instead.

Do NOT use DOS=HIGH.  Don't waste your time trying to run DV/X without
ST:M
on your QEMM386.SYS device line.  Set FILES=45 or higher; multiple DV
windows eat up those handles.  STACKS=0,0 is usually your best bet.

Look for .QIP files in SERVER\FONTS\*; these are optional fonts.  Disk 2
contains NEWMISC.QIP which contains more SNF fonts.  If you want these, run
from your new DVX directory:
COPY A:NEWMISC.QIP
QUNPACK NEWMISC.QIP
