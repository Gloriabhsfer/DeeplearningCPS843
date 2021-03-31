# Homework 2 Video Captioning 
## Requirement
- Tensorflow 1.15
- Python 3.6
## Seq2Seq model without Attention

- [Only Seq2Seq](https://github.com/Gloriabhsfer/DeeplearningCPS843/blob/main/hw2/myseq2seq.py)
- Output: [Only Seq2Seq Result]([Only Seq2Seq](https://github.com/Gloriabhsfer/DeeplearningCPS843/blob/main/hw2/myseq2seq.py))
- Bleu Score:0.72454 

## Seq2Seq model with Attention
- [With attention](https://github.com/Gloriabhsfer/DeeplearningCPS843/blob/main/hw2/my_seq2seq.py)
- [result](https://github.com/Gloriabhsfer/DeeplearningCPS843/blob/main/hw2/output.txt)
- Bleu Score:0.699866535

## To run the code:
`sh hw2_seq2seq.sh testing_data/feat output.txt (or final_output.txt)`

Please specify a directory path containing directory feat/ inside with all the .npy files as 2nd argument.
