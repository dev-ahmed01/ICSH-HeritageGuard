# Suggested manuscript wording

The repository currently contains a verified public **index of dataset sources**, not a complete public archive of the analysis code and processed outputs. For accuracy, do not describe it as a fully reproducible code-and-processed-data release.

## Repository URL

https://github.com/dev-ahmed01/ICSH-HeritageGuard

## Replace the last part of the Data Availability and Reproducibility section

The original Hall I and Cloister FBG workbooks are available through Zenodo (DOIs 10.5281/zenodo.3256111 and 10.5281/zenodo.3248893). Dataset source links, citations and checksums are indexed at the HeritageGuard GitHub repository. Retrospective analysis code and processed outputs are not yet included in that public repository. The original E1 results remain separate from reconstructed and cross-location results.

## LaTeX (paste into the manuscript)

The original Hall I and Cloister FBG workbooks are available on Zenodo (DOIs 10.5281/zenodo.3256111 and 10.5281/zenodo.3248893) \cite{storm,stormcloister}. The dataset links, source citations and checksums are indexed at \url{https://github.com/dev-ahmed01/ICSH-HeritageGuard}. Retrospective code and processed outputs are not yet deposited in this public repository. Original E1 results remain separate from reconstructed and transfer results.

**Important:** add `\usepackage{url}` in the document preamble if no package already provides `\url`. This is a textual URL without the need to enable `hyperref` or PDF link annotations.

Do not add a repository link that requires Google sign-in or points to an unverified private folder as evidence of public availability.

## To upgrade later to a true code-and-results archive

Once the data-processing scripts, saved feature matrices, split identifiers, prediction records and validation scripts have been selected and checked for publication, upload them as a versioned release. Then update the manuscript wording to describe the materials actually present. Preserve all original E1 limitations when doing so.
