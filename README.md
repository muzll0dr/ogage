# ogage for OGC

Includes Brightness Control, Volume Control, Mute, Brightness 10%, Brightness 50%, Perfnorm, perfmaxm, Wifi On, Wifi Off and Standby

Prequisites
===========
```
sudo apt install brightnessctl rustc autotools-dev automake libtool libtool-bin
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
