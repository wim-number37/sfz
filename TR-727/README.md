# Roland TR-626 Rhythm Composer SFZ
Soundfont instrument for use with the free TR-626 samples available as of this writing at http://machines.hyperreal.org/manufacturers/Roland/TR-626/. See tr-626.txt for info about the origin of the files.

* Samples are expected in a samples folder below the one containing the sfz file. If the samples are elsewhere, edit or remove the default_path at the top of the file. The path must be relative to the location of the sfz file and must contain the / at the end.
* Notes are mapped to the General Midi (GM) Drum map. Note numbers can be edited to taste in the section at the beginning of the file. 
* TR-626.sfz outputs everything to a single stereo pair.
* TR-626-multi.sfz adds multiple outputs which are customizable in the file. The default mappings follow the somewhat odd polyphony/output groups in the original TR-626 for nostalgia sake. These may not be the most practical. Edit to taste.
* There is a "key switch" to select between the **Snare 1** and **Snare 2** sounds for the Snare1/2 key mapping. MIDI note 24 selects Snare 1, note 26 selects Snare2. This is done because there are only two available snare key mappings in the GM Drum map. The other key mapping is used for Snare 3.
* The 626 has volume level and tuning controls for each sound. Tuning can be adjusted +/- 7 semitones.
* Panning controls have been added for convenience.
* In theory multiple output sfz's should operate in single output players, which should ignore output numbers other than 0. In practice I've found that not always to be the case.
* The LO BONGO.WAV file in the origional has a delay in it due to silence at the start of the file. The samples.zip version here has been fixed to remove the silence.
 

