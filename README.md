# sfz
A collection of instruments in the [SFZ format](https://sfzformat.com). 

* Tested in [sforzando player](https://www.plogue.com/products/sforzando.html) and [sfizz](https://sfz.tools/sfizz/) on MacOS, and [isfizz](https://www.kiraqtech.jp/blog/isfizz-en/) on iOS/iPadOS.
* The sfz files are my own creation. They may be freely used, distributed, and modified with or without attribution.
* If included, included samples are permitted under the sample's license agreement. Re-distribution beyond that is subject to the license agreement included with the sample set.
* If not included, the README file for each sfz for should indicate where to download the samples.
* Convention for these files is to keep all samples in a subdirectory `samples` and including any subdirectory scheme of the sample source below there.
  Examples:
  * A download with all files in a single directory would have all files in the `samples` folder.
  * A download with files in directories `BD`, `SD`, `CH`, etc. would have those subdirectores below the `samples` folder.
  * Each sfz file should begin with a `default_path=samples/` line for easily changing sample locations if you don't prefer this structure.
* Most files should have a section near the top for MIDI Note mapping for each sound.
  * Drum instruments here are mapped to the General Midi (GM) Drum map.
* I've avoided use of include files in most cases. While I prefer the better organization and portability of include files, I've wanted to keep the file structure as simple as possible for those who aren't familiar with such schemas. For instance, in sfizz/isfizz you can edit a top-level sfz file that is loaded, but wouldn't easily be able to edit other files without an external editor. On iOS that would be somewhat involved for a non technical user.
  This also tries to minimize the chance of opening a sub-file that wouldn't work as a standalone instrument.
