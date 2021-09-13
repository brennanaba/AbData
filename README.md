# H3Data

Position of the BB atoms for most antibody Fvs in the pdb. 

It comes with a csv containing the pdb ID + the heavy chain ID, the resolution and the (aligned) sequence.

This is mostly for my use but if anyone wants to use it, feel free.

### Position of chains and CDR regions

All antibodies here (for both structure and sequence) are numbered using IMGT. For structures (stored as numpy array), the padding is Nan values. For sequences it is "-".
Here are the positions of each region:


Heavy chain: [:133]

Light chain: [133:]

CDR-H1: [25:34] -> With anchors [23:36]

CDR-H2: [53:61] -> With anchors [51:63]

CDR-H3: [102:122] -> With anchors [100:124]

CDR-L1: [157:174] -> With anchors [155:176]

CDR-L2: [189:196] -> With anchors [187:198]

CDR-L3: [228:243] -> With anchors [226:245]


### Cite

If you are using this you should cite SAbDab, as that is where I got all the data from:

```tex
@article{SABDAB,
  title={{SAbDab}: the structural antibody database},
  author={Dunbar, James and Krawczyk, Konrad and Leem, Jinwoo and Baker, Terry and Fuchs, Angelika and Georges, Guy and Shi, Jiye and Deane, Charlotte M},
  journal={Nucleic acids research},
  volume={42},
  number={D1},
  pages={D1140--D1146},
  year={2014},
  publisher={Oxford University Press}
}
```
