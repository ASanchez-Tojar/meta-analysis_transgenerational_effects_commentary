[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3549539.svg)](https://doi.org/10.5281/zenodo.3549539)

# Meta-analysis of adaptive "transgenerational" effects: a commentary on [Yin et al. (2019)](https://onlinelibrary.wiley.com/doi/full/10.1111/ele.13373), Ecology Letters.

This project contains the materials for a project testing the generality and robustness of adaptive "transgenerational" effects across species, environments... It re-analyzes a published meta-analytic data set to show that adaptive "transgenerational" effects - more specifically, anticipatory parental effects, despite existing in some species, are not as widespread as generally stated.

This repository contains the data and Rmarkdown code used in the following study:

---

Alfredo Sánchez-Tójar, Malgorzata Lagisz, Nicholas P. Moran, Shinichi Nakagawa, Daniel W. A. Noble, Klaus Reinhold. 2020. The jury is still out regarding the generality of adaptive “transgenerational” effects. Ecology Letters, 23(11):1715-1718. DOI: [10.1111/ele.13479](https://doi.org/10.1111/ele.13479)

---

More information and materials available at the [OSF project](https://osf.io/srjgp/). For any further information, please contact: [Alfredo Sánchez-Tójar](https://scholar.google.co.uk/citations?hl=en&user=Sh-Rjq8AAAAJ&view_op=list_works&sortby=pubdate), email: alfredo.tojar@gmail.com

## Folders:

[`code`](https://github.com/ASanchez-Tojar/meta-analysis_transgenerational_effects_commentary/tree/master/code): contains an Rmarkdown file (`supplementary_information.biblio.rmd`) that corresponds with the supplementary information file. This Rmarkdown file contains all the code used in this project, except some functions, which are available in the R script `functions.R` and imported from within the Rmarkdown file. In addition, the file `Sanchez-Tojar_et_al_commentary.bib` corresponds to all the references used in the study, both the main text and the supplementary information. The folder [`docs`](https://github.com/ASanchez-Tojar/meta-analysis_transgenerational_effects_commentary/tree/master/code/docs) contains the .html version of the supplementary information.

[`data`](https://github.com/ASanchez-Tojar/meta-analysis_transgenerational_effects_commentary/tree/master/data): contains the original data set published by Yin et al. (2019) (i.e. `Yin et al raw data.csv`) together with the final data set used in our study (i.e. `transgenerational.csv`). Additionally, the remaining files are related to the phylogenetic tree and relationships among the species included in the models. For more information, see the [supplementary information](https://asanchez-tojar.github.io/meta-analysis_transgenerational_effects_commentary/supplementary_information.html).

[`docs`](https://github.com/ASanchez-Tojar/meta-analysis_transgenerational_effects_commentary/tree/master/docs): contains the supplementary file of the study. To visualize the html file, click [**here**](https://asanchez-tojar.github.io/meta-analysis_transgenerational_effects_commentary/supplementary_information.html). 

[`figures`](https://github.com/ASanchez-Tojar/meta-analysis_transgenerational_effects_commentary/tree/master/figures): contains the figures available in the main text, and one of the figures included in the supplementary information. The reamining figures of the supplementary information are generated from within the Rmarkdown file. For more information, see the [supplementary information](https://asanchez-tojar.github.io/meta-analysis_transgenerational_effects_commentary/supplementary_information.html).

[`models`](https://github.com/ASanchez-Tojar/meta-analysis_transgenerational_effects_commentary/tree/master/models): contains sets of models run as part of this project. For more information, see the [supplementary information](https://asanchez-tojar.github.io/meta-analysis_transgenerational_effects_commentary/supplementary_information.html).

### Notes:

See details of the licence of this repository in [LICENSE.txt](https://github.com/ASanchez-Tojar/meta-analysis_transgenerational_effects_commentary/blob/master/LICENSE.txt)

21 Jan 2020: a few minor edits have been added to section 3.1 of `supplementary_information.biblio.rmd`. These minor edits consist of commenting some lines of code to make reproducibility of results faster and easier. However, since these minor edits do not modify anything substantially, we have decided not to update this in Zenodo. Apologies for any inconveniences.
