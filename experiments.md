# EEG CNN Project - Experiment Log

## Experiment 1 - Baseline CNN

- Dataset: EEG Eye State Classification
- Model: 1D CNN
- Preprocessing: StandardScaler normalization
- Train/Test split: 80/20
- Epochs: 10
- Optimizer: Adam
- Loss: Binary Crossentropy

### Result:
- Test Accuracy: 0.73

### Observation:
CNN baseline EEG sinyallerinde temel patternleri öğrenebildi ancak temporal bağımlılıkları modellemede sınırlı kaldı.

# SPRINT 1 — DATA PREPARATION & BASELINE MODEL

## Sprint Goal
EEG Eye State datasetinin hazırlanması ve ilk baseline CNN modelinin oluşturulması.

---

## Completed Work

- EEG Eye State dataset Kaggle üzerinden indirildi ve projeye entegre edildi.
- Veri seti CSV formatında okunarak pandas DataFrame haline getirildi.
- Feature ve label ayrımı gerçekleştirildi.
- StandardScaler kullanılarak veri normalizasyonu yapıldı.
- Train/Test split (%80 / %20) oluşturuldu.

---

## Model

- Model Type: 1D Convolutional Neural Network (CNN)
- Loss Function: Binary Crossentropy
- Optimizer: Adam
- Epochs: 10

---

## Results

- Test Accuracy: 0.73

---

## Observations

- CNN modeli EEG sinyallerindeki temel patternleri öğrenebilmiştir.
- Ancak zaman bağımlı (temporal) ilişkiler tam olarak modellenememiştir.
- Daha gelişmiş modeller (LSTM / SNN) ile performans artırılabilir.

---

## Conclusion

Sprint 1 başarıyla tamamlanmıştır. Baseline model kurulmuş ve referans performans elde edilmiştir.
