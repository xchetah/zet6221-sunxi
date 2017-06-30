# zet6221-sunxi
zet6221 driver for linux-sunxi.

supports :
* zet6221
* zet6223
* zet6231
* zet6251/zet6252

## Fex File:
* use ctp_wakeup instead of ctp_reset in fex file :

<code>
ctp_wakeup = port:PB03<1>&lt;default&gt;&lt;default&gt;<1>
</code>

## Original Sources:


http://www.zeitecsemi.com/dokuwiki/lib/exe/fetch.php?media=allwinner:a13_v66.rar

http://www.zeitecsemi.com/dokuwiki/lib/exe/fetch.php?media=allwinner:a20_v66.rar
