# Scenic

**Scenic** is a project that utilizes transfer learning with a pretrained ResNet model using TensorFlow/Keras for classifying natural scene images. The project leverages the **Intel Image Classification Dataset** for training and evaluation.

## Features

- Built using TensorFlow/Keras.
- Employs transfer learning with pretrained ResNet weights for efficient feature extraction.
- Classifies natural scenes into six categories: *buildings, forest, glacier, mountain, sea,* and *street*.

## Dataset

- **Intel Image Classification Dataset**  
  The dataset contains natural scene images divided into six categories.

  Dataset source: [Intel Image Classification Dataset](https://www.kaggle.com/datasets/puneet6060/intel-image-classification)

## Results

- ResNet50 with transfer learning achieved **92% accuracy** on the test dataset.

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE.txt) file for more details.

## Acknowledgments

- Dataset by [Intel](https://www.kaggle.com/datasets/puneet6060/intel-image-classification).
- Pretrained ResNet weights from [Keras Applications](https://keras.io/api/applications/).
- ResNet architecture: *"Deep Residual Learning for Image Recognition"*.

