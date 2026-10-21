# FeatureMAP Tutorial

A practical guide to using the FeatureMAP R package and Shiny application.

**[Read the tutorial online](https://tidymass.github.io/featuremap_tutorial/)** ·
**[View the R package](https://github.com/tidymass/featuremap)** ·
**[View the Shiny app](https://github.com/tidymass/featuremap_shiny)**

## About the tutorial

FeatureMAP turns feature-level metabolomics signals into interpretable
metabolic modules. This tutorial covers the complete workflow through two
complementary interfaces:

- **R package:** a reproducible, code-based workflow for analysis and custom
  pipelines.
- **Shiny app:** a guided, point-and-click workflow for interactive analysis
  and result exploration.

Both tracks follow the same analysis logic:

1. Prepare the feature and optional MS2 annotation tables.
2. Annotate metabolite features.
3. Extract a network-supported metabolic subnetwork.
4. Identify and evaluate functional modules.
5. Interpret significant modules and export the results.

## Tutorial contents

| Track | Topics |
|---|---|
| **R package** | Installation, data preparation, feature annotation, PCSF subnetwork extraction, module identification, and functional annotation |
| **Shiny app** | Installation, data upload, interactive execution of each analysis step, result inspection, and export |

The functional annotation chapter also introduces optional PubMed retrieval,
LLM-assisted interpretation, advanced multi-agent debate, and cross-module
synthesis. These services are optional and are not required for the earlier
analysis steps.

## Authors and support

FeatureMAP is developed by
[Yuting Wang](https://ytwangzero.github.io/) and
[Xiaotao Shen](https://www.jaspershenlab.com/) (corresponding author).

For questions, documentation corrections, or feature requests, please
[open an issue](https://github.com/tidymass/featuremap_tutorial/issues).
