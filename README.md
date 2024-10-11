# ResNet50 Transfer Learning on Document Liveness Challenge (DLC-2021) Dataset
This project involves fine-tuning the ResNet50 model, pre-trained on ImageNet, using transfer learning techniques on the Document Liveness Challenge Dataset (DLC-2021). The goal is to classify documents as original, recaptured, or printed documents, which is crucial for identity verification systems and anti-fraud measures.

## Key Features:

**Model**: Fine-tuned ResNet50 with ImageNet weights.

**Dataset**: Document Liveness Challenge (DLC-2021).

**Task**: Liveness detection of documents to differentiate between original, recaptured, or printed documents.

**Transfer Learning**: Leveraged the powerful feature extraction capabilities of ResNet50 by freezing early layers and fine-tuning the deeper layers on the DLC dataset.

**Performance**: This approach achieved a val_accuracy of 0.7762, after 12 epochs on CPU, so it can be optimized.

## Installation and Usage:
1- Clone the repository:
```
git clone https://github.com/qandos-git/Document-Liveness-Detection-using-ResNet50.git
```
2- Install `tensorflow`:
```
!pip install tensorflow
```
3- Fine-tune the model.
## Dataset:
- The DLC-2021 dataset can be downloaded [here](https://www.mdpi.com/2313-433X/8/7/181).
- Make sure to read the data files properly before running them.

