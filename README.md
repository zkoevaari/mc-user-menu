mc-user-menu
============
Custom scripts for the User menu in GNU Midnight Commander.

<img width="644" height="388" alt="image" src="https://github.com/user-attachments/assets/67d86df2-5075-4143-be27-c7d6557ca7ae" />


## Installation

For the current user, place `menu` into `~/.config/mc/`, or replace `/etc/mc/mc.menu` for a system-wide setup.
Note that the current configuration can be accessed directly from MC through "Command" menu -> "Edit menu file".


## List of changes
(Compared to default `mc.menu` as of MC version 4.8.33)

Improved entries:
- Compress the current subdirectory (tar.gz)
- Extract (compressed) tar archive {Note: was "Extract the contents of a compressed tar file"}

New entries:
- Move current file to TRASH
- Move tagged files to TRASH
- Open current file in the background with xdg-open
- View file type using the `file` command
- Create an empty file
- Diff tagged files
- Meld current files
- Meld tagged files
- Meld current directories
- Show Git changes in current file (Meld)
- Show Git changes in working directory (Meld)
- Compress tagged files (tar.gz)
- Compress the current subdirectory (tar.lz)
- Compress tagged files (tar.lz)
- Archive the current subdirectory (tar)
- Archive tagged files (tar)
- Extract compressed tarlz archive
- Extract compressed rar archive
- Extract tagged (compressed) tars to subdirectories
- Plzip or decompress current file
- Plzip or decompress tagged files
- Parchive current file with par2create

Additionally, many default entries have been disabled, but all these and original versions of improved entries were kept in comment blocks for future reference.


## Further reading

If interested, see my related [blog post](https://www.rockfort.io/blog/2026/20260223_mc_config_part2.html) discussing some of the design decisions and explaining the scripts one-by-one.
