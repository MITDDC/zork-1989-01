# Zork binary files, 1989 January
This repository contains the binary files for a January 1989 version of [Zork](https://en.wikipedia.org/wiki/Zork), an interactive fiction game created at MIT by Tim Anderson, Marc Blank, Bruce Daniels, and Dave Lebling. The files are a part of the [Massachusetts Institute of Technology, Tapes of Tech Square (ToTS) collection](https://archivesspace.mit.edu/repositories/2/resources/1265) at the MIT Libraries Department of Distinctive Collections (DDC).
## File organization and details
### [zork](../main/zork)
The files within this directory are the Zork specific files from the ```2841.tap``` tape image file within the ```/tots/recovered/vol3``` directory of the [ToTS collection](https://archivesspace.mit.edu/repositories/2/resources/1265). Most files are written in the MDL programming language and were originally created on a PDP-10 timeshare computer running the ITS operating system.

The files were extracted from the tape image using the [itstar program](https://github.com/PDP-10/itstar). The filenames have been adapted to Unix conventions, as per the itstar translation. The original filename syntax would be formatted like, ```CSTACY; MADADV HELP```, for example. All files have been placed into this artificial zork directory for organizational purposes.

The [```cstacy```](../main/zork/cstacy) directory contains the copies of files for the ITS version of the game. Presumably copied by user CSTACY in 1989.

### [codemeta.json](../main/codemeta.json)
This file is metadata about the Zork files, using the [CodeMeta Project](https://codemeta.github.io/) schema.
### [LICENSE.md](../main/LICENSE.md)
This file describes the details about the rights to these files. See [Rights](#rights) for additional information.
### [README.md](../main/README.md)
This file is the readme detailing the content and context for this repository.
### [tree.txt](../main/tree.txt)
A file tree listing the files in the [```zork```](../main/zork) directory showing the original file timestamps as extracted from the tape image.

## Preferred Citation
[filename], Zork binary files, 1989 January, Massachusetts Institute of Technology, Tapes of Tech Square (ToTS) collection, MC-0741. Massachusetts Institute of Technology, Department of Distinctive Collections, Cambridge, Massachusetts. [swh:1:dir:bc359495b6856ca418aae7a95a817b3b8d9f1c60](https://archive.softwareheritage.org/swh:1:dir:bc359495b6856ca418aae7a95a817b3b8d9f1c60)
## Rights
To the extent that MIT holds rights in these files, they are released under the terms of the [MIT No Attribution License](https://opensource.org/licenses/MIT-0). See the ```LICENSE.md``` file for more information. Any questions about permissions should be directed to [permissions-lib@mit.edu](mailto:permissions-lib@mit.edu)
## Acknowledgements
Thanks to [Lars Brinkhoff](https://github.com/larsbrinkhoff) for help with identifying these files and with extracting them using the itstar program mentioned above.
