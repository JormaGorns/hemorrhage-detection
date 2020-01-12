# hemorrhage-detection

This repository contains our implementation and training of a combined recurrent-convolutional DNN for intracranial hemorrhage (bleeding inside the brain) detection on CT scans.

![model](docs/model.png)

The architecture that we have developed vastly outperforms the standard convolution-only approach: Our model achieves a recall (that is, it correctly detects bleeding) of 94% compared to a recall of 73% when only using a CNN. The bidirectional recurrent neural network enables our model to incorporate information from CT slices above *AND* below the current slice 

This arc
colab
overview
books?
