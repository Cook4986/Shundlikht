# Shundlikht
Shundlikht is a Python program (Jupyter Notebook) that automatically transcribes, translates (if you want), and collates the text embedded pdf images associated with each installment of a given work in [the Shund.org database](https://shund.org/). The images associated with each installment are hosted by the [National Library of Israel](https://www.nli.org.il/en).

## Dependencies
* [pandas](https://pandas.pydata.org/)
* [pypdf](https://pypdf.readthedocs.io/en/stable/)
* [Google Cloud Translate](https://cloud.google.com/translate/docs/advanced/translate-documents)

## Usage
1. Create local directory, named after the target Shund.org work
2. Export Shund.org search results associated with work (See: image, below)
3. Place exported CSV in the working directory
4. In ipynb "Globals":
  * Set Google Application Credentials
  * Set "workDir" to working directory pathname
5. "Run All" cells

![](https://shund.org/rails/active_storage/disk/eyJfcmFpbHMiOnsibWVzc2FnZSI6IkJBaDdDVG9JYTJWNVNTSWhNMmgwWjJKelozcDRNekUwZUdaNmREVmljR1pyYjNwM1pXMW1aZ1k2QmtWVU9oQmthWE53YjNOcGRHbHZia2tpQVh4cGJteHBibVU3SUdacGJHVnVZVzFsUFNKVFkzSmxaVzV6YUc5MElESXdNak10TURZdE1UVWdZWFFnT1M0MU5pNHpNaUJCVFM1d2JtY2lPeUJtYVd4bGJtRnRaU285VlZSR0xUZ25KMU5qY21WbGJuTm9iM1FsTWpBeU1ESXpMVEEyTFRFMUpUSXdZWFFsTWpBNUxqVTJMak15SlRJd1FVMHVjRzVuQmpzR1ZEb1JZMjl1ZEdWdWRGOTBlWEJsU1NJT2FXMWhaMlV2Y0c1bkJqc0dWRG9SYzJWeWRtbGpaVjl1WVcxbE9ncHNiMk5oYkE9PSIsImV4cCI6IjIwMjMtMTEtMjJUMTU6NTQ6MDcuMzYxWiIsInB1ciI6ImJsb2Jfa2V5In19--9d3ce558474c0670e52d962a87b9fea21f826d52/Screenshot%202023-06-15%20at%209.56.32%20AM.png)

## TO-DO
* Annotate filepaths with language code extension, if target language differs from source
* Add spelling correction

## Caveats
* Runs locally
* NLI may attempt to block automated requests
* Translation may have errors (in addition to transcriptions)
* GCT (Google) is black-boxed

### Matt Cook - 2023
### [mncook.net](https://www.mncook.net/)
