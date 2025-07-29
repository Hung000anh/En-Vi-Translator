# En-Vi-Translator

English-Vietnamese Translator

This project implements a neural machine translation (NMT) model that translates English sentences into Vietnamese using the Transformer architecture. The model is trained on a parallel English-Vietnamese dataset and achieves competitive results measured by BLEU scores.

## 📌 Features

* Transformer-based Seq2Seq architecture using PyTorch
* Custom tokenization and vocabulary building
* Training pipeline with early stopping
* Evaluation using both sentence-level and corpus-level BLEU scores
* Greedy decoding for inference
* Pretrained model saving and loading support

## 🔧 Requirements

* Python 3.8+
* PyTorch
* TorchText
* pandas
* matplotlib
* nltk

## 📊 Evaluation Results

**BLEU Score on first 1000 test sentences:** `0.6949849223929432`

## 🔍 Example Translation Results

| Input English                          | Actual Vietnamese                                | Predicted Vietnamese                             |
| -------------------------------------- | ------------------------------------------------ | ------------------------------------------------ |
| i thought you needed the sleep         | tôi nghĩ bạn cần ngủ                             | tôi nghĩ bạn cần giấc ngủ                        |
| you will survive                       | bạn sẽ sống sót                                  | bạn sẽ sống sót                                  |
| he is a doctor and also a novelist     | ông là một bác sĩ và cũng là một tiểu thuyết gia | ông là một bác sĩ và cũng là một tiểu thuyết gia |
| what you were taught is wrong          | những gì bạn đã được dạy là sai                  | những gì bạn đã được dạy là sai                  |
| i shouldve known tom would be here too | tôi cũng nên biết tom cũng sẽ ở đây              | tôi nên biết tom sẽ ở đây quá                    |

## 🚀 Pretrained Model

You can download the pretrained model from [Google Drive](https://drive.google.com/file/d/1T6a-nT56rBbVMK0JkWpTd7pXWTos1mnv/view?usp=drive_link).
