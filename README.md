# magma-5g-agw

https://github.com/openvswitch/ovs/actions \
https://github.com/openvswitch/ovs/actions?query=branch%3Abranch-2.15

http://archive.ubuntu.com/ubuntu/pool/main/o/openvswitch/ \
http://archive.ubuntu.com/ubuntu/pool/main/o/openvswitch/openvswitch-switch_2.15.0-0ubuntu3_amd64.deb


https://rdr-it.com/en/ubuntu-18-04-add-multiverse-and-universe-repositories/

```bash
sudo apt install libunbound2
```

download latest magma packages:
```bash
wget https://github.com/ShubhamTatvamasi/magma-agw-build/releases/download/09-12-2021--06-21-38/magma-sctpd_1.7.0-1631431614-9e52cffa_amd64.deb

wget https://github.com/ShubhamTatvamasi/magma-agw-build/releases/download/09-12-2021--06-21-38/magma_1.7.0-1631431614-9e52cffa_amd64.deb

wget https://github.com/ShubhamTatvamasi/magma-agw-build/releases/download/09-12-2021--06-21-38/python3-psutil_5.8.0_amd64.deb

wget https://github.com/ShubhamTatvamasi/magma-agw-build/releases/download/09-12-2021--06-21-38/python3-ryu_4.34_all.deb
```

install packages:
```bash
sudo apt install ./magma-sctpd_1.7.0-1631431614-9e52cffa_amd64.deb

sudo apt install ./python3-psutil_5.8.0_amd64.deb

sudo apt remove python3-ryu
sudo apt install ./python3-ryu_4.34_all.deb

sudo apt install ./magma_1.7.0-1631431614-9e52cffa_amd64.deb
```




