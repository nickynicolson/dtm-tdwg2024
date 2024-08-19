# Deconstructing the monograph

Lightning talk covering Eren Karabey's work on [KewBridge/specimens2illustrations](https://github.com/KewBridge/specimens2illustrations) for the *LTNG02 Diversity and Commonalities of AI Applications to Biodiversity Issues and Data* session at TDWG 2024

## Abstract

Monographs are gold-standard taxonomic outputs, which collate many different kinds of richly interlinked data, evidenced through citation to persistent specimen resources. Advances in collections digitisation and data mobilisation mean that many of these specimen metadata records and images are now available online for linking and reuse. Now that we have this rich - but distributed - set of data, we are interested in the applying machine learning and computer vision techniques to help with species identification.  Accurate, accessible, expert-curated data is crucial for the development of machine learning models. Traditionally monographs have been aimed at the botanical researcher, but the information contained within these publications represents a valuable resource for machine learning researchers. By gathering openly accessible data, it is possible to deconstruct the monograph to a set of multi-modal datasets which interlink (i) species descriptions (enumerating traits) with (ii) specimen images used as reference for the species (as listed in the material examined section) and (iii) scientific illustrations which depict diagnostic features (which are linked to the specimen used as the reference for the illustration). We will describe work on a pipeline process to automate this deconstruction and to populate a machine learning platform with citable datasets to enable different kinds of reuse. We will discuss the potential for the wider application of this technique to a range of different monographic sources.

## Constraints

- Duration:5 minutes

## Compilation

Content is defined in markdown in `presentation.qmd`

A github action uses [quarto](https://quarto.org) to compile this to a powerpoint slidedeck, which is then posted to github pages at: https://nickynicolson.github.io/dtm-tdwg2024/presentation.pptx
