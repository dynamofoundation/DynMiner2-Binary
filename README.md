# DynMiner2-Binary

Windows and linux binaries for Yiimp stratum based pools

Example for stratum:
```
dynminer2 -mode stratum -server web.letshash.it -port 5966 -user dy1qyc3lkpe8ysns5z65u3t5j0remfpdr49j6h60gg.test2 -pass d=2 -miner GPU,16384,128,0,0
```

Example for solo:
```
dynminer2 -mode solo -server http://192.168.1.193:6433/ -user user -pass 123456 -wallet dy1qyc3lkpe8ysns5z65u3t5j0remfpdr49j6h60gg -miner GPU,65536,128,0,0
```
