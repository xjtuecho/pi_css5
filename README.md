# pi_css5

PI(= 3.1415926535897932384626...) Calculation Program.

## Documents

- [readme.txt](readme.txt)
- [install.txt](install.txt)

## 1M benchmark result on some SoC

Benchmark command:

```shell
./pi_ccs5 $((1<<20))
```

- Intel Celeron 1037U (IvyBridge) on Hyper-V 3.69s
- Amlogic S905D (4xA53) on phicomm N1 18.51s
- Intel Celeron N2840 (BayTrail) 29.53s
- BCM2836 (4xA7) on raspberry PI 2B 33.14s
