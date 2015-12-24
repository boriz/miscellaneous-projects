<h1> Generate midi/tune datablock: </h1>

Step 1.
Convert midi to simplified format (note on, note off, delay). Using tool from https://github.com/LenShustek/miditones
miditonesV1.6.exe

Step 2.
Massage output file to make it excel-friendly

Step 3.
Use MIDI.xlsx to convert text file to S7 datablock source format

Step 4.
Copy from excel to TIA Portal (DB source). Compile, download, enjoy.
