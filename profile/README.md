## Ajax Multi-Commentary: code, data, and models

Here is a comprehensive list of code, data, and models created during the Ajax Multi-Commentary project (AjMC), a four-year research project funded by the Swiss National Science Foundation ([grant PZ00P1_186033](https://data.snf.ch/grants/grant/186033)).

## Repositories

### Applications
- [ajmc-kodon](https://github.com/AjaxMultiCommentary/ajmc-kodon): Minimal computing implementation of the Ajax multi-commentary platform based on Kōdōn
- [Kōdōn](https://github.com/AjaxMultiCommentary/kodon): Minimal-computing Javascript library built upon Svelte to publish classical commentaries
- [ajmc-elixir](https://github.com/AjaxMultiCommentary/ajmc-elixir): Elixir implementation of the Ajax multi-commentary platform (discontinued)

### Pipeline

- [ajmc-pipeline](https://github.com/AjaxMultiCommentary/ajmc-pipeline): Pipeline to process digitised classical commentaries, implemented in Python
- [ajmc_annotation_utils](https://github.com/AjaxMultiCommentary/ajmc_annotation_utils): Small Python package for dealing with documents annotated in [INCEpTION](https://inception-project.github.io/)
- [inception-recommender](https://github.com/AjaxMultiCommentary/inception-recommender): An external recommender for [INCEpTION](https://inception-project.github.io/) with support for Classics NER

### Data

#### Canonical data

TBA

#### Images

- [ajmc-public-commentaries](https://github.com/AjaxMultiCommentary/ajmc-public-commentaries): Image data of public domain commentaries
- [OCR_artificial_data_sample](https://zenodo.org/records/14840349): Synthetic dataset for multi-script text line recognition (sample)

#### Texts

- [ReadableAjax](https://github.com/AjaxMultiCommentary/ReadableAjax): Basic HTML rendering of critical editions of Sophocles' *Ajax* encoded in TEI/XML
- [ajmc-tei](https://github.com/AjaxMultiCommentary/ajmc_tei): TEI/XML exports of public domain commentaries from the Ajax Multi-Commentary project

### Datasets

- [OCR groundtruth](https://github.com/AjaxMultiCommentary/GT-commentaries-OCR): Ground-truth data for OCR of digitised classical commentaries
- [PLA groundtruth](https://github.com/AjaxMultiCommentary/GT-commentaries-layout): Ground-truth data for PLA of digitised classical commentaries
- [NE-annotated corpus](https://github.com/AjaxMultiCommentary/AjMC-NE-corpus): Annotated corpus to support the tasks of named entity recognition, entity linking and citation mining on classicsl commentaries.
- [Lemma Linkage corpus](https://github.com/AjaxMultiCommentary/lemma-linkage-corpus) (coming soon!): Annotated corpus to support the recognition and linking of commentary lemmas.

### ML Models

- OCR (optical character recognition)
    - [OCR kraken models](https://github.com/AjaxMultiCommentary/OCR-kraken-models)
    - [OCR transformer model](https://github.com/AjaxMultiCommentary/OCR-transformer-model)
- PLA (page layout analysis)
    - [Layout YOLO models](https://github.com/AjaxMultiCommentary/layout-yolo-models)
- Language Models
    - ...
- Task-specific models
    - NER
    - Lemma linkage (recognition)

