# Edge Impulse Image Classification: Cup vs Dog

This project uses **Edge Impulse** to build an image classification model that distinguishes between images of **cups** and **dogs** using transfer learning and a phone camera for data acquisition.

---

## 📦 Project Summary

- **Type:** Image Classification
- **Classes:** `cup`, `dog`, and `uncertain`
- **Model:** MobileNetV2 (Transfer Learning)
- **Tools Used:** 
  - [Edge Impulse Studio](https://studio.edgeimpulse.com)
  - Android phone camera for image upload
  - Python (for prediction & testing, optional)

---

## 🧠 Workflow

1. **Data Collection:**
   - Images of cups and dogs were collected using the phone camera via the Edge Impulse app.
   - Minimum 30–50 images per class to improve model accuracy.

2. **Impulse Design:**
   - Image preprocessing (96x96 RGB)
   - Transfer Learning using MobileNetV2

3. **Model Training:**
   - Trained with data augmentation
   - Accuracy validated via confusion matrix and live testing

4. **Model Testing:**
   - Real-time testing done using the Edge Impulse mobile app
   - Some fluctuation observed due to lighting/backgrounds

---

## 🔍 Model Output Example

```python
Predicted class: cup
Confidence: 0.92
