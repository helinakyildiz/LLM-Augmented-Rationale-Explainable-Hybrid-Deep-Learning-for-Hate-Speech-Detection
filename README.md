# LLM-Augmented-Rationale-Explainable-Hybrid-Deep-Learning-for-Hate-Speech-Detection
# Deep-HateDetect: Sosyal Medya Verilerinde Derin Öğrenme ile Nefret Söylemi Tespiti

Bu proje, sosyal medya (Twitter/X) platformlarındaki nefret söylemlerini otomatik olarak sınıflandırmak için geliştirilmiş, ileri seviye bir Doğal Dil İşleme (NLP) çalışmasıdır. Proje kapsamında LSTM (Long Short-Term Memory) ve BiLSTM (Bidirectional LSTM) mimarileri karşılaştırmalı olarak analiz edilmiştir.

## 📌 Proje Özeti

Günümüz sosyal medya ekosisteminde toksik içeriğin tespiti, platform güvenliği için kritik bir rol oynamaktadır. Bu çalışma, metin verilerini semantik düzeyde anlamlandırarak yüksek doğrulukla sınıflandırmayı hedefler.

### Temel Özellikler
- **Veri Ön İşleme:** Metin temizleme, tokenizasyon ve `pad_sequences` yöntemleriyle veri standardizasyonu.
- **Model Mimarileri:** - Standart LSTM katmanları ile sekans analizi.
  - Çift yönlü bilgi akışı sağlayan BiLSTM katmanları ile bağlamsal derinlik.
- **Performans:** Eğitim ve doğrulama süreçlerinde modelin overfitting (aşırı öğrenme) durumunu izlemek için kayıp (loss) ve doğruluk (accuracy) metriklerinin analizi.

## 🚀 Teknik Detaylar
- **Frameworks:** TensorFlow, Keras, Scikit-learn
- **Dil:** Python
- **Yöntem:** Word Embeddings & Recurrent Neural
- mı


## 📊 Öngörülen Sonuçlar
Yapılan testlerde, BiLSTM modelinin metnin her iki yönündeki bağlamı yakalama yeteneği sayesinde, karmaşık nefret söylemi kalıplarında standart modellere göre daha yüksek F1-skoru sergilediği gözlemlenmiştir.
