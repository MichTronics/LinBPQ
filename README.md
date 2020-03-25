# LinBPQ
Linux version of BPQ32 Ham Radio networking package

Installation Ubuntu
--------------------

Installing LinBPQ on Ubuntu 19.10<br>

Don't know yet if we need this i will test it:<br>
```
For example, if you have an amd64 system that you want to install 
i386 libraries onto, do the following:
  multiarch support is present from dpkg 1.16.
  run dpkg --add-architecture i386.
  run apt-get update to refresh the package cache with the newly added architecture.
  to delete i386 run dpkg --remove-architecture i386.
```


```
sudo apt-get install libpcap-dev libconfig++-dev
```

```
mkdir /PacketRadio
cd /PacketRadio
git clone https://github.com/michtronics/LinBPQ.git
cd /LinBPQ
make
```
