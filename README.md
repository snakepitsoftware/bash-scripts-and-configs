# bash-scripts-and-config
Useful bash scripts and configuration files

#### Directory Structure
The directory structure could use a little explaining, ...
scripts/ - useful scripts for working in a UNIX like environment, should all be self contained, only dependent on installed applications
dots/ - dot files (minus the dot) for controlling the behavior of the shell and other applications
configs/ - other config files for controlling the behavior of applications, these may just be snippets

The files in this project support OS/X and Linux as best they can as these are the only OSs that I currently have access to. You might find that FreeBSD is fairly well supported as well as it used to be my main OS.

#### Using These Files
There will eventually be a script called create-links.sh in the root of this repo that can be used to create symbolic links to the other files as appropriate. Basically, it'll create links in ~/bin for all the scripts and links in ~/ for all the dot files.
