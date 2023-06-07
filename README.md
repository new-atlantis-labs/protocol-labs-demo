# protocol-labs-demo

We have built the process to upload data to IPFS and fetch that data for annotation.  In this example, we have uploaded Tara Oceans datasets and annotated them with geographic and atmospheric measurements (temperature and precipitation in particular).
Tara Oceans datasets contain a variety of sequencing results from microorganisms in the ocean Layering atmospheric measurements onto that metagenome data helps give a full picture of the health of the ocean and help to understand the drivers of that health. 

We have built the process for taking annotated data from IPFS and running it through a container on Bacalhau. In this example, we deployed a containerized runtime for the HUMAnN3 metabolic network analysis toolset.  This aims to describe the metabolic potential of a microbial community and its members. This encodes a fingerprint of the health of a systems microbial community.
