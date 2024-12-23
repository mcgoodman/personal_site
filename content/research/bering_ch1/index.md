---
title: "Predator-prey overlap and predation"
subtitle: "The ecological implications of biogeographic range shifts in the Bering Sea"
excerpt: "As waters warm, species are redistributing in space and in relation to one another - but what are the implications of these range shifts for species interactions? In my first thesis chapter (published in the journal *Ecography* in 2022), I used 30+ years of species biomass and stomach contents data to assess whether changes in species distributions in the Bering Sea have altered the extent of spatial overlap between juvenile walleye pollock and their predators, and whether those overlap changes have led to predictable changes in predation on the pollock stock."
date: 2023-10-02
draft: false
layout: single
---

<style type="text/css">
.button_custom {
  font-family: "Commissioner";
  font-size: 18px;
  color: #242424;
  border: 1px solid #242424;
  padding: 8px 24px;
  border-radius: 3px;
  background-color: white;
}

.button_custom:hover {
  background-color: #242424;
  color: white;
  border: 1px solid #242424;
  border-radius: 3px;
}
</style>


Many studies in marine ecosystems have documented species range shifts in  response to climate change, and many more have used species distribution models to  project species ranges under future conditions. More recently, multiple studies have employed projections from species distribution models to "rewire" food webs under future environmental changes, moving beyond a single-species focus to characterize ecosystem dynamics via changes in trophic interactions. Presumably, as the spatial overlap between fish and their predators changes over time, so too should predation rates (integrated across space) - but how well can we predict trophic interactions from predator-prey overlap?

In this study, we employed spatiotemporal models to characterize decadal-scale changes in spatial overlap between the distribution of juvenile walleye pollock and the distributions of four of its groundfish predators: arrowtooth flounder, Pacific cod, Pacific halibut, and adult walleye pollock. These fishes represent ecologically and commercially important species in a rapidly changing  sub-Arctic ecosystem, the eastern Bering Sea, Alaska, USA. 

-----------

![During years with extensive sea ice, melting sea ice results in the formation of a deep “cold pool” of water below 2 °C in the Eastern Bering Sea (EBS). The cold pool can restrict the movement of some predators into the northeast EBS shelf, such that years with less extensive cold pools may result in greater spatial overlap between juvenile pollock and their predators. For example, area overlap between juvenile pollock and flounder was about 15% higher during 2015, when the cold pool was receded (~124,500 km2), than in 2009, when it was more extensive (~333,000 km2). Smoothed 2 °C and 0 °C isotherms are shown as solid and dashed lines, respectively.](featured.png)

---------------


We then examined whether changes in spatial overlap corresponded to changes in predation, using spatiotemporal models of predator stomach contents. We found marked shifts in spatial overlap between juvenile pollock and two predators (arrowtooth flounder and Pacific halibut) over 34 years, with changes in overlap corresponding to increases in population-scale predation pressure. By contrast, we did not find clear relationships between spatial overlap and predation for Pacific cod and adult pollock, the two predators for which juvenile  pollock constitute a much smaller diet proportion.

Our findings highlight the complexity of predicting predation dynamics for generalist marine species and suggest a need for better process-based methods for understanding the potential future ecological impacts of coupled species range shifts. However, our results also show that simple metrics of spatial overlap between relatively specialized predators and their prey offer promise as a means to integrate predictions from species distribution models into ecosystem-based fisheries management.

-----------

![For each species of predator, we used VAST (Vector Autoregressive Spatio-Temporal) models to generate annual estimates of spatial overlap with, and predation on, juvenile pollock. Predation is measured annually as both the total biomass of juvenile pollock consumed (in tonnes) by each species of predator across the EBS annually (“total predation”), and as the average biomass of juvenile pollock consumed per biomass of predator (“relative biomass”).](diagram.png)

-----------


<a href="https://onlinelibrary.wiley.com/doi/full/10.1111/ecog.06084"><button class="btn btn-primary button_custom"><i class="fa fa-file"></i> Read the paper</button></a><b>&emsp;</b>
<a href="https://github.com/mcgoodman/Goodman-et-al_2022_Ecography"><button class="btn btn-primary button_custom"><i class="fa fa-code"></i> Check out the code</button></a>
