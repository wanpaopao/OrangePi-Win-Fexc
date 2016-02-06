The script.bin file can usually be found in the main directory of a microSD card prepared with official Debian image. The folder containing the script can be inspected under both Windows and Linux.

This tool is compiled for Windows. It is tested under Windows 7 x86. 

How to convert bin to fex or fex to bin:

1.Place your script.bin or script.fex file inside the folder where fexc.exe, FEX2BIN.BAT and BIN2FEX.BAT are located. It is important that the file you are going to convert to fex is named script.bin (if you are aiming for bin -> fex conversation else you would need to edit the BIN2FEX.BAT file). It is important that the file you are going to convert to bin is named script.fex (if you are aiming for bin -> fex conversation else you would need to edit the FEX2BIN.BAT file).

2. Run either BIN2FEX.BAT or FEX2BIN.BAT - which, respectively, convert BIN -> FEX and FEX -> BIN

3. The output file would show up in the same folder.

sunxi-fexc

Usage: ./sunxi-fexc [-vq] [-I <infmt>] [-O <outfmt>] [<input> [<output>]]

infmt:  fex, bin  (default:fex)
outfmt: fex, bin, uboot  (default:bin)
