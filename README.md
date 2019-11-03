# raspbian time machine server playbook

Setups a time machine server on a raspbian based OS.

## Requirements

* Raspberry 3 or 4
* Installed raspbian OS
* ssh server enabled ([see official documentation](https://www.raspberrypi.org/documentation/remote-access/ssh/))
* a hfs+ formatted USB Drive ([see mr-bt's manual](https://github.com/mr-bt/raspberrypi-timemachine#1-format-the-hard-drive))
* ansible installed on a client device
* ssh configured on client device

## Run playbook

```
./run.sh
```
