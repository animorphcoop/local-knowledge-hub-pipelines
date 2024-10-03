# Local Knowledge Hub Pipelines

Fork from https://github.com/open-webui/pipelines to experiment with RAG pipelines at a Co-op Hackathon:
* local-dir_pipeline reading a directory with pdfs or other files
* pipelines/website_pipeline.py reading a set of webpages
* pipelines/coop-data_pipeline.py: reading a csv file containing an open directory of co-operatives (e.g. on https://www.uk.coop/resources/open-data — licensed under ODC-by v1.0). It stores the index once built and just loads it afterwards

Requires downloading data and/or specifying html webpage addresses in those scripts. 