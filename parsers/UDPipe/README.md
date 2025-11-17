# Classical Armenian UDPipe 2 Model

The Classical Armenian model `classical_armenian-caval-ud-2.15-241121` is part of the **Universal Dependencies 2.15 Models** release and is distributed under the **CC BY-NC-SA** licence.  
The model is available via the UDPipe 2 **REST service** at: https://lindat.mff.cuni.cz/services/udpipe/

Below are the official evaluation results on the UD test set:

| Model                                      | Mode              | Words | Sents | UPOS  | XPOS | UFeats | AllTags | Lemma | UAS   | LAS   | MLAS  | BLEX  |
|-------------------------------------------|-------------------|:-----:|:-----:|:-----:|:----:|:------:|:-------:|:-----:|:-----:|:-----:|:-----:|:-----:|
| classical_armenian-caval-ud-2.15-241121   | Raw text          | 98.80 | 60.28 | 97.16 | —    | 94.95  | 94.10   | 97.40 | 82.79 | 79.50 | 68.83 | 73.76 |
| classical_armenian-caval-ud-2.15-241121   | Gold tokenization | —     | —     | 98.23 | —    | 96.05  | 95.13   | 98.49 | 88.81 | 85.30 | 73.40 | 78.39 |

## Acknowledgments

The models have been developed as part of the "CAVaL: Classical Armenian Valency Lexicon" project funded by the Deutsche Forschungsgemeinschaft (DFG), project number 518003859.

We are grateful to Milan Straka for his assistance with the code and for modifying scripts to accommodate the specific requirements of our model.

## Contact
For any questions or assistance regarding the deployment and use of the model, please contact [Lilit Kharatyan](https://www.phil.uni-wuerzburg.de/en/vgsp/team/lilit-kharatyan/).
