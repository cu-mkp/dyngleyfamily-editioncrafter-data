[![DOI](https://zenodo.org/badge/574682278.svg)](https://zenodo.org/badge/latestdoi/574682278)

# Old Books, New Attitudes
## Manuscripts & the Intergenerational Movement of Medical Knowledge in Early Modern England

Historians of science agree that something pivotal happened in England in the latter decades of the sixteenth century, as medieval theories about the body or the natural world diminished in the face of new discoveries, new ideas, and a new experimental method. And yet, the reading habits of sixteenth-century English artisans, bureaucrats, merchants, and farmers tell a different story, one that this project seeks to explore. Early modern English people were avid collectors of medieval manuscripts filled with centuries-old texts related to medicine, astrology, agriculture, or craft manufacture. _Old Books, New Attitudes_ seeks to understand why early modern readers valued this medieval knowledge; how generations of readers engaged with these manuscripts over time; and what role these older books played in the development of the new medical sciences. 

The first stage of the project focuses on Trinity College Cambridge MS O.8.35, a later fifteenth-century guide to medical practice and one of at least five Middle English “how-to” manuscripts owned by Henry Dyneley (d. 1589). EditionCrafter will provide the ready-made infrastructure for a digital critical edition of TCC MS O.8.35 that encodes both the medieval origins, materials, and methods of the recipes and instructions original to the manuscript, as well as reader marks and signatures that demonstrate the use and reuse of the manuscript over time. If the prototype edition of TCC MS O.8.35 is a success, _Old Books, New Attitudes_ will produce digital editions of Dyneley’s other medieval manuscripts with the goal of reconstructing Dyneley’s library, and by extension, the sources he mined as author of Wellcome MS 244, a huge compendium of medical, alchemical, and meteorological knowledge. 

The aim of the project is to reconstruct the intergenerational transference of medical and scientific knowledge in books, and to show how medieval sources played an important role in facilitating a culture of scientific exchange and inquiry in early modern England.

## Trinity College Cambridge MS O.8.35

This open-access critical edition is only possible thanks to the digitization efforts of the librarians at Trinity College. TCC MS O.8.35 has been digitized in IIIF format; the link to the IIIF manifest is here: [https://mss-cat.trin.cam.ac.uk/Manuscript/O.8.35/manifest.json](https://mss-cat.trin.cam.ac.uk/Manuscript/O.8.35/manifest.json). Additional information on the manuscript's contents, format, and provenance is available in the Wren Library's [James Catalogue Online](https://mss-cat.trin.cam.ac.uk/Manuscript/O.8.35).

## editioncrafter-data

Data and metadata for an edition created with EditionCrafter, a publication tool for digital critical editions under development by the [Making and Knowing Project](https://makingandknowing.org/) (M&K), [Performant Software Solutions](https://www.performantsoftware.com/), and a number of case-study collaborators. EditionCrafter, under development (2022-2024), is designed to be an open-source, customizable publishing tool that will allow users to deploy their own texts, data, and commentary as low-maintenance digital critical editions. It will enable the creation of static sites that rely on basic well-established technologies and workflows to address issues of longevity, maintenance, sustainability, and cost. For more about this work, see the NSF award announcement: [Crafting an Open Source Digital Publication Tool for the History of Science](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2218218&HistoricalAwards=false).

This project builds upon the publication of *[Secrets of Craft and Nature. A Digital Critical Edition of BnF Ms. Fr. 640](https://edition640.makingandknowing.org/#/)* by the Making and Knowing Project. The underlying software developed for *Secrets of Craft and Nature* will serve as the starting point for EditionCrafter. 

## editioncrafter-data repository

This repository is a template repository for users who plan to use EditionCrafter to create their editions. It contains the basic structure and organization of the files needed as input for the creation of the "folios view" element: the side-by-side viewing panes of the text, where users can choose between versions of the text including facsimile images, transcribed text, and translated text. All associated metadata is also to be housed in this repository.

<img src="https://raw.githubusercontent.com/cu-mkp/edition-webpages/master/images/howtouse-dualpane.png" alt="how-to-use-dualpane" width="500">

> Example of the "folios view," with side-by-side viewing panes of [fol. 4r](https://edition640.makingandknowing.org/#/folios/4r/f/4r/tl) of BnF Ms. Fr. 640 in *Secrets of Craft and Nature*.


## How-tos

Because this repository may be used by beginners, a number of helpful how-tos have been included:
- [Introduction to Git and Github](how-tos/intro-to-github.md)
- [Naming Protocols](how-tos/naming-protocols.md)
- [Setting up Github to Work Locally & General Workflow](how-tos/github-local-setup-and-workflow.md)
- [Command Line Intro and Helpful Commands](how-tos/command-line.md)
- [Project Setup Overview](how-tos/project-setup.md) - reference for project developers

## Repository Structure

This repository has two main areas: 
1. [texts/](texts/) directory - all files associated with an edition's source material (i.e., transcriptions and translations)
2. [metadata/](metadata/) directory - all metadata (data about data) associated with an edition

This is based upon the model used for the creation of *Secrets of Craft and Nature*. M&K's repository for BnF Ms. Fr. 640’s data is [cu-mkp/m-k-manuscript-data](https://github.com/cu-mkp/m-k-manuscript-data) and the “read me” file (scroll down below the file and directory listings on the repo's homepage) describes the repo's structure and how M&K has already worked with Github for *Secrets of Craft and Nature*.
