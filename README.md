# Single-Image-Super-Resolution

<img src="/overall.jpg" style="margin: 10px;">

This is the official implementation of our paper [Single Image Super-Resolution using Residual Channel Attention Network](https://doi.org/10.1109/iciis51140.2020.9342688).

Abstract: Single Image Super-resolution refers to the method of converting one low-resolution image to its high-resolution counterpart which is a very challenging task since a low-resolution image can yield several possible high-resolution images. Super-resolution has applications in several paradigms like biomedical engineering, face recognition, satellite imaging among others. Several techniques exist in literature with recent research focusing on using deep convolutional neural networks along with residual learning techniques for enhancing performance. In this paper, we propose a deep learning-based approach for the problem, wherein we use a fully convolutional attention network coupled with residual in the residual block (RIR), Residual Channel Attention Block (RCAB), and long and short skip connections. The RIR block allows us to bypass the redundant low-frequency features and focuses on the important high-frequency information. We have used the DIV2k dataset for training our network and then tested our model on five publicly available datasets for validating our results: Set5, Set14, B100, Manga109, and Urban 100. The proposed methodology achieves commendable results compared to other existing deep learning-based methodologies in this domain.

## Requirements

To install the dependencies, run the following using the command prompt:

`pip install -r requirements.txt`

## Citation

If this repository helps you in any way, consider citing our paper as follows:
```
@inproceedings{basak2020single,
  title={Single Image Super-Resolution using Residual Channel Attention Network},
  author={Basak, Hritam and Kundu, Rohit and Agarwal, Anish and Giri, Shreya},
  booktitle={2020 IEEE 15th International Conference on Industrial and Information Systems (ICIIS)},
  pages={219--224},
  year={2020},
  organization={IEEE}
}
```
