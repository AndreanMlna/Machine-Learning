# Machine-Learning

# Transfer Learning for Image Classification (Lions vs cheetahs)

This project demonstrates transfer learning using pre-trained models (VGG16, ResNet18, and MobileNetV2) to classify images into two classes: donkey and horse.

## 📁 Dataset
- Custom dataset with at least 100 images per class.
- Data split: 70% train, 30% validation.
- Preprocessing: Resize to 224x224, normalization, and augmentation.

## 🔧 Models Used
- **VGG16**: High accuracy but prone to overfitting.
- **ResNet18**: Fast convergence and stable validation.
- **MobileNetV2**: Lightweight and efficient, suitable for mobile deployment.

## 📊 Results

| Model       | Final Train Acc | Final Val Acc |
|-------------|------------------|----------------|
| VGG16       | 100%             | 92.5%          |
| ResNet18    | 100%             | 90.0%          |
| MobileNetV2 | 100%             | 90.0%          |

## 🧠 Transfer Learning Benefits
- Reuse of learned features from ImageNet.
- Faster training on smaller datasets.
- Better generalization with fewer resources.

## 📦 Requirements
- Python 3.x
- PyTorch
- torchvision
- matplotlib

## 🚀 Run the Training
```bash
python train.py
