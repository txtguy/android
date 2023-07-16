## Intro

- Install on Linux

```sh
sudo apt install kdeconnect
```

- Install on Android device

https://f-droid.org/packages/org.kde.kdeconnect_tp
- **v1.26.4** (12604) 2023-07-12: https://f-droid.org/repo/org.kde.kdeconnect_tp_12604.apk

## Example USAGE

- List of devices

```sh
kdeconnect-cli -a

kdeconnect-cli -l
```

- Send file to Android device

https://userbase.kde.org/KDE_Connect/Tutorials/Useful_commands

> `kdeconnect-cli -d $(kdeconnect-cli -a --id-only) --share "${file}"`

```sh
kdeconnect-cli -d "$(kdeconnect-cli -a --id-only)" --share hello.txt
```
