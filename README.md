# Boosting Multimedia Recommendation via Separate Generic and Unique Awareness

The code and datasets of our paper "Boosting Multimedia Recommendation via Separate Generic and
Unique Awareness"

# Overview

We propose a Separate Alignment aNd Distancing framework (SAND) for multimedia recommendation, which concurrently learns both modal-unique and -generic representation to achieve more comprehensive items representation. First, we split each modal feature into generic and unique part. Then, in the alignment module, for better integration of semantic information between different modalities , we design a SoloSimLoss to align generic modalities. Furthermore, in the distancing module, we aim to distance the unique modalities from the modal-generic so that each modality retains its unique and complementary information. In the light of the flexibility of our framework, we give two technical solutions, the more capable mutual information minimization and the simple negative ℓ2 distance. Finally, extensive experimental results on three popular datasets demonstrate the effectiveness and generalization of our proposed framework.

# Requirements

The model is implemented using PyTorch. The versions of packages used are shown below.

- numpy==1.18.0
- scikit-learn==0.22.1
- torch==1.6.1

# Data Preparation


Corresponding to MMRec.

# Special Thanks

Special thanks to [MMRec](https://github.com/enoche/MMRec)

# Quick run

```js
python main.py
```

# Open Source Log

We open-source the training and testing logs, as well as the logs that SAND plugs into other classical methods (VBPR, FREEDOM) to facilitate a deeper understanding of our SAND.
