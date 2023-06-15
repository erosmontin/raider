# Raider [R]("https://www.allgaeuer-zeitung.de/cms_media/module_img/3499/1749737_1_org_91659601.jpg")
     
a package to read and convert multiraid noise kspace to ismrmrd

# Installation
```
pip install git+https:https://github.com/erosmontin/raider.git
```
# read Noise KSpace from a multi Raid file
read a multiraid file, get the noise and convert it into ismrmrd format.


```
from raider_eros_montin import raider as rd
rd.exportNoiseFromRaid('multiraid.dat','outputname.h5',resolution=[1,1,1])

```

# Tests
1. [ ] Linux 
  1. [x] Debian based 
3. [x] windows
4. [ ] Mac
# Cite Us
- Montin E, Lattanzi R. Seeking a Widely Adoptable Practical Standard to Estimate Signal-to-Noise Ratio in Magnetic Resonance Imaging for Multiple-Coil Reconstructions. J Magn Reson Imaging. 2021 Dec;54(6):1952-1964. doi: 10.1002/jmri.27816. Epub 2021 Jul 4. PMID: 34219312; PMCID: PMC8633048.


[*Dr. Eros Montin, PhD*](http://me.biodimensional.com)

**46&2 just ahead of me!**
