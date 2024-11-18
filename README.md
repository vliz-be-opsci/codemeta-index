# codemeta-index

This repository will list files containing links to Git repositories with codemeta.json files in them.
This repository will have a GitHub action (to be created) that will:
1. download all the mentioned codemeta.json files,
2. semantically uplift them to triples, effectively building a knowledge graph version of this registry of softwares, 
3. generate a static website (possibly with a dynamic react component) that allows browsing, searching and navigating the combined knowledge graph. 
