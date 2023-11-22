# Shundlikht
Shundlikht is an Python program (Jupyter Notebook) that, once run locally, automatically transcribes, translates (if you want), and collates the pdf images associated with each installment of a given work in the Shund.org database. The images associated with each installment are hosted by the National Library of Israel (NLI).

## Dependencies
* pandas
* pypdf
* google.cloud

## Usage
1. Make local directory, named after target work
2. Export Shund.org search results (CSV) and place in new folder
3. In "Globals", below:
4. Set Google Application Credentials
5. Set workDir to new folder pathname
6. Choose target language
7. "Run all"

## TO-DO
* annotate filepaths with language code extension, if target language differs from source
* Add spelling correction

## Caveats
* runs locally
* NLI may attempt to block automated requests
* Translation may have errors (in addition to transcriptions)
* GCT (Google) is black-boxed

## Matt Cook - 2023
### mncook.net
