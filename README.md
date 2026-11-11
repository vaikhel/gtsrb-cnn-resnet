# GTSRB CNN vs ResNet

Classification of German traffic signs using three different approaches.

## Dataset

- Source: German Traffic Sign Recognition Benchmark (GTSRB)
- Classes: 43
- Task: Multi-class image classification
- Images: ~50,000

## Project Structure
```
gtsrb-cnn-resnet/
├── data/
├── notebooks/
├── src/
├── requirements.txt
└── README.md
```

## Models

Three approaches will be compared:

- Small CNN trained from scratch
- ResNet with frozen backbone
- ResNet fine-tuning