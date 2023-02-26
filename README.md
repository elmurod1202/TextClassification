# Text classification dataset and analysis for Uzbek language
Multi-label text classification dataset for Uzbek language and some sourcode for analysis.
This repository contains the code and dataset used for text classification analysis for the Uzbek language. The dataset consists of 512,750 news articles collected from 9 Uzbek news websites and press portals, covering various categories such as politics, sports, entertainment, technology, and others. All text is in Latin script.

## Dataset
The dataset files can be accessed and downloaded from https://doi.org/10.5281/zenodo.7677431 

## Code
The code for text classification analysis is provided in this repository. We used Python programming and scikit-learn libraries for preprocessing and classifying the texts.

## Results
Based on the model performance results, it can be concluded that the logistic regression models work best when both the word level and character level n-grams are considered (by concatenating their TF-IDF matrices). Neural network models, such as RNN and CNN , perform better than rule-based models, and their performance is enhanced by adding specific knowledge of the language, such as pretrained word-embedding vectors. Among the transformer-based models, the monolingual BERTbek model achieved the highest performance with an F1-score of 85.2%, compared to its multilingual counterpart (with 83.4% F1-score). The results of our experiments demonstrate the effectiveness of deep learning models for text classification in the Uzbek language and provide a strong foundation for further research in this area.

## Citation
If you use this or paper in your research, please cite the following paper:

[Kuriyozov Elmurod, Ulugbek Salaev, Sanatbek Matlatipov, & Gayrat Matlatipov. (2023). Text classification dataset and analysis for Uzbek language. 10th Language and Technology Conference: Human Language Technologies as a Challenge for Computer Science and Linguistics (LTC'23), Poznań. Poland.](https://doi.org/10.5281/zenodo.5659638)

## Cite
<pre>
@proceedings{kuriyozov_elmurod_2023_7677431,
  title        = {{Text classification dataset and analysis for Uzbek 
                   language}},
  year         = 2023,
  publisher    = {Zenodo},
  month        = feb,
  doi          = {10.5281/zenodo.7677431},
  url          = {https://doi.org/10.5281/zenodo.7677431}
}
</pre>

## Contact
For any questions or issues related to the dataset or code, please contact [elmurod1202@urdu.uz, ulugbek.salaev@urdu.uz].
