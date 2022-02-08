# yaWERTY
 Russian ЯВЕРТЫ layout for Windows.

## Building the installer
First, set up the build environment (has to be performed once):
1. Download and extract the LZMA SDK from [here](https://www.7-zip.org/a/lzma1900.7z).
2. Copy `bin/7zSD.sfx` to this folder.

Then, build:
1. Build the layout in MS KLC.
2. Copy the resulting "ruyawert" folder here.
3. Compress **the contents** of the folder into a 7-Zip archive named `ruyawert.7z` and place it in the `ruyawert` folder. **If you compress the folder you will get a "File is corrupt" error when attempting to install the keyboard**
4. Run `build.bat`.
