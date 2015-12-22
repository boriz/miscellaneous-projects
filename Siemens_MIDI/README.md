Generate sound datablock:

Step 1.
Convert midi to simplified format (note on, note off, delay): https://github.com/LenShustek/miditones
miditonesV1.6.exe

Step 2.
Massage output file to make it excel-friendly

Step 3.
Use MIDI.xlsx to convert text file to be S7 datablock source format

Step 4.
Copy from excel to TIA Portal (in DB source). Compile, download, enjoy.
