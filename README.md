# fish_infection_detection

## Data
SalmonScan dataset includes 456 images of fresh fish and 752 images of infected fish from mainly two sources, online and aquaculture salmon firms. Data augmentation methods like rotation, cropping, flipping, and scaling were used to guarantee the dataset's strength and size. The dataset is available via https://data.mendeley.com/datasets/x3fz2nfm4w/1

## Models
This works finetues three DL models: CLIP, ViT and DenseNet201.

## 10-fold Cross Validation Results

### CLIP 
Accuracy: 0.9363 ± 0.0354
Precision: 0.9499 ± 0.0268
Recall: 0.9203 ± 0.0432
F1: 0.9301 ± 0.0386

### ViT
Accuracy: 0.9296 ± 0.0257
Precision: 0.9351 ± 0.0300
Recall: 0.9178 ± 0.0256
F1: 0.9237 ± 0.0274

### DenseNet
Accuracy: 0.9677 ± 0.0159
Precision: 0.9690 ± 0.0156
Recall: 0.9635 ± 0.0181
F1: 0.9656 ± 0.0167
