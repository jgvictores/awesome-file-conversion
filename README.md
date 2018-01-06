# awesome-file-conversion
Curated list of awesome open-source tools for converting between file formats.

All tools with command-line capabilities, which does not exclude GUI capabilities, are marked via `[CLI]`.

## Documents, presentations and spreadsheets
- [libreoffice](https://www.libreoffice.org) - Support for `.odt`,`.odp`,`.ods` and [other formats] (https://help.libreoffice.org/Common/XML_File_Formats), and export/import to `.pdf` (however, if available, out-of-scope Word import of `.pdf` is worth a try).
- [ods2md](https://github.com/kennytm/ods2md) `[CLI]` - `ods2md.py input_file.ods > output_file.md`

## Images (Pictures)
- [gimp](https://www.gimp.org) - Large support of different bitmap formats: `.bmp`,`.jpg`,`.png`,`.tif` ... - GUI usage: Open, then `Shift+Ctrl+E` or `File`->`Export as...` (format will be given by extension, not dropdown selection).
- [imagemagick](https://www.imagemagick.org) `[CLI]` - `magick image.jpg image.png` according to [official documentation](http://www.imagemagick.org/script/command-line-processing.php), but in Ubuntu use commands from [graphicsmagick-imagemagick-compat](https://packages.ubuntu.com/xenial/all/graphicsmagick-imagemagick-compat/filelist): `convert image.jpg image.png`
- [inkscape](https://inkscape.org) - Large support of different vector formats: `.svg`,`.emf`...

## Multimedia (Audio and Video)
- [lame](https://man.cx/lame(1)) `[CLI]` - `lame sample.wav sample.mp3`
- [timidity](https://man.cx/timidity(1)) `[CLI]` - `timidity -Ow name.mid`
- [tuxguitar](https://sourceforge.net/projects/tuxguitar) - Support for `.gp5`,`.tuxguitar`, and exports to `.ly`,`.midi`,`.xml`...
- [vlc](https://www.videolan.org) - Converts between audio and video formats, even video to audio. Large support of different formats: `.acc`,`.mp3`,`.mp4`... - GUI usage: click on `Media`->`Convert / Save...`.
