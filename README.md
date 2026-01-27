Copy Pasta:

1) wget http://bin.entware.net/mipselsf-k3.4/installer/generic.sh -O - | sh

2) export PATH=/opt/bin:/opt/sbin:$PATH

3) opkg update

4) opkg install git-http

5) opkg install git  # (Optional, if git is missing)

6) mv /usr/bin/git /usr/bin/git.bak

7) ln -s /opt/bin/git /usr/bin/git

8) git config --global http.sslVerify false

9) git config --global --add safe.directory /usr/data/moonraker/moonraker

10) git clone --depth 1 https://github.com/krahembuhl85/Creality-Helper-Script-K1-CFS.git /usr/data/helper-script

11) sh /usr/data/helper-script/helper.sh




## Created while waiting for GCOCE Typo correction on start_print.cfg by Nik

## Original Helper Script CFS Branch by Nik Oli:  
[Git](https://github.com/Nik-oli/Creality-Helper-Script-K1-CFS)

## Original Helper Script Wiki by Guilouz:  
[Wiki](https://guilouz.github.io/Creality-Helper-Script-Wiki/)


