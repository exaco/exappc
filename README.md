# ExaPPC
ExaPPC is a large paraphrase corpus consisting of monolingual sentence-level paraphrases using different sources. 

It is the first large-scale paraphrase dataset in Persian that can be used to train state of the art language models like BERT. There are 2.3M labeled sentence pairs in the corpus consisting of 1M paraphrase label and 1.3M non-paraphrase label. Efforts were made manually and semi-automatically to construct this corpus.

The advantages of this corpus compared to the existing ones are the number of pair sentences, sentence Length variation and textual diversity, including formal and dialogue sentences.

## Data
Format of data is as follows:

sentence1, sentence2, label(paraphrase, non-paraphrase), manner(Human-Annotation, Semi-Automatically)

## Results
Our results suggest that ExaPPC will be helpful in a variety of NLP applications like paraphrase detection task.

We fine-tuned ParsBert using presented corpus and developing a paraphrase detection in Persian with an accuracy of 94% on our test data.

## Future Releases
Future releases of ExaPPC will focus on expanding the paraphrase pairs regarding data size usable for paraphrase generation downstream task and increasing the size of related pairs to have a more divergent corpus. Our goal is to provide ExaPPC as a continuous updating and improvement resource.

## Citation
If you are using this dataset, please cite the initial <a href="https://ieeexplore.ieee.org/document/9786243/">paper</a>:

```
@INPROCEEDINGS{9786243,
  author={Sadeghi, Reyhaneh and Karbasi, Hamed and Akbari, Ahmad},
  booktitle={2022 8th International Conference on Web Research (ICWR)}, 
  title={ExaPPC: a Large-Scale Persian Paraphrase Detection Corpus}, 
  year={2022},
  volume={},
  number={},
  pages={168-175},
  doi={10.1109/ICWR54782.2022.9786243}}
  ```
