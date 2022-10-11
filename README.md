# Spatial distribution of sharks in Atlantis GOA

This code produces spatial distribution of salmon and Pacific sleeper sharks, respectively captured by the groups `Shark_pelagic` and `Shark_demersal` in Atlantis GOA. These species are not well sampled in any of the trawl surveys we have access to, so the sdmTMB approach used for groundfish species was not viable here.  

Seasonal spatial distributions for salmon sharks are approximated from the kernel density predictions from [Weng et al. (2008)](https://doi.org/10.3354/meps07706).  

Spatial distributions (constant over time) for sleeper sharks are modeled with sdmTMB and International Pacific Halibut Commission (IPHC) Fishery-Independent Setline Survey ([FISS](https://iphc.int/data/fiss-data-query)) data. 

Juveniles and adults were assumed to have the same spatial distributions.