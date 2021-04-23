# halletal2021

[![arXiv](http://img.shields.io/badge/arXiv-2104.10919-blue.svg?style=flat)](https://arxiv.org/abs/2104.10919)

This repository hosts a tidied version of the work presented in Hall et al. (2021). We've stripped away unused or broken scripts, tests, and drafts of the paper that did not appear on ArXiV. If you're interested in looking at those anyway, the full repository of everything we did on this project can be found here: https://www.github.com/ojhall94/malatium

**Note**: We have reshuffled some of the directories when creating this repositories. The scripts may not run without errors.

## Abstract

Studies using asteroseismic ages and rotation rates from star-spot rotation have indicated that standard age-rotation relations may break down roughly half-way through the main sequence lifetime, a phenomenon referred to as weakened magnetic braking. While rotation rates from spots can be difficult to determine for older, less active stars, rotational splitting of asteroseismic oscillation frequencies can provide rotation rates for both active and quiescent stars, and so can confirm whether this effect really takes place on the main sequence.

We obtained asteroseismic rotation rates of 91 main sequence stars showing high signal-to-noise modes of oscillation.
Using these new rotation rates, along with effective temperatures, metallicities and seismic masses and ages, we built a hierarchical Bayesian mixture model to determine whether the ensemble more closely agreed with a standard rotational evolution scenario, or one where weakened magnetic braking takes place. The weakened magnetic braking scenario was found to be $98.4\%$ more likely for our stellar ensemble, adding to the growing body of evidence for this stage of stellar rotational evolution. This work represents the largest catalogue of seismic rotation on the main sequence to date, opening up possibilities for more detailed ensemble analysis of rotational evolution with Kepler.

## Data

Table 1 of the paper is hosted in this repository in the `data` folder, along with collected data from the literature used in this analysis.

Some data are too large to store on this repository, and were not released with the publication. If you are interested in obtaining these data (for example for reproducing the work, or using our posterior samples as priors in your own work), please contact:

`oliver.hall [at] esa [dot] int`

## Citing

If you use the results of this paper, or any of the code in this repository, please cite our work with the following BibTeX entry:

```latex
@ARTICLE{2021arXiv210410919H,
       author = {{Hall}, Oliver J. and {Davies}, Guy R. and {van Saders}, Jennifer and {Nielsen}, Martin B. and {Lund}, Mikkel N. and {Chaplin}, William J. and {Garc{\'\i}a}, Rafael A. and {Amard}, Louis and {Breimann}, Angela A. and {Khan}, Saniya and {See}, Victor and {Tayar}, Jamie},
        title = "{Weakened magnetic braking supported by asteroseismic rotation rates of Kepler dwarfs}",
      journal = {Nature Astronomy},
     keywords = {Astrophysics - Solar and Stellar Astrophysics, Astrophysics - Earth and Planetary Astrophysics},
         year = 2021,
        month = apr,
       eprint = {2104.10919},
 primaryClass = {astro-ph.SR},
       adsurl = {https://ui.adsabs.harvard.edu/abs/2021arXiv210410919H},
      adsnote = {Provided by the SAO/NASA Astrophysics Data System}
}
```

## Authors

Oliver J. Hall (@ojhall94) [*corresponding author*]

Guy R. Davies (@grd349)

Jennifer van Saders

Martin B. Nielsen (@nielsenmb)

Mikkel N. Lund (@miklnl)

William J. Chaplin

Rafael A García

Louis Amard

Angela A. Breimann

Saniya Khan (@rilasani)

Victor See

Jamie Tayar
