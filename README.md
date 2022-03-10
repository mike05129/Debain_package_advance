# Debain_package_advance<br />
This is for learning Debian package<br />
Download source code<br />
Suggest requirement: Ubuntu 20.04<br />


## __Useful CMD__ <br />
Search file : dpkg -S file_name_pattern <br />
Download : pull-lp-source package <br />
Installation : dpkg -i package.deb <br />
Remove : dpkg -r package.deb <br />
Package : dpkg -b package file_name.deb <br />
Control file : dpkg -e package file_name.deb<br />
List installed : dpkg -l<br />
Content : dpkg -c package.deb<br />
Configure : dpkg --configure package<br />



## __REFERENCE__ <br />
GNU:http://www.gnu.org/software/software.html <br />
Maintainer Scipts:https://wiki.debian.org/MaintainerScripts <br />
Useful CMD : https://www.debian.org/doc/manuals/maint-guide/build.zh-tw.html <br />
Git lab : https://salsa.debian.org/public

## __Troubleshooting__ <br />
locked by another process : https://askubuntu.com/questions/219545/dpkg-error-dpkg-status-database-is-locked-by-another-process <br />
Permission denide(/usr/bin/testing.sh):Before packaged,don't forget using chmod...  
