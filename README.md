# Debain_package_advance<br />
This is for learning Debian package<br />
Download source code revised and upload to PPA<br />
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
Create a source package from the branch contents : debuild -S -d -us -uc <br />
Add changelog text : dch -i <br />


## __REFERENCE__ <br />
GNU:http://www.gnu.org/software/software.html <br />
Maintainer Scipts:https://wiki.debian.org/MaintainerScripts <br />
Useful CMD : https://www.debian.org/doc/manuals/maint-guide/build.zh-tw.html <br />
Git lab : https://salsa.debian.org/publicFun <br />
Linux function : https://man7.org/linux/man-pages/man1/dpkg-source.1.html <br />
Debian file : https://www.debian.org/doc/manuals/maint-guide/dother.zh-tw.html (Don't forget intsall file) <br />
Debian file : https://www.debian.org/doc/manuals/debmake-doc/debmake-doc.zh-cn.pdf (Take time to read it) <br />

## __PPA Experience__ <br />
Basic : https://help.launchpad.net/Packaging/PPA <br />
PGP Email : https://help.launchpad.net/ReadingOpenPgpMail (It's more easily using the latest way... ) <br />
OpenPGP Key : https://help.ubuntu.com/community/GnuPrivacyGuardHowto <br />

## __Troubleshooting__ <br />
locked by another process : https://askubuntu.com/questions/219545/dpkg-error-dpkg-status-database-is-locked-by-another-process <br />
Permission denide(/usr/bin/testing.sh):Before packaged,don't forget using chmod...  
