# SwissCyberGrid

SwissCyberGrid is an interactive tool that demonstrates the effect of cyber-attacks on the Swiss ultra-high-voltage power grid and the efficiency of several detection algorithms.

A public version is available at [https://swisscybergrid.iigweb.hevs.ch/](https://swisscybergrid.iigweb.hevs.ch/).

## Code

- The [Angular frontend](https://github.com/GeeeHesso/AramisFrontend) was developed by [Gwenaëlle Gustin](https://github.com/gwenaellegustin) and the team of [David Wannier](https://www.hevs.ch/fr/collaborateurs/wannier-1805) at the HES-SO Valais-Wallis.
- The [backend](https://github.com/GeeeHesso/AramisAPI.jl) is a combination of Julia and Python, developed by [Marc Gillioz](https://github.com/gillioz) and the group of [Philippe Jacquod](https://etranselec.ch/), also at the HES-SO Valais-Wallis.


## Sources

- The model of the Swiss transmission grid is based on the [PanTaGruEl](https://zenodo.org/records/2642175) model of the European grid.
- The synthetic consumption and production data is generated using an [open-source method](https://doi.org/10.1038/s41597-025-04479-x) and is similar to an existing [dataset](https://zenodo.org/records/13378476) published by Marc Gillioz, Guillaume Dubuis and Philippe Jacquod.
- The ML algorithms have been trained by the same authors and will be the subject of a publication to appear.

## Funding

This project was funded by the [armasuisse Cyber-Defence Campus](https://www.cydcampus.admin.ch).
