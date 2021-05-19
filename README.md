# ogage for RGB10 Max

Includes Brightness Control, Volume Control, Mute, Brightness 10%, Brightness 50%, Perfnorm, perfmaxm, Wifi On, Wifi Off and Standby

HotKey - 17
Brightness Up - 8
Brightness Down - 9
Brightness 10% - 14
Brightness 50% - 15
Volume Up - 11
Volume Down 10
Mute - 16
Perfnorm - 4
Perfmax - 6
Wifi Off - 7
Wifi On - 5
Suspend - 13

![image](https://user-images.githubusercontent.com/20381196/113501670-5b8d7000-956a-11eb-8707-132d909a2ec5.png)


Prequisites
===========
```
sudo apt install brightnessctl rustc autotools-dev automake libtool libtool-bin libevdev-dev
```

Build
=====
```
git clone https://github.com/southoz/ogage.git
cd ogage
cargo build --release
strip target/release/ogage
```
ogage executable will be in the target/release folder.
