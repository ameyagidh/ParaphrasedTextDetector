# ParaphrasedTextDetector

### Introduction
The objective of this project is to develop neural network models capable of identifying pairs of rephrased texts. Paraphrasing involves conveying the same message as the original text by rewording or rearranging its content. Detecting such rephrased texts holds significance in various applications, such as spotting duplicate questions on online platforms, assisting in finding answers to similar queries, and detecting plagiarism in academic contexts.

### Dataset
The dataset utilized in this project consists of pairs of sentences, each labeled either as "paraphrased" or "not paraphrased." These datasets—PAWS, Quora Question Pairs (QQP), and MRCP—are publicly accessible and have been employed in previous research endeavors within this domain.

### Methods
Multiple embedding techniques were utilized in the development of neural network models for paraphrase detection. Evaluation metrics, including accuracy, F1 score, precision, and recall, were employed. While prior research exhibited performance ranging from 70% to 80% on the datasets, the models developed in this project demonstrated comparable or superior accuracies, ranging from 65% to 93%.

### Dependencies
- Python version 3.9 or later
- TensorFlow version 2.0 or later
- PyTorch version 2.0
- Transformers
- NumPy
- Pandas
- Scikit-learn

### Usage
1. Clone the repository using the following command:

```
git clone <repository_URL>
```

2. Follow the provided instructions to execute the code.

3. To predict rephrased text pairs using the trained model, execute the final block in the file `BERT/QQP_PAWS_BERT.ipynb`.

### Future Work
To enhance the project further:

1. Optimize the BERT model to address challenges posed by the PAWS dataset by experimenting with different pre-processing techniques, fine-tuning hyperparameters, or incorporating additional methods such as data augmentation.

2. Explore alternative NLP models such as GPT-3, T5, and XLNet, which have shown promise in recent research and may be better suited to handle the challenges presented by the PAWS dataset.

3. Extend the scope of the study to include other paraphrase datasets similar to the characteristics of the PAWS dataset, aiming to improve understanding of the model's performance and generalizability across diverse datasets.

4. Implement ensembling techniques to combine the strengths of various models and enhance overall performance in paraphrase detection tasks.
