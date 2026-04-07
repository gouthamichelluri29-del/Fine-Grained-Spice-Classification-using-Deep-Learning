# Fine-Grained-Spice-Classification-using-Deep-Learning
A comparative study of ResNet50 and VGG16 for classifying 
22 visually similar spice categories using transfer learning 
and data augmentation.

## Results
| Model    | Augmentation | Accuracy |
|----------|-------------|----------|
| ResNet50 | No          | 82.19%   |
| ResNet50 | Yes         | 81.51%   |
| VGG16    | No          | 75.34%   |
| VGG16    | Yes         | 72.60%   |

## Tech Stack
- PyTorch, torchvision
- ResNet50, VGG16 (transfer learning)
- scikit-learn, seaborn, matplotlib

## Key Findings
ResNet50 consistently outperformed VGG16, showing stronger 
generalisation across fine-grained spice categories.

## Note
Dataset was independently collected by me and later merged 
with team contributions in a collaborative phase, where we 
collectively deployed the model on a JetBot robot for 
real-world inference. Model implementation and analysis 
are entirely my own work.
