---
title: "Galactic Archaeology"
excerpt: "Uncovering the assembly history of the Milky Way"
layout: single
classes: wide
collection: research
author_profile: true
number: 1
header:
  image: /assets/images/gaia_mapping.jpg
  teaser: /assets/images/Gaia.png
---
Gaia is revolutionising the field of Galactic archaeology. Gaia DR3 has significantly increased the number of stars with radial velocities and provided for the first time astrophysical parameters, including metallicities for over 5 million stars. This dataset is improving our view of the local stellar halo.

![Halo Sample](/assets/images/halo_sample.png){:.align-center style="width: 50%; caption="Test"}
<sup>Figure showing the halo sample used in our study. The red circle shows a 2.5 kpc volume around the Sun, where we are able to invert Gaia parallaxes to obtain a reliable distance measurement. Selecting halo stars kinematically we have a sample of approximately 70,000 halo stars.</sup>


Merger debris is known to populate the inner stellar halo and is visible as substructure in integrals of motion (IOM) space, e.g. energy and angular momentum. Identifying these over-densities is possible with the use of clustering algorithms. 


![Single Linkage](/assets/images/single_linkage.png){:.align-center style="width: 90%; caption="Test"}<sup>2D visualisation of the single linkage algorithm where at each step of the algorithm the two closest components are joined until all components are joined. Taken from [Lövdal et al. (2022)](https://ui.adsabs.harvard.edu/abs/2022A&A...665A..57L/abstract){:target='_blank'}.</sup>


In this work, we use a single-linkage algorithm, which joins the two closest components together at each step. We apply this in the 3D integral of motion (IOM) space of energy and angular momenta. Our method differs from the regularly used clustering algorithms, where arbitrary decisions have to be made on when to stop linking components together. We do this by assessing the significance of the clusters at each step, comparing the number of stars in the dataset to the number in a smooth artificial halo, within that cluster region. The artificial halo is generated from the dataset by shuffling two components of the velocity to remove the substructure. 

We extract clusters when they reach their maximum significance and then in the next step we link clusters into groups using how close they are in IOM space (with a Mahalanobis distance) and their stellar populations (colour-magnitude diagrams and metallicity distributions). This provides an updated view of the local stellar halo using Gaia DR3 data. We find that the local stellar halo appears to be made up of 7 main groups and a handful of smaller substructures. The majority of these structures have been reported previously but we present an updated catalogue of their members. The catalogue can be found [here](https://cdsarc.cds.unistra.fr/viz-bin/cat/J/A+A/670/L2){:target='_blank'}

Several of the smaller substructures at high energy are new and interesting to follow up. Some of these present a small spread in metallicity indicative that they could have had a disrupted globular cluster origin. Others fall in the region of IOM space where we may expect debris from Gaia Enceladus since the debris from large mergers is known to be complex. Linking the complex debris together allows us to place further constraints on the nature of the Gaia Enceladus merger. Interpreting and characterising the different accretion events further requires the addition of chemical information that will be made more possible with 4MOST and WEAVE.

![IOM Space](/assets/images/IOM_space_groups.png){:.align-center style="width: 90%; caption="Test"}<sup>Figure showing the substructures within the local stellar halo in integrals of motion (IOM) space and velocity space. The substructures are colour coded by groups, showing that the local stellar halo appears to be made up of 7 main groups and a handful of smaller substructures.</sup>



For more information see:

[*Gaia DR3 view of dynamical substructure in the stellar halo near the Sun*](https://ui.adsabs.harvard.edu/abs/2023A&A...670L...2D/abstract){:target='_blank'} <br/>Dodd, Emma; Callingham, Thomas M.; Helmi, Amina; Matsuno, Tadafumi; Ruiz-Lara, Tomás; Balbinot, Eduardo; Lövdal, Sofie (2023)

[*Substructure in the stellar halo near the Sun. II. Characterisation of independent structures*](https://ui.adsabs.harvard.edu/abs/2022A&A...665A..58R/abstract){:target='_blank'} <br/> Ruiz-Lara, T.; Matsuno, T.; Lövdal, S. S.; Helmi, A.; Dodd, E; Koppelman, H. H. (2022)

[*Substructure in the stellar halo near the Sun. I. Data-driven clustering in integrals-of-motion space*](https://ui.adsabs.harvard.edu/abs/2022A&A...665A..57L/abstract){:target='_blank'} <br/> Lövdal, S. S.; Ruiz-Lara, T.; Koppelman, H. H.; Matsuno, T.; Dodd, E.; Helmi, A. (2022)


Here is a talk I gave on the topic:
{% include video id="AzglD9nrUbo" provider="youtube" %}


<sup>Cover image: Gaia Artist's impression - credits: ESA/ATG medialab; background image: ESO/S. Brunie</sup>


