# EUtilsCookbook

Similar to [NCBI-Hackathons/EDirectCookbook](https://github.com/NCBI-Hackathons/EDirectCookbook), but for [EUtils](https://www.ncbi.nlm.nih.gov/books/NBK25500/). To make it more compatible to most of web services, I assumed the return result should be a JSON file.

## Get taxonomy information from a tax id:

Like division, scientificname, commonname.
``` shell
https://eutils.ncbi.nlm.nih.gov/entrez/eutils/esummary.fcgi?db=taxonomy&id=116153&retmode=json
```

See the result [here](https://eutils.ncbi.nlm.nih.gov/entrez/eutils/esummary.fcgi?db=taxonomy&id=116153&retmode=json).

## Get taxonomy id from a species name:

``` shell
https://eutils.ncbi.nlm.nih.gov/entrez/eutils/esearch.fcgi?db=taxonomy&retmode=json&term=Aethina%20tumida
```

See the result [here](https://eutils.ncbi.nlm.nih.gov/entrez/eutils/esearch.fcgi?db=taxonomy&retmode=json&term=Aethina%20tumida).
