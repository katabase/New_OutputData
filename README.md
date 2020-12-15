# Encoded TEI-XML catalogues

Digitised manuscripts sale catalogues semantically encoded and restructured in the TEI-XML format (level 1).

* `AUC`: auction catalogues;
* `LAC`: _Librairie ancienne et autographes de Charavay_;
* `LAV`: _Catalogue de lettres autographes, manuscrits, documents historiques, etc., d'Auguste Laverdet_.

## Workflow

The PDF scans (images + text layer, i.e. the OCR transcriptions generated from the [Transkribus](https://readcoop.eu/transkribus/?sc=Transkribus) software) were parsed on five levels with the _GROBID-Dictionaries_ API:



![GROBID-API](/Volumes/LaCie/Toolkit/Mirror/New_OutputData/img/GROBID-API.png)

<br> and exported into the document in the TEI-XML format, which was to be corrected manually.

The structure of the document was validated using the pre-existing XML schema

```xml
<?xml-model href="../../_schemas/schema_grobid_output.rng" type="application/xml" schematypens="http://relaxng.org/ns/structure/1.0"?>
<?xml-model href="../../_schemas/schema_grobid_output.rng" type="application/xml" schematypens="http://purl.oclc.org/dsdl/schematron"?>
```



## Cite this repository

Ljudmila Petkovic, Simon Gabay, Matthias Gille Levenson, Alexandre Bartz and Lucie Rondeau du Noyer, _Encoding the manuscripts sale catalogues_, Neuchâtel: Université de Neuchâtel, 2020, [https://github.com/katabase/New_OutputData](https://github.com/katabase/1_OutputData).

## Licence

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Licence Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International Licence</a>.