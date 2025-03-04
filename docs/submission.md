---
layout: default
title: Submission process
nav_order: 5
---

# Submission process

This year DaMaLOS welcomes submissions in the form of long (up to 12 pages) and short (up to 6 pages) research papers, research objects (up to 3 pages), position papers (up to 6 pages), demos (up to 3 pages), posters (up to 3 pages). References are not counted within the page limit. Please use numbered citations in sequential order, e.g., APA style, and whenever possible add a (DOI) link.

Accepted papers will go to the proceedings of the workshop and will be publicly available under CC-by 4.0 license at [PUBLISSO FRL](https://repository.publisso.de/){:target="_blank"} indexed by [LIVIVO](https://www.livivo.de/) and [DBLP](https://dblp.org/search?q=damalos). PUBLISSO mints DOIs and provides a fast publication process that will allow us to have the proceedings ready right after the conference, including slides. Accepted workshop papers aligned with Life Sciences or domain-agnostic will be later invited to submit an extended and improved version to the Journal of Biomedical Semantics ([JBMS](./jbms)).

### Types of submissions
* Full research papers (up to 12 pages): Presenting novel scientific research
* Short research papers (up to 6 pages): Presenting research results at early stages
* Position papers (up to 6 pages): Introducing positions, ideas, opinions and discussions around a topic
* Research objects (up to 3 pages): Describing datasets, software, workflows, training materials together with their metadata
* Demos (up to 3 pages): Presenting tools (software, workflows and so) from a practical perspective
* Posters (up to 3 pages): Presenting works in a graphical display

**Note 1:** If your submission refers to other research artifacts produced as part of the research you are reporting about, e.g., datasets, software releases, workflows, machine learning models, we encourage you to deposit those research artifacts into repositories so they are recognized on their own with citation details and corresponding identifier. During the camera-ready process, we will ask you some additional information about those resaerch artifacts so we can include it as part of the embedded JSON-LD providing metadata for each accepted paper. Below you can see an example of the metadata that we have provided in previous years.

```
{ 
  "@context": "https://schema.org", 
  "http://purl.org/dc/terms/conformsTo": "https://bioschemas.org/profiles/ScholarlyArticle/0.3-DRAFT", 
  "@type": "ScholarlyArticle", 
  "@id": "https://doi.org/10.4126/FRL01-006423950", 
  "identifier": "DOI:10.4126/FRL01-006423950", 
  "name": "Keynote: The swings and roundabouts of a decade of fun and games with Research Objects", 
  "headline": "Keynote: The swings and roundabouts of a decade of fun and games with Research Objects", 
  "publisher": "https://repository.publisso.de/", 
  "isPartOf": { "@id": "https://d-nb.info/gnd/121881389X" }, 
  "license": "https://creativecommons.org/licenses/by/4.0/" 
}
```

**Note 2:** This year, in addition to the regular text-based PDF article, you also have the opportunity to submit, if you wish, a more machine-readable format of your submission. This could be, for instance, an editable text-based file or a [nanopublication](https://nanopub.net/). Bundle the files together as a ZIP file. Accepted contributions will include all the files that you submit (if any the file is bigger than a couple of GB, we will contact you to figure it out how to proceed).

### Guidelines
All submissions must be original and not simultaneously submitted to another journal or conference/workshop. All submissions must be in English. Proceedings of the workshop will be publicly available under [CC-by 4.0 license](https://creativecommons.org/licenses/by/4.0/){:target="_blank"}; by submitting you agree to the use of this license for accepted papers. Papers should be formatted according to [LNCS templates](https://www.springer.com/gp/computer-science/lncs/conference-proceedings-guidelines){:target="_blank"}.

### Submission system
All workshop submissions should be done via [DaMaLOS-2025 submission system](https://app.oxfordabstracts.com/stages/77706/submitter){:target="_blank"}

## Topics
 DaMaLOS targets the following (and similar) topics:

* Research management
  * Importance, automatization and connections across Research Data and Software (and other digital objects) Management for Linked Open Science (LOS,  i.e., Open Science + Linked Open Data principles)
  * Special features/metadata required in research management plans for LOS
  * Extensions to current RDM plans to better support LOS
* FAIRness and FAIRification
  * Integration/alignment between FAIR and research management plans
  * FAIRification processes, either by design or post-research-object creation
  * FAIR tooling, e.g., evaluators, extensions, governance
  * RO-Crates, Signposting and FDOs
* Open Science and Scientometrics
  * Benefits of LOS over Open Science
  * How research plans and LOS can be used to improve collection and storage of (usually volatile) data produced at, e.g., conferences
  * Integration of software, data, and other research outcomes into science-related metrics
