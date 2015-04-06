This repository is for the collection of species-specific stage
ontologies.

STATUS: Alpha - some of the links below will not work until purls are registered

This repository is primarily for the developers of these
ontologies. End-users should access these ontologies via their standard
purls; for example:

  * http://purl.obolibrary.org/obo/zfs.obo
  * http://purl.obolibrary.org/obo/zfs.owl

Or via dedicated web interfaces (e.g. ZFIN) or OntoBee
(e.g. http://purl.obolibrary.org/obo/ZFS_0000044 )

Currently this repository is the source for the following stage ontologies:

  * MmusDv (mouse) (purl not yet registered)
  * HsapDv (human) (purl not yet registered)
  * OlatDv (medaka) (purl not yet registered)
  * ZFS (zebrafish) - [Browse](http://purl.obolibrary.org/obo/ZFS_0100000)

The following stage ontologies maintain their source in separate repositories:

  * [FBdv (Drosophila)](http://purl.obolibrary.org/obo/fbdv) - [browse](http://purl.obolibrary.org/obo/fbdv/FBdv_00005259)
  * WBls (C elegans) - [browse](http://purl.obolibrary.org/obo/WBls_0000002)
  * plants - see http://www.plantontology.org - [browse](http://purl.obolibrary.org/obo/PO_0009012)
  * Xenopus (stages are part of anatomy ontology XAO) [browse](http://purl.obolibrary.org/obo/XAO_1000000)

## Uses of Staging Ontologies ##

These stages are primarily used to connect anatomical structures to start/end stages

## Note on mammalian stage ontologies ##

Currently EMAPA and EHDAA2 uses stages without an explicit namespace (they follow the form TSnn or CSnn). These will be mapped to mmusdv and hsapdv.

We also provide a combined mammalian stage ontology that includes uberon core stages, mmusdv and hsapdv:

  * http://purl.obolibrary.org/obo/uberon/subsets/life-stages-mammal.owl

## Multi-species stage ontologies ##

Uberon includes a generic staging ontology (building on work by BILA and Bgee)

**Documentation: http://purl.obolibrary.org/obo/uberon/docs/Modeling-developmental-stages**

Two versions are available here:

  * http://purl.obolibrary.org/obo/uberon/subsets/life-stages-core.obo
  * http://purl.obolibrary.org/obo/uberon/subsets/life-stages-core.owl
  * http://purl.obolibrary.org/obo/uberon/subsets/life-stages-composite.obo (OWL available soon)

The core includes only high-level grouping classes (`zygote stage`,
`gastrula stage`, `embryonic stage`, etc).

The composite version includes species-specific stages hanging off as
leaf nodes from the generic stages. No attempt is made to map stages
at a more granular level (e.g. between human Carnegie and mouse
Theiler).

These ontologies are described here:

  * http://purl.obolibrary.org/obo/uberon/references/reference_0000036

## Guidelines for contributors of stage ontologies ##

See [ContributorGuidelines](ContributorGuidelines.md)

## Recordining Timing Information ##

See [Timings](Timings.md)

## Stage Relations ##

See [Relations](Relations.md)

## Papers and Presentations ##

  * [RCN presentation on stages in PO](http://www.slideshare.net/rlwalls2008/po-development-stages-jan2014)
  * Osumi-Sutherland, et al. [The Drosophila phenotype ontology.](http://www.biomedcentral.com/content/pdf/2041-1480-4-30.pdf) Journal of biomedical semantics 4.1 (2013): 30. (this paper describes use of FBdv to classify embryonic lethal phenotypes)