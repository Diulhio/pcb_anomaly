# Image-Based Detection of Modifications in PCBs with Deep Convolutional Autoencoders

by
Diulhio Candido de Oliveira
Bogdan Tomoyuki Nassu
Marco Aurelio Wehrmeister

All the codes are available as jupyter notebooks, just copy it and run in the Google Colab and Google Drive :)
Please, note that the training notebooks that use TPUs requires that you upload all .tfrecords files in your own Google Storage.

The dataset is available at: https://github.com/Diulhio/pcb_anomaly/tree/main/dataset

Please cite: http://arxiv.org/abs/2210.00100

```
@article{candido2023image,
  title={Image-Based Detection of Modifications in Assembled PCBs with Deep Convolutional Autoencoders},
  author={Candido de Oliveira, Diulhio and Nassu, Bogdan Tomoyuki and Wehrmeister, Marco Aurelio},
  journal={Sensors},
  volume={23},
  number={3},
  pages={1353},
  year={2023},
  publisher={MDPI}
}
```



## Abstract

In this paper, we introduce a semi-supervised approach for detecting modifications in assembled printed circuit boards (PCBs) based on photographs taken without tight control over perspective and illumination conditions. We take as an instance of this problem the visual inspection of gas pump PCBs, which can be modified by fraudsters wishing to deceive customers or evade taxes. Given the uncontrolled environment and the huge number of possible modifications, we address the problem as a case of anomaly detection, proposing an approach that is directed towards the characteristics of that scenario, while being well-suited for other similar applications. Experiments performed on a dataset built to represent real-world situations (and which we will make publicly available) show that our approach outperforms other state-of-the-art approaches for anomaly segmentation in the considered scenario, while producing comparable results on a more general object anomaly detection task.

## Implementation details

Available soon

## License

TODO

