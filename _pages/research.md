---
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

<br>

## Galaxy Evolution
My research broadly focuses on the evolution of low-mass galaxies. Specifically, I study the resolved stellar populations of dwarf galaxies in our cosmic neighborhood, the Local Group, using space-based and large ground-based telescopes.  I employ both stellar and galactic evolution models in order to interpret these observations and constrain the key physical processes that govern galaxy evolution over cosmic time. My work is primarily advised by [Prof. Dan Weisz](http://dweisz.github.io/).

### Local Group Dwarf Galaxies
Low-mass galaxies are increasingly central to a wide variety of astrophysics. They are thought to power cosmic reionization, have become testbeds for cold dark matter models of galaxy formation, and are among the best proxies for the low metallicity star-forming conditions in the early Universe. While most low-mass galaxies are too faint to see at higher redshifts, the proximity of dwarf galaxies in our cosmic neighborhood, the Local Group (LG), allows for observation of their individually resolved stars. The colors, luminosities, and spectra of these stars provide a stellar fossil record that encode a galaxy’s entire evolution across cosmic time. I am currently developing a framework for incorporating both resolved star photometry and spectroscopy to measure the comprehensive formation histories of resolved dwarf galaxies in the LG. Through this work, I hope to provide new insight into the poorly understood physics of low-mass galaxy evolution in the early Universe.

## Stellar Spectroscopy
The absorption features imprinted in the spectrum of a star encode its physical structure, chemicalc composition, and motion through space. As such, spectroscopy of resolved stars is an incredibly powerful tool in the study of stellar populations and galaxy evolution.

### Chemical Abundances
The chemical composition of individual stars trace the chemistry of the interstellar medium at their birth, providing a detailed fossil record of a galaxy's chemical evolution over cosmic time. Supernovae (of various kinds), stellar winds, neutron star mergers, and gas in/outflows each leave a unique chemical signature in the abundance patterns of stars observed today. Accordingly, studying the detailed chemical abundances of large numbers of resolved stars provide valuable insight on everything from the formation and evolution of galaxies to the detailed nuclear and quantum physics that underly stellar evolution and the production of heavy elements.

Specifically, I focus on the measurement of chemical abundances from low-resolution (R~2000) blue-optical spectrographs, which are capable of observing fainter and more distant stars than high-resolution spectrographs. Because many absorption features are blended together in low-resolution spectra, robustly measuring abundances requires novel full-spectrum fitting techniques like [The Payne](https://ui.adsabs.harvard.edu/abs/2019ApJ...879...69T/abstract) or [The DD-Payne](https://ui.adsabs.harvard.edu/abs/2019ApJS..245...34X/abstract)  which use neural networks to efficiently fit the entire spectrum for all stellar parameters and abundances at once. I am currently working with Keck/LRIS spectra of globular cluster stars to validate low-resolution abundance measurements against high-resolution measurements of the same stars. I am also involved with [FOBOS](https://fobos.ucolick.org/), a next-generation low-resolution, highly-multiplexed, blue-optical spectrograph for the Keck Observatories.

### Chemical Information Content
Recently I have worked on quantifying how precisely various existing and proposed spectrographs can measure the chemical composition of stars outside of the Milky Way (e.g., in Local Group dwarf galaxies and the disk of M31/Andromeda). This work was published in [Sandford et al. (2020)](https://ui.adsabs.harvard.edu/abs/2020ApJS..249...24S/abstract).  Along with it, I released [Chem-I-Calc](https://w.astro.berkeley.edu/~nathan_sandford/research.html#chemicalc), a Python package designed to make it straightforward for stellar spectroscopists to calculate additional forecasts for instruments and observations not discussed in the paper.

Highlights from this study include:
* Low- and moderate-resolution spectroscopy at blue-optical wavelengths are incredibly information rich and enable the measurement of many individual elements including several neutron capture elements (e.g., Sr, Ba, La, and Eu).
* High-resolution spectrographs contain considerable chemical information even at low S/N, which can be extracted by fitting the full wavelength coverage simultaneously. Even small windows of these spectra can constrain [Fe/H] and a handful of other elements.
* Next generation facilities (e.g., JWST/NIRSpec and 30-m class telescope) will enable precision abundance measurements throughout the Local Group and [Fe/H] and [α/Fe] for resolved stars out to several Mpc.

<br>

## Undergraduate Research

### Metallicity Gradients in Disk Galaxies
Because the distribution of enriched gas in a galaxy is strongly coupled to galactic gas flows and, in turn, internal feedback processes, the radial metallicity gradient of a galaxy contains valuable information about the physics governing galaxy evolution. For example, the negative metallicity gradients commonly observed in disk gradients are thought to be evidence for inside-out galaxy formation, which is the theory that galaxies form stars earliest in their inner regions due to high gas densities. As the galaxy continues to accrete gas, stars begin forming at larger and larger radii. This differential radial formation time results in gas in the inner regions of a galaxy becoming more enriched than gas in the outer regions—forming a negative metallicity gradient. Recent observational campaigns have dramatically increased the number of galaxies with measured metallicity gradients allowing for rigorous comparisons of observations to galaxy evolution models.

As an undergraduate under the supervision of Dr. Yu Lu at the Carnegie Observatories, I expanded upon a readially resolved [semi-analytic galaxy evolution model](https://academic.oup.com/mnras/article/446/2/1907/2892882), adding functionality to track the radial profile of oxygen abundances in disk galaxies across cosmic time. By leveraging the low computational requirements and flexibility of our semi-analytic model, I efficiently explored the effects of a variety of galactic feedback physics on the metallicity gradients of disk galaxies. When analyzing our model’s predictions in light of recent observations, I found that ejective feedback and efficient gas recycling can erase a galaxy’s metallicity gradient, even if a galaxy had undergone inside-out galaxy evolution. This work comprised my undergraduate thesis (available upon request).

### Indirect Detection of Dark Matter Annihilation
Dark Matter makes up ~85% of all matter in the Universe, but because it only interacts with normal (baryonic) matter and light gravitationally, its nature is largely unknown. Several candidates for dark matter, like weakly interacting massive particles (WIMPs), are predicted to self-annihilate and produce high energy gamma rays. If this is true, dark matter should be indirectly detectable in regions of high dark matter densities by gamma-ray telescopes like the [Fermi Large Area Telescope (Fermi-LAT)](https://fermi.gsfc.nasa.gov/science/eteu/dm/). As some of the most dark matter-dominated systems in the Universe with few other astrophysical gamma ray sources, dwarf spheroidal galaxies are excellent targets for indirect dark matter searches. Conversely, dark matter annihilation signatures may be the only feasible way to detect hypothetical "dark satellites" of the Milky Way, which contain too little baryonic, luminous matter to be seen by traditional optical surveys.

Through the [Science Undergraduate Laboratory Internship](https://science.energy.gov/wdts/suli/) at the [Kavli Institute for Partical Astrophysics and Cosmology](https://kipac.stanford.edu/), I prepared for an all-sky blind search for dark satellites. With Dr. Eric Charles and Dr. Mattia Di Mauro, I applied various tests for systematics in our data reduction pipeline and performed a preliminary stacked analysis of seven years of Fermi-LAT dwarf galaxy data. We found no signs of excess gamma-rays due to dark matter annihilation, providing a more stringent constraint on the dark matter annihilation cross-section than previously found.

<br>

## Publications
Below is a list of my peer-reviewed publications; a complete list of publications can be found on [ADS](https://ui.adsabs.harvard.edu/search/filter_author_facet_hier_fq_author=AND&filter_author_facet_hier_fq_author=author_facet_hier%3A%220%2FSandford%2C%20N%22&fq=%7B!type%3Daqp%20v%3D%24fq_author%7D&fq_author=(author_facet_hier%3A%220%2FSandford%2C%20N%22)&q=author%3A%22Sandford%2C%20Nathan%20R.%22&sort=date%20desc%2C%20bibcode%20desc&p_=0).

* Gull, M., Weisz, D., Senchyna, P., **Sandford, N.**, et al., In Prep, <br>
*A Panchromatic Study of Massive Stars in Extremely Metal-Poor Local Group Dwarf Galaxy Leo A*
* **Sandford, N.**, Weisz, D. & Ting, Y.-S., In Prep, <br>
*Validating Stellar Abundance Measurements from Multi-Resolution Spectroscopy*
* Fu, S. et al (including **Sandford, N.**), 2022, ApJ, 925, 6. <br> 
*Metallicity Distribution Function of the Eridanus II Ultra-Faint Dwarf Galaxy from Hubble Space
Telescope Narrow-band Imaging*
* Bundy, K. et al (including **Sandford, N.**), 2020, SPIE, 11447. <br> 
*The Keck-FOBOS spectroscopic facility: conceptual design*
* **Sandford, N.**, Weisz, D. & Ting, Y.-S., 2020, ApJS, 249, 24. <br> 
*Forecasting Chemical Abundance Precision for Extragalactic Stellar Archaeology*
* Xiang, M., Ting, Y.-S., Rix, H.W., **Sandford, N.**, et al., 2019, ApJS, 245, 34. <br> 
*Abundance Estimates for 16 Elements in 6 Million Stars from LAMOST DR5 Low-Resolution Spectra*

<br>
