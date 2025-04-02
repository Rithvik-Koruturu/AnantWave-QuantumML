# AnantWave-QuantumML

## Quantum Algorithms & Quantum Machine Learning Implementations in PennyLane

This repository contains Python implementations of popular quantum algorithms and quantum machine learning (QML) techniques using **PennyLane**, a quantum computing library.

### Implemented Quantum Algorithms:
- **Deutsch's Algorithm**
- **Deutsch-Josza Algorithm**
- **Bernstein-Vazirani Algorithm**

### Quantum Machine Learning Additions:
New commits have introduced quantum image encoding techniques for training QML models. These include:

1. **Quantum Image Encoding with Amplitude Encoding**
   - Encodes classical images into quantum states using amplitude encoding.
   - Efficiently represents images for quantum processing.

2. **Feature Extraction and PCA-based Encoding**
   - Extracts essential features from classical images.
   - Uses Principal Component Analysis (PCA) to reduce dimensionality before encoding into quantum states.

3. **Quantum Feature Encoding using VGG16 and Amplitude Embedding**
   - Leverages VGG16 for feature extraction.
   - Converts extracted features into quantum states using amplitude embedding.

## Prerequisites
To run the code, install the following libraries:

- [PennyLane](https://pennylane.ai/)
- [NumPy](https://numpy.org/)
- [TensorFlow](https://www.tensorflow.org/) (for VGG16-based encoding)
- [Scikit-learn](https://scikit-learn.org/) (for PCA-based encoding)

## Explanation of Structure:

### Quantum Algorithm Implementations:
Each algorithm (Deutsch's, Deutsch-Josza, Bernstein-Vazirani, Simon's) has its own section. This includes:
   - **Cell 1**: Defining the quantum device.
   - **Cell 2**: Defining the oracle.
   - **Cell 3**: Writing the quantum algorithm.
   - **Cell 4**: Printing the measurement results.
   - **Cell 5**: Drawing the quantum circuit using `draw_mpl`.

### Quantum Image Encoding Modules:
Each encoding technique has its own module, ensuring clear separation and easy integration into QML models.

2. **Code Snippets**:
   - The code snippets follow a structured format, making it easy to understand each step in quantum encoding and algorithm implementation.

## Contribution & Future Work:
- Additional quantum-enhanced feature extraction methods.
- Hybrid quantum-classical models for image classification.

Stay tuned for more updates!

