RO en attente de la fin de migration







































# redshift_relative

Brouillon

TODO : il me semble avoir déjà fait une autre doc => fusionner

Testé avec succès : Debian Bullseye 11

A priori il suffit juste d'installer **redshift-gtk** sans le mettre dans /etc/lightdm/lightdm.conf
il auto-configure la localisation (par FAI et IP ?)

Fichier de config : $HOME/.config/redshift.conf

Pour que tous les écrans soient gérés (par défaut seul le n°1 était géré, mettre dans le fichier de config ([doc](http://jonls.dk/redshift/) rubrique "Configuration file"):
```sh
[randr]
screen=_all_
```

doc utile : 
http://jonls.dk/redshift/
https://wiki.debian.org/Redshift
https://docs.redshift3d.com/display/RSDOCS/Installing+Redshift+on+Linux
https://www.educba.com/redshift-linux/
