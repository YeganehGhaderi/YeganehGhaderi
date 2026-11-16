## Hi, I'm Yeganeh 👋

Computer Science undergraduate at the **University of Tehran** (GPA 17.56/20).
I'm interested in **deep learning for medical and biological data**, especially imbalanced datasets, and in writing careful, tested, reproducible ML code.

### 🔬 Projects
- **[numpy-autograd](https://github.com/YeganehGhaderi/numpy-autograd)**: a tensor-level autograd engine and neural-network library in pure NumPy (Linear, Dropout, SGD / Momentum / Adam). Verified against PyTorch with 75 tests and CI; an MLP trained with it reaches 89.0% test accuracy on Fashion-MNIST (PyTorch: 88.7%).
- **[DermaMNIST transfer study](https://github.com/YeganehGhaderi/dermamnist-transfer-study)**: does ImageNet pretraining help on small, imbalanced skin-lesion images? A custom CNN vs. ResNet-18 from scratch vs. pretrained ResNet-18, with the training loop, Focal Loss, Grad-CAM and temperature scaling written by hand in PyTorch (37 tests, CI). The pretrained model reached test Macro-F1 0.692 (vs. 0.520 from scratch, 3 seeds); melanoma recall stayed at 0.55, and the official split shares lesions between train and test, documented as a limitation.
- **[Traffic Severity Prediction](https://github.com/YeganehGhaderi/traffic-severity-prediction)**: 4-class severity prediction on 100K imbalanced samples. Leakage-safe pipeline, SMOTE, feature selection (35→25) and SHAP. XGBoost reached Macro F1 0.577 (vs. 0.478 for the linear baseline).

### 🧩 Other
- **[x86-64 To-Do Tracker](https://github.com/YeganehGhaderi/x86-64-todo-tracker)**: command-line to-do app in NASM assembly using raw Linux system calls.

### 📚 Currently studying
Artificial Intelligence · Machine Learning · Theory of Computation

### 🛠 Tools
- **ML:** PyTorch · NumPy · scikit-learn · XGBoost · SHAP · pandas · matplotlib
- **Engineering:** Python · C/C++ · Git · GitHub Actions · pytest · Linux

### 📫 Contact
[Email](mailto:Yeganeh.Ghaderi84@gmail.com) · [LinkedIn](https://www.linkedin.com/in/yeganeh-ghaderi)
