# Local Knowledge Hub Pipelines

Fork from https://github.com/open-webui/pipelines to experiment with RAG pipelines at a Co-op Hackathon:
* pipelines/local-dir_pipeline reading a directory with pdfs or other files
* pipelines/website_pipeline.py reading a set of webpages
* pipelines/coop-data_pipeline.py: reading a csv file containing an open directory of co-operatives (e.g. on https://www.uk.coop/resources/open-data — licensed under ODC-by v1.0). It stores the index once built and just loads it afterwards


# Usage

install requirements:
```python
pip install -r requirements.txt
```

Download data in data/ and add links to data or webpages is the three above scripts.

Adapt the scripts for your use cases.
