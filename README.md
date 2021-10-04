# Portuguese Fake News Detector Using BERT

This project implements a text classification that reads portuguese news and classify them in "true" or "fake". The dataset used is the Fake.Br Corpus [1], containing 3600 samples os "true" news and 3600 samples of "fake" news.

The language pre-trained model used is BERTimbau - Portuguese BERT [2], a BERT based language model trained on BrWac Corpus [3].

This project uses the BERTimbau pre-trained model and fine tunning for text classification using the Fake.br Corpus using PyTorch.

Using a holdout validation dataset, the trained model's accuracy per class is 92.03% for the class "fake" and 98,77% for the class "true"



# References

[1] Rafael A. Monteiro, Roney L. S. Santos, Thiago A. S. Pardo, Tiago A. de Almeida, Evandro E. S. Ruiz, and Oto A. Vale, “Contributions to the study of fake news in portuguese: New corpus and automatic detection results,” in Computational Processing of the Portuguese Language. 2018, pp. 324–334, Springer International Publishing.

[2] Fabio Souza, Rodrigo Nogueira, and Roberto Lotufo, “BERTimbau: pretrained BERT models for Brazilian Portuguese,” in 9th Brazilian Conference on Intelligent Systems, BRACIS, Rio Grande do Sul, Brazil, October 20-23 (to appear), 2020.

[3] Jorge Wagner, Rodrigo Wilkens, Marco Idiart, and Aline Villavicencio, “The brwac corpus: A new open resource for brazilian portuguese,” 05 2018.
