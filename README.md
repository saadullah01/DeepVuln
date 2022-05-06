# DeepVuln
A deep learning based approach to detect vulnerability in C/C++ source code.

## Process
- Pre-train a language model on a large corpus of C/C++ dataset
- Fine-tuning the model for the classification task of ***vulnerability detection*** in C/C++
- Evaluate the model on test dataset

## Resources
**Pre-training Dataset:** C/C++ files from 100 GitHub repositories ([Link](https://drive.google.com/drive/folders/1xjMZR8r7DhtL1Yc8mqyaTGBS6YTjsy_E?usp=sharing))

**Fine-tuning Dataset:** [Draper VDISC Dataset](https://osf.io/d45bw/)

**Model:** [DistilBERT](https://arxiv.org/abs/1910.01108)

**Code:** Project code is available on [this colab notebook](https://colab.research.google.com/drive/1ZNUaFdaPRUBa3vClAeXmv1SQFbe5ahaN?usp=sharing)

**Progress Tracker:** Progress of the project can be tracked through this [GitHub Project](https://github.com/saadullah01/DeepVuln/projects/1)

## References to Online Tutorials
* [Pre-traing BERT](https://huggingface.co/blog/how-to-train)
* [Fine tunning](https://skimai.com/fine-tuning-bert-for-sentiment-analysis/)
