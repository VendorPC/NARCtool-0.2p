narctool 0.2-p rebooted - modified by FrankieD, Vendor, and Zekromaegis

Simplified scripts were created for quicker use

Extract.py
All files ending in ".narc" will be extracted
Place your NARC(s) in this folder and run "Extract.py"
A new folder will appear named after the NARC(s) you extracted followed by "_extracted"

Compile.py
All folders ending with "_extracted" will be compiled
After running Compile.py your compiled NARC(s) will appear in the same folder your NARC(s) were extracted to

Although they are very rarely used I included Compress/Decompress variants of the above scripts

Should either script not function as expected run NARCTool.py in Windows CMD or a CMD equivalent

--------------

narctool 0.1-p

This modified version of narctool has been made so that it works with
filename-less NARC files like those in Pokemon Diamond and Pearl by
creating files named (narc_name).(file_number).(file_type)

Refer to the original readme, below:

--------------

narctool 0.1 - by natrium42

Tool for working with NARC and compressed NARC files (CARC files).
See narc.h for description of NARC file format.

Run without arguments for help.


Parts of code use work by Haruhiko Okumura and Andre Perrot,
