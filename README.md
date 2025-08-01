# 🐛 Multi-Class Jute Pest Image Classification (IEEE Published)

This project implements and compares advanced CNN models — **Xception, ResNet-50, and DenseNet-201** — to classify 17 jute pest species. The research has been **published in IEEE** and demonstrates high accuracy and real-world agricultural relevance.

---

## 📄 IEEE Paper

- **Title:** Multi-Class Jute Pest Image Classification Leveraging Advanced CNN Models  
- **Authors:** Prathap V, Abhilash G, Abhinav K, Venkata Sandeep, B M Vineel Eshwar, Shailesh K R  
- **DOI:** *[Pending/To Add]*

---

## 📂 Dataset

- **Samples:** 7,253 images  
- **Classes:** 17 pest types (e.g., Termite, Red Mite, Mealybug, Jute Semilooper, etc.)  
- **Source:** UCI ML Repository  
- **Split:** 70% Train, 20% Val, 10% Test  
- **Preprocessing:** Resize to 224×224, normalization, augmentation (flip, rotate, crop)

---

## ⚙️ Models Compared

| Model         | Accuracy | Precision | Recall | F1-Score | AUC  |
|---------------|----------|-----------|--------|----------|------|
| **Xception**      | **99%**   | 0.95      | 0.96   | 0.95     | 0.98 |
| **ResNet-50**     | 95%       | 0.93      | 0.94   | 0.93     | 0.95 |
| **DenseNet-201**  | 86%       | 0.85      | 0.86   | 0.85     | 0.88 |

---

## 📊 Visual Insights

### Xception:
- Accuracy/Loss ![](figs/xception_acc_loss.png)
- Confusion Matrix ![](figs/xception_cm.png)
- ROC Curve ![](figs/xception_roc.png)

### ResNet-50:
- Accuracy/Loss ![](figs/resnet_acc_loss.png)
- Confusion Matrix ![](figs/resnet_cm.png)
- ROC Curve ![](figs/resnet_roc.png)

### DenseNet-201:
- Accuracy/Loss ![](figs/densenet_acc_loss.png)
- Confusion Matrix ![](figs/densenet_cm.png)
- ROC Curve ![](figs/densenet_roc.png)

---

## 🚀 Future Scope

- Integrate **Vision Transformers (ViT)** or hybrid models  
- Real-time pest monitoring in **smart farms**  
- Deployment on **edge devices or drones**

---

## 📚 Citation

```bibtex
@inproceedings{jute_pest_cnn_2025,
  author    = {Prathap V and Abhilash G and Abhinav K and Venkata Sandeep and B M Vineel Eshwar and Shailesh K R},
  title     = {Multi-Class Jute Pest Image Classification Leveraging Advanced CNN Models},
  booktitle = {IEEE Conference on ...},
  year      = {2025},
  doi       = {Add DOI here}
}
