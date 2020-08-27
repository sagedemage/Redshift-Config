# About
A redshift configuration for my location.

## Redshift.conf file location
~/.config/redshift/redshift.conf

## Configuration steps
1. Make directory
```
mkdir ~/.config/redshift/
```
2. Create the file and edit it
```
sudo vim ~/.config/redshift/redshift.conf
```

## Enable redshift with systemd
1.Make systemd user directory

```
mkdir ~/.config/systemd/user
```

2.Create and edit redshift-gtk.service

```
sudo vim ~/.config/systemd/user/redshift-gtk.service
```
3. Enable redshift-gtk.service

```
systemctl --user enable redshift-gtk.service
```

