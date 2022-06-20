## 01 - Install DC 

1. use `sconfig` to:
    - Change the hostname
    - Change IP to static
    - Chnge the DNS server to our own IP address

2. Install Active Direcory Windows Feature

```shell
Install-WindowsFeature AD-Domain-Services -IncludeManagment
```