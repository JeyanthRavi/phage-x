# Third-party data notices

The MIT license in this repository applies to the original PHAGE-X software.
It does not replace the terms attached to third-party datasets or reference
sequences included with, or downloaded by, the project.

## PhageHostLearn

PHAGE-X includes selected files from **PhageHostLearn - training and test
data**, Zenodo record [11061100](https://zenodo.org/records/11061100), licensed
under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

Citation:

> Boeckaerts et al., "Prediction of Klebsiella phage-host specificity at the
> strain level," *Nature Communications* (2024).

The included copies are unmodified source-data files. Checksums and individual
source URLs are recorded in `data/phagehostlearn/manifest.json` and
`backend/data/phages/manifest.json`.

## NCBI reference assemblies

Reference assemblies are sourced through NCBI Datasets. Accession, organism,
source URL, and checksums are recorded in the corresponding manifest files,
including `backend/data/species/manifest.json` and
`backend/data/samples/manifest.json`. These records remain subject to their
source database terms and any rights associated with the original submissions.

## Research-use limitation

The presence of a dataset, sequence, model artifact, or ranking result does not
establish biological safety, treatment efficacy, or clinical validity. PHAGE-X
is a research prototype and all outputs require independent laboratory review.
