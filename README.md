# Bash System Info 
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/5a3b5bbe370e409a96a0de70b1c95c31)](https://www.codacy.com/app/marshki/bash_sys_info?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=marshki/bash_sys_info&amp;utm_campaign=Badge_Grade)
[![MIT licensed](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/hyperium/hyper/master/LICENSE)

Bash script extracts useful information from a `Linux` host using a menu-driven interface.
This script builds upon *grabsysinfo.sh* attributed to Vivek Gite circa 2007.09.12.

Test status: 

Operating System | Tested to Work  
-----------------|---------------
Centos 7         | Y
Debian 8         | Y 
Debian 9         | Y 
Fedora 26        | N
Fedora 27        | N
Ubuntu 16.04     | Y 
Ubuntu 18.04     | N

# Getting Started 

First, see: [REQUIREMENTS.md](https://github.com/marshki/bash_sys_info/blob/master/REQUIREMENTS.md)

Then, for the whole enchillada run as `root`: 

`bash system_info.sh`. 

which will present a text-based menu from which you can make a selection and receive output:
 
Debian 8     | Debian 8 pi 
----------   | -----------
![Alt text](https://github.com/marshki/bash_sys_info/blob/master/docs/screen_grab.png "Deb_think") | ![Alt text](https://github.com/marshki/bash_sys_info/blob/master/docs/screen_grab_2.png "Deb_pi")
 
# TODO

[ ] General code review and clean up. 
[ ] Use `awk` to do most regexp stuff.  
[ ] Refactor header for.
[ ] Test on: Fedora 26 & 27, Ubuntu 18.04.   

# History 

First commit 2016.10.07

Code review 2017.11.05 

# License 

[MIT license](https://opensource.org/licenses/MIT). 'Nuff said. 

# Acknowledgments 

Vivek Gite attributed author of `grabsysinfo.sh` from which this project builds upon. 
