# About ciconia-pt-br
This repository is meant to be used to translate Ciconia Phase 1 and sequels from English to Brazilian Portuguese.

# About the patch
To install, download the latest release on the [Releases](https://github.com/JesterThirty4/ciconia-pt-br/releases) page. More instructions on how to install are inside Ciconia PT_BR.rar

# Repository structure

- The folder where PSD images are stored, to modify menus and logos.
- Text fonts. Same purpose as the item above.
- Where the main script is stored.
- Main files used in the project.

# How to create a final release
## Those aren't instructions on how to install the translation! For them, read "About the Patch" above.

To create a final patch like my repository, the resources are all included in [tools](https://github.com/JesterThirty4/ciconia-pt-br/tree/master/tools).
- The first step is to extract *arc.nsa*, for this, use *nsaout.exe*. You just need to move it to a folder with an archive *arc.nsa* and then execute *nsaout*. It'll extract the archives automatically, in a folder named *arc*.
- Now you have all the images you need to edit. Search for PSDs of the archive you'll edit in [photoshop-resources](https://github.com/JesterThirty4/ciconia-pt-br/tree/master/photoshop%20resources). After editing, you need to compile the arc in a *.nsa* again. For this, use the tool *nsaarc.exe* in [tools](https://github.com/JesterThirty4/ciconia-pt-br/tree/master/tools). Just execute, choose the folder arc and write the archive's name.
- Now about the script, you need to extract it from a archive *pscript.dat* to a *.txt* archive. My repository already contains a extracted version of the [script](https://github.com/JesterThirty4/ciconia-pt-br/tree/master/script). If you want to do manually, use the  *nsdec.exe* in [tools](https://github.com/JesterThirty4/ciconia-pt-br/tree/master/tools). Just move the archive *pscript.dat* in the same directory as *nsdec* and rename it to *nscript.dat*. The text will be extracted in *result.txt* on the same folder.
- Now that the script is in *.txt* format, make your changes! To compact it to a *.dat* format again, rename your text script to *0.txt* and move it to the same folder as nsmake.exe. After that, execute *nsmake*. The result will be a *nscript.dat. Rename it to *pscript.dat*.
- Now you need to organize the archives in your project. Use the archives in [steam api](https://github.com/JesterThirty4/ciconia-pt-br/tree/master/steam%20api) and [CiconiaPhase1.app](https://github.com/JesterThirty4/ciconia-pt-br/tree/master/CiconiaPhase1.app), they're necessary to the patch, and also the *default.ttf* font in [fonts-used](https://github.com/JesterThirty4/ciconia-pt-br/tree/master/fonts-used).
- In the end, your patch needs to be organized in a folder [like that](https://i.imgur.com/eucxqF9.png).

# Project Members
- [JesterThirty4](https://twitter.com/JesterThirty4) (Translator)
- [Anna Reis](https://twitter.com/MiyoHead) (Programmer)

# Credits
- [@MiyoHead](https://twitter.com/MiyoHead) Helped me with the script and patch! Thank you!
- [@InochiPM](https://twitter.com/InochiPM) Provided me with his Ciconia logo. Thank you!
- [@Loli_Deca](https://twitter.com/Loli_Deca) Helped me with some important grammatical erros. Thank you!
