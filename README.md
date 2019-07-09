# devOps_w7

``` BASH

➜  frontend curl http://localhost:4567/grab/cpu_times/
scputimes(user=101.12, nice=5.78, system=61.66, idle=39403.08, iowait=10.69, irq=0.0, softirq=8.84, steal=0.0, guest=0.0, guest_nice=0.0)

➜  frontend curl http://localhost:4567/grab/swap_memory/
sswap(total=0, used=0, free=0, percent=0, sin=0, sout=0)

➜  frontend curl http://localhost:4567/grab/virtual_memory/
svmem(total=1040146432, available=728817664, percent=29.9, used=134377472, free=165117952, active=512454656, inactive=242925568, buffers=43180032, cached=697470976, shared=4571136, slab=94785536)

➜  frontend curl http://localhost:4567/grab/net_if_addrs/
{'lo': [snicaddr(family=<AddressFamily.AF_INET: 2>, address='127.0.0.1', netmask='255.0.0.0', broadcast=None, ptp=None), snicaddr(family=<AddressFamily.AF_PACKET: 17>, address='00:00:00:00:00:00', netmask=None, broadcast=None, ptp=None)], 'eth0': [snicaddr(family=<AddressFamily.AF_INET: 2>, address='172.17.0.2', netmask='255.255.0.0', broadcast='172.17.255.255', ptp=None), snicaddr(family=<AddressFamily.AF_PACKET: 17>, address='02:42:ac:11:00:02', netmask=None, broadcast='ff:ff:ff:ff:ff:ff', ptp=None)]}


```