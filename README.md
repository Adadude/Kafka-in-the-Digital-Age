# BachelorThesis

## Requirements

Install the Python libraries used by the corpus construction and sub-study scripts:

```bash
pip install -r requirements.txt
```

`torch` can be installed with either CPU support or the CUDA version appropriate for your system. See the official PyTorch installation instructions if you want GPU acceleration for the GLiNER or BERTopic analyses.

DISCLAIMER:
The Kafka Corpus is not included within this repository. To gain acess to it, refer to Prof. Dr. Manuel Burghardt @Uni Leipzig. When downloaded, it should be named
"KafkaCSV.zip" and be located within "..\Kafka_GoodReads\KafkaCSV.zip"

To run the corpus preproccessing code, run this in the terminal: ".\run_corpus.bat" 

To run the sub studies, run this in the terminal: ".\run_sub_studies.bat"

the automatition script requires that the project runs on a virtual enviroment. This can be done by running "python -m venv .venv", be sure to install all the required packages to the virtual enviroment and not to the global enviroment as that can lead to conflicts with local installs. 

The scripts for the thesis can be found within the "annotated" folder.

The "Corpus_Construction" folder contains the scripts required to preprocess the given Kafka Corpus.

The folders "Sub_Study_1", "Sub_Study_2", and "Sub_Study 3" contain the necessary scripts and information required to run the individual sub_studies.

For further information on the codes, refer to "Code_Documentation.pdf".
