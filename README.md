# Gene_IC50_Text_Extraction
Collaboration with twoXAR. Extract gene names, IC50/Ki values from text.

The file deep-learn-bio-nlp-master/BC2 Gene Mention Example.ipynb was used to extract gene mentions from parsed_mce_simple.tsv. It outputs a file called simple_eval.eval that contains gene names, locations in the text, and corresponding IDs. Training corpus used is located in bc2gm-corpus-master.

The file Extract_IC50_Combine.ipynb uses nltk parsing and regex to extract information relating to pharmacokinetic properties of each drug candidate--specifically, the metric of measurement (IC50/Ki/EC50) and the value of the metric. It combines this output with the genes extracted to produce a tsv file containing IDs, gene names, metric, and value.
