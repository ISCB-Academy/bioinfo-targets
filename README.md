# Modular, reproducible bioinformatics workflows with the {targets} R package

[![CC BY 4.0][cc-by-shield]][cc-by]

Modern bioinformatics pipelines can be incredibly complex, but all tend to follow a common pattern: they start with raw data, then pass the data through various programs until arriving at a final result. If this is done in an ad-hoc, unorganized fashion, the results may never be reproducible or even worse, unreliable and/or wrong. Pipeline management software is therefore essential to obtain results that are robust and reproducible. The targets R package is a recently developed workflow manager that comes with many excellent features for bioinformatics, including data caching, pipeline-level parallelization, and HPC support. In this hands-on workshop, I will demonstrate how targets can be used in concert with other tools like docker and conda to orchestrate modular, reproducible bioinformatics pipelines. The workshop will feature variant-calling as an example, but the concepts and tools can be applied to nearly any analysis.

Pre-requisites: Basic familiarity with R. Installations of recent versions of R, RStudio, conda, and docker.

Duration: 2 hours

**Time/Date:** June 30, 2022 at 8:30 PM BST 

## Who is this for?

Anybody interested in maintaining bioinformatics pipelines **with R**. There are many pipeline tools available, but I can't tell you which is best for your project. For example, if you mostly do things in python, [snakemake](https://snakemake.readthedocs.io/en/stable/) may be a better alternative, etc. 

This workshop is primarily intended for people who already use R and want to use it to construct and maintain bioinformatics pipelines.

## Format

The workshop is split into two parts:

- Part I will introduce the {targets} R package and demonstrate its basic usage.
- Part II will show how to use {targets} in combination with docker and conda to orchestrate bioinformatics workflows.

## Resources

- [Slides](https://joelnitta.github.io/iscb-targets-intro/)
- [Code repository](https://github.com/joelnitta/targets_vcf_example) for variant calling workflow using {targets}
- Data Carpentry ["Data Wrangling and Processing for Genomics"](https://datacarpentry.org/wrangling-genomics/04-variant_calling/index.html) workshop, basis for the {targets} variant calling workflow
- [Blog post](https://www.joelnitta.com/posts/2021-11-16_r-bioinfo-flow/) describing these methods
- [Collaborative notes](https://docs.google.com/document/d/198SPo_UHiAlUglKvIx-m_t4mBr5jCwGjGoMppbFz_Uc/edit#)

## Objectives

By the end of the workshop, participants will be able to:
- Use basic functions of the {targets} R package
- Write wrapper functions calling programs to run in docker from R
- Use the {targets} R package to construct bioinformatics pipelines

## Not covered

This workshop will **not include**:
- Details about docker
- Details about R
- Thorough explanation of variant calling

## Contributing :hearts:
- If you like it, leave your star in this project :star2:
- If you would like to complain/suggest/contribute to this project, feel free to open a issue :heart_decoration:
- Please follow our [contributing guidelines](https://github.com/ISCB-Academy/bioinfo-targets/blob/main/CONTRIBUTING.md). 

## Citation

If you use any of the materials of this lesson, please cite as:
> Nitta, J.H. 2022. "Modular, reproducible bioinformatics workflows with the targets R package" https://github.com/ISCB-Academy/bioinfo-targets

## License

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg

