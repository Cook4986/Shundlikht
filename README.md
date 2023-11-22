# Shundlikht
Shundlikht is an Python program (Jupyter Notebook) that, once run locally, automatically transcribes, translates (if you want), and collates the pdf images associated with each installment of a given work in the Shund.org database. The images associated with each installment are hosted by the National Library of Israel (NLI).

## Dependencies
* pandas
* pypdf
* google.cloud

## Usage
1. Create local directory, named after the target Shund.org work
2. Export Shund.org search results associated with work (See: image, below)
3. Place exported CSV in working directory
4. In "Globals", below:
5. Set Google Application Credentials
6. Set workDir to new folder pathname
7. Choose target language
8. "Run all"

![](https://shund.org/rails/active_storage/disk/eyJfcmFpbHMiOnsibWVzc2FnZSI6IkJBaDdDVG9JYTJWNVNTSWhNMmgwWjJKelozcDRNekUwZUdaNmREVmljR1pyYjNwM1pXMW1aZ1k2QmtWVU9oQmthWE53YjNOcGRHbHZia2tpQVh4cGJteHBibVU3SUdacGJHVnVZVzFsUFNKVFkzSmxaVzV6YUc5MElESXdNak10TURZdE1UVWdZWFFnT1M0MU5pNHpNaUJCVFM1d2JtY2lPeUJtYVd4bGJtRnRaU285VlZSR0xUZ25KMU5qY21WbGJuTm9iM1FsTWpBeU1ESXpMVEEyTFRFMUpUSXdZWFFsTWpBNUxqVTJMak15SlRJd1FVMHVjRzVuQmpzR1ZEb1JZMjl1ZEdWdWRGOTBlWEJsU1NJT2FXMWhaMlV2Y0c1bkJqc0dWRG9SYzJWeWRtbGpaVjl1WVcxbE9ncHNiMk5oYkE9PSIsImV4cCI6IjIwMjMtMTEtMjJUMTU6NTQ6MDcuMzYxWiIsInB1ciI6ImJsb2Jfa2V5In19--9d3ce558474c0670e52d962a87b9fea21f826d52/Screenshot%202023-06-15%20at%209.56.32%20AM.png)

## TO-DO
* annotate filepaths with language code extension, if target language differs from source
* Add spelling correction

## Caveats
* runs locally
* NLI may attempt to block automated requests
* Translation may have errors (in addition to transcriptions)
* GCT (Google) is black-boxed

### Matt Cook - 2023
### [mncook.net](https://www.mncook.net/)
