---
layout: post
title: "Postdoctoral Research Projects"
description: ""
tags: [NSF, Postdoc, research, Brassica, Systems, Genetics]
comments:
image:
  feature:
  credit:
  creditlink:
---

## Physiological Systems Biology of Competition in *Brassica rapa*

<figure>
	<img style="float: right" src="/images/research_overview.jpg">
</figure>

Plants growing in dense stands compete with one another for light resources at the top of the canopy. When plants sense neighbors through the phytochrome photoreceptor system they become apical dominant and grow upwards to maximize light capture. This response is termed shade avoidance and has very important ecological and agronomic consequences if plant resources are used for competitive growth instead of reproductive output. For example, overseeding in an agricultural field is wasteful of seed resources if many individuals die after competing with neighbors for limited light and nutrient resources. In ecological settings, mixed plant communities are competing for resources in a similar way to agricultural settings, but without the direct human management of inputs. In order to study the agronomic and ecological consequences of competition I am working with the emerging model species *Brassica rapa*. *B. rapa* is an ideal model for plant competition research because it has a sequenced genome, is both a crop and a weed in agricultural settings, and is a highly morphologically and physiologically diverse species. I am approaching this from many different angles that rely on my diverse research background and interests.

### 1) *B. rapa* trait database

<figure>
	<img  src="/images/graph_db.jpg">
</figure>

Hard won biological data (especially from the field) should not just sit in a lab note book or on spread sheets scattered across various machines. Sharing phenotypic data after publication should be a priority for us as a community, just like putting sequencing data into NCBI databases ([see Zamir 2013](http://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.1001595)). This allows for the data to be used to ask multiple questions, for modeling, or to be analyzed using systems biology techniques. Towards all these goals I have designed a graph database to house all of the published trait data, experimental meta-data, publications, gene expression data, from the *B. rapa* population that I am working with combined with all the genomic features of the reference genome.

A partial realization of this work has come out of working with an undergraduate [Tiffany Ho](https://github.com/tiaho) to create an interactive data visualization tool to examine co-occurrence of eQTL with physiological QTL called [QTLVisR](http://symposium.plb.ucdavis.edu/apps/qtl-visualization). This is still a work in progress, but the example does a great job showing the concept.

### 2) Multi-trait mapping with a dense genetic map

In collaboration with [Mike Covington](http://mfcovington.github.io/) (who generated the SNPs), I created a saturated genetic map for this population that can be found [here](https://github.com/rjcmarkelz/brassica_genetic_map_paper). This new map, along with a Bayesian statistical approach and my graph database all blends together into a fun data science project. I am remapping all the published traits in the database using a multi-trait approach. This data is used directly in the next two aspects of my project. <img src="/images/genetic_map.jpg">

### 3) Trait data integration

I have been working on this aspect of my project the longest. The central dogma of molecular biology says DNA → RNA → Protein. Scaling the actions and interactions of proteins spatially across tissue or cell types is physiology. Scaling the actions of physiology across space and time is development. Updating the simple model to include physiology and development would look something like this: DNA → RNA → Protein → Metabolites → Physiology → Development. Of course there are feedbacks every step of the way, and it is hard to disentangle each of these into separate processes, but this simple conceptual model goes a long way. If there is a genomic location for these interactions explaining some of the variance observed in the physiological or developmental phenotype, then there is a QTL in that genomic location. QTL studies are conducted using genetic mapping populations where the parents of these populations are differ significantly from one another in the trait of interest. Up until recently, a majority of QTL studies have focused on traits that are the result of many proteins interacting one level of biological organization below the physiological or developmental trait. It is a large jump in biological organization to work backwards from physiology and development to DNA sequence differences. Assaying messenger RNA (mRNA) across a genetic mapping population can act as a stepping stone between the physiology and the DNA. mRNA contains rich amounts of information about the collective outputs of the cells assayed. Or to put it another way, mRNA can provide clues as to what proteins cells are planning to make given the current information from internal developmental and external environmental cues. The collection of mRNA expression is generally referred to as the gene co-expression network. I am interested in understanding the gene co-expression network and how it relates to DNA polymorphisms in one direction and physiological and developmental phenotypes in the other direction. In order to be able to do this, we not only need a good understanding of the biology, but we also need a good understanding of the ways in which these pieces of biological information fit together. I am working on the statistical techniques to connect these pieces of information in a probabilistic framework. This work is in collaboration with Upendra Devisetty who did the bench work using a high-throughput RNA-seq library preparation technique developed in the [Sinha Lab](http://www-plb.ucdavis.edu/labs/sinha/).

### 4) Genetically informed *B. rapa* physiological growth models

I am using this data to parameterize physiologically based models of plant growth. Coming full circle to my PhD work in metabolism and physiology. This is my favorite part of my project. It involves integrating environmental time course data, physiological QTLs, and programming mathematical models of plant growth. Based on my meta-analysis results, and preliminary physiological modeling results, I choose a subset of genotypes to grow in the field for 2014 to test model predictions. The field site I work at is home to three close collaborators at University of Wyoming: [Dr. Rob Baker](http://www.robertlbaker.org/Evolution_and_Development.html), Dr. Marc Brock, and [Dr. Cynthia Weinig](http://www.uwyo.edu/molecbio/faculty-and-staff/cyntia-weinig.html)

Here is a preview of a canopy scale model output predicting peak canopy N content for four different treatments. Notice that there is a clear interaction between N availability and crowding as to when there is peak canopy N. I am currently working on the physiology, metabolomics and RNA-seq samples with four great undergrads: Christina Day, Amanjot Kaur, Lakshmi Pabbisetty, and Neije Mukherjee-Roy.

<img src="/images/physiology_simulations.jpg">

In addition, I am developing a high-throughput 3D imaging robot and analysis pipeline to take non-destructive plant growth data for model calibration/validation. It is really enjoyable to build equipment. It pulls together many ways of thinking about biological problems. It forces the biologist to really think about what process they are trying understand and how to quantify it using some sort of sensor. These projects help biologists build intuition about measurement error, instrument limitation, methods development, materials selection, and design. These are skills that are undervalued in biology.

<figure>
	<img  src="/images/3D_summary.jpg">
</figure>

{% include _vimeoPlayer.html id="108757972" %}

# Graduate Research Projects

During graduate school I was interested in doing a mixture of field, molecular, computational, and engineering projects. Thanks in part to the freedom afforded by a NSF Graduate Research Fellowship, I designed research projects to answer open questions in the climate change literature that incorporated these four components. Here is a copy of [my dissertation](/pdfs/Markelz_PhD_Dissertation_2012.pdf).



### Abstract
The balance between photosynthetic carbon dioxide (CO<sub>2</sub>) assimilation and respiratory CO<sub>2</sub> release influence plant growth, crop yields, and the ability of terrestrial ecosystems to offset ~2-3 Gt CO<sub>2</sub> yr -1 of anthropogenic emissions. Rising atmospheric CO<sub>2</sub> concentration ([CO<sub>2</sub>]) this century will impact plant photosynthesis and respiration with consequences for plant productivity in natural and agro-ecosystems. The capacity of all plants to grow and ecosystems to store carbon in elevated [CO<sub>2</sub>] can be dependent on interactions with water,  nutrients, and plant developmental processes. The purpose of this thesis is to address fundamental knowledge gaps in understanding plant responses to the interaction between elevated [CO<sub>2</sub>] with water, nitrogen (N), and leaf developmental programs: (1) determine what is the mechanistic response of maize C<sub>4</sub> photosynthesis to a three way interaction between atmospheric [CO<sub>2</sub>], N availability and drought utilizing the unique capabilities of a Free Air CO<sub>2</sub> Enrichment (FACE) field experiment; (2) determine the transcriptional reprogramming of leaf respiration in response to growth in elevated [CO<sub>2</sub>] and variable N supply using *Arabidopsis thaliana* and a custom built gas exchange system; (3) determine when in leaf development the transcriptional reprogramming of respiration occurs in response to elevated [CO<sub>2</sub>] by studying the detailed developmental timelines and molecular events of leaf growth in A. thaliana. The knowledge gaps addressed in this work will help inform crop improvement and models that predict future ecosystem function and global food supply in the face of a changing climate.

### Elevated [CO<sub>2</sub>], Nitrogen Availability, and Drought in Maize
C<sub>4</sub> plants, like maize, make up some of the most valued crops and important keystone species in subtropical grassland ecosystems. In C<sub>4</sub> plants, CO<sub>2</sub> is converted into a four carbon acid and pumped from the mesophyll cells into the bundle sheath cells where it is re-released near the site of RUBISCO. This mechanism makes C<sub>4</sub> photosynthesis an efficient way for the plants to fix carbon used in growth processes. C<sub>4</sub> plants are theoretically not suppose to have a stimulation in photosynthetic carbon assimilation when grown in elevated [CO<sub>2</sub>] because of this CO<sub>2</sub> concentrating mechanism. In this paper I designed a field experiment to test the interaction of elevated [CO<sub>2</sub>] and nitrogen availability on maize growth, carbon assimilation and development. I found that elevated [CO<sub>2</sub>] did not provide a benefit to carbon assimilation or growth in either nitrogen treatment early in the field season. A late season drought allowed me to test what the effects of water availability had on these interactions. By merging the field data with a model of C<sub>4</sub> photosynthesis I showed that drought made photosynthetic capacity sensitive to elevated [CO<sub>2</sub>] and that low nitrogen availability exaggerated this difference. [paper](/pdfs/Markelz_etal_2011.pdf)
<figure>
    <img src="/images/C4_photosynthesis_modeling.png">
    <figcaption> Photosynthetic modeling combining field and lab gas exchange data showing CO<sub>2</sub> by nitrogen interaction only in drought conditions. Summary of A/ci response curves and CO<sub>2</sub> supply functions for maize grown at ambient [CO<sub>2</sub>]  (Panels A and C, dashed lines) and elevated [CO<sub>2</sub>]  (Panels B and D, solid lines) as well as high N (black lines) and limiting N (grey lines) during non-drought conditions (panels A and B) or drought conditions (panels C and D). Stomatal limitation (SL) to carbon assimilation was also calculated for each treatment.</figcaption>
</figure>

### Elevated [CO<sub>2</sub>], Nitrogen Availability, and Respiration- in *Arabidopsis thaliana*
Plant respiration is a very important component of plant growth and global carbon cycle, but less studied compared to photosynthesis. This is especially true for night-time dark respiration. There was a great deal of confusion in the literature about whether growth in elevated [CO<sub>2</sub>] would increase, decrease, or not change the dark respiration rates of plants. After conducting a literature review on the topic I found that various papers were not consistent in how they quantified respiration and there appeared to be evidence for an interaction between elevated [CO<sub>2</sub>] and nitrogen availability on plant respiration. I wanted to understand the molecular mechanisms of this interaction so I chose to work with *Arabidopsis thaliana* because of the suite of molecular and genetic tools available. The problem with using *A. thaliana* was that there was no standard equipment to measure leaf respiration in a plant this small so I designed a custom respiration system (see below) in order to very accurately quantify leaf respiratory CO<sub>2</sub> efflux. This new chamber, allowed me show that the elevated [CO<sub>2</sub>] did stimulate leaf respiration regardless of nitrogen availability, but the response was dampened in the limiting nitrogen condition. This finding was supported biochemically and from gene expression micro-array data. [paper](/pdfs/Markelz_etal_2014a.pdf)

<figure>
    <img src="/images/CO2_HN_LN_expression.png">
    <figcaption> Molecular support for biochemical and physiological increase in respiration in elevated [CO<sub>2</sub>]. This figure is a graphical summary of genes encoding components of the TCA cycle and mitochondrial electron transport chain that responded to elevated [CO<sub>2</sub>] during midnight (top) or midday (bottom) and limiting N (left) or ample N (right). Each blue (positive percentage change) and yellow (negative percentage change) represents the mean percentage change of a unique transcript that responded significantly (P < 0.05) to elevated [CO<sub>2</sub>].
    </figcaption>
</figure>

### Elevated [CO<sub>2</sub>], Leaf Development, and Respiration in *Arabidopsis thaliana*
As leaves develop they gradually transition from being a sink tissue to a source tissue. Sink tissues rely on transport of carbon and other nutrient resources from mature source tissues in order to maintain high growth rates through this developmental transition. A majority of the elevated [CO<sub>2</sub>] literature had focused on mature tissues. I was curious if the stimulation in respiration rates that I observed in mature tissues were also occurring in younger tissues. The answer to this question has important implications to how plant respiration is modeled in whole plant growth models. I found that as leaves grew and became source tissues the stimulation in leaf respiration in elevated [CO<sub>2</sub>] increased. This finding was also supported biochemically and from gene expression data. This developmental gradient in respiratory response makes sense in that the mature tissue is best able to incorporate the CO<sub>2</sub> into sugars and that more of that carbohydrate is being respired at night to fuel the whole plant growth stimulation in elevated [CO<sub>2</sub>]. [paper](/pdfs/Markelz_etal_2014b.pdf)
<figure>
    <img src="/images/leaf_respiration_development.png">
    <figcaption> Graph showing the developmental dependency of the leaf respiration response to elevated [CO<sub>2</sub>]. Midnight dark respiration rates (R) of leaf 10 of Arabidopsis thaliana grown at ambient [CO<sub>2</sub>]  (370 ppm) or elevated [CO<sub>2</sub>]  (750 ppm), at 23, 24 (Expanding) or 29, 30 and 31 (Mature) days after germination. Scale bar = 1 cm.
    </figcaption>
</figure>

<!--# Equipment Projects

### Single Leaf Arabidopsis Respiration chamber/pipeline - [paper1](/pdfs/Markelz_etal_2014a.pdf) [paper2](/pdfs/Markelz_etal_2014b.pdf)
...work in progress...

#### Custom LICOR 6400 chamber head for soybean leaf respiration - [paper](/pdfs/Gillespie_etal_2012.pdf)
...work in progress...

#### Fruitfly Respiration[paper](/pdfs/Walters_etal_2012.pdf)
...work in progress...

# Undergraduate Thesis Project
#### How will elevated [CO<sub>2</sub>] alter soil and plant water status of the C<sub>3</sub>-crop soybean and the C<sub>4</sub>-crop maize? -[paper](/pdfs/Hussain_etal_2013.pdf)
...work in progress...
-->
