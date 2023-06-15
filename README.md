# Raider
You get the name right?
# installation
```
pip install git+https:https://github.com/erosmontin/raider.git
```
# read Noise kspace from multiraidfile

```
from raider_eros_montin import raider as rd
K=rd.readMultiRaidNoise('/data/MYDATA/SNR_rawdata_examples/2018-07-31_BRAINO_scan/MULTI-RAID-FILE/meas_MID02317_FID373207_AXIAL_2D_GRE_1SL.dat',False,False)
rd.KSpace2DtoISMRMRD(K,"aaa.h5",[1,1,1])
```


[*Dr. Eros Montin, PhD*](http://me.biodimensional.com)
**46&2 just ahead of me!**
