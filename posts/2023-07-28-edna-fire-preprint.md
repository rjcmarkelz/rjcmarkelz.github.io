---
title: Fire Impacts on Pollinators Across Ecosystem Types
description: -- Our pre-print is up!
author: RJ Cody Markelz
date: 2023-07-28
categories: [research, fire, ecology, science, visualization, illustration, pollinators, arthropods, eDNA, zine]
image: /images/blue-oak-ranch-sketch.jpg
---

<p align="Left">
  <img src="/images/blue-oak-ranch-sketch.jpg" alt="Oak tree landscape sketch" height="300"/>
</p>

The above sketch is from one of our field sites, Blue Oak Ranch Reserve. I recently blogged about a [introductory fire ecology class](/posts/2023-05-05-fire-ecology-class-1.html) at the [Blue Oak Ranch Reserve](https://ucnrs.org/reserves/blue-oak-ranch-reserve/). The reserve is part of the [UC Reserve system](https://ucnrs.org/) and is one of the many sites I am collecting data at for a larger project looking at fire impacts on California ecosystems and insect pollinators. Other blog posts in the series are also available: [post 2](/posts/2023-05-08-intro-fire-science.html), [post 3](/posts/2023-05-19-blue-oak-fire.html), [post 4](/posts/2023-05-26-plants-insects.html). I wrote about the reserve system in these other posts on [fire data](/posts/2022-07-15-ucreservefires/) and [environmental data](/posts/2022-02-01-uc-reserve-data-1/). 

We just finished up analyzing the research and writing up the paper. It is currently available as a pre-print [here](https://www.biorxiv.org/content/10.1101/2023.07.17.548903v2). 

### Abstract
Wildfires are increasingly altering ecosystems, posing significant challenges for biodiversity conservation and ecosystem management. In this study, we used DNA metabarcoding to assess the response of arthropod communities to large-scale wildfires across diverse habitat types. We sampled six reserves within the University of California Natural Reserve System (UCNRS), each which was partially burned in the 2020 Lightning Complex wildfires in California. Using yellow pan traps to target pollinators, we collected arthropods from burned and unburned sites across multiple habitat types including oak woodland, redwood, scrub, chamise, grassland, forest, and serpentine habitats. We found no significant difference in alpha diversity values between burned and unburned sites; instead, seasonal variations played a significant role in arthropod community dynamics, with the emergence of plant species in Spring promoting increased pollinator richness at all sites. Compositional similarity analysis revealed that burn status was not a significant grouping factor when comparing all sites. Instead, community composition primarily varied across reserves, indicating distinct pools of arthropods structured geographically. Habitat type played a crucial role in determining the response of arthropod communities to fire. While communities in grasslands and oak woodlands exhibited recovery following burn, scrublands experienced substantial changes in community composition. Our study highlights the importance of examining community responses to wildfires across broad spatial scales and diverse habitat types. By understanding the nuanced dynamics of arthropod communities in response to fire disturbances, we can develop effective conservation strategies that promote resilience and maintain biodiversity in the face of increasing wildfire frequency and intensity driven by climate change.

The code repository is available [here](https://github.com/rjcmarkelz/edna-fire). The repository also contains instructions on how to make reproducible data science docker containers for each of the major steps in the analysis pipeline. We made the docker container with the largest number of software dependencies available on docker hub [here](https://hub.docker.com/r/codymarkelz/holmquist-etal-edna-fire-paper).