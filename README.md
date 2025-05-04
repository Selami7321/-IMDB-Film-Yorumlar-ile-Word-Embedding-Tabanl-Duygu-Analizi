# -IMDB-Film-Yorumlar-ile-Word-Embedding-Tabanli-Duygu-Analizi
IMDB film yorumları üzerinden, farklı kelime temsilleri ile sentiment analysis gerçekleştiren NLP sınıflandırma projesi (Naive Bayes, DNN, GloVe + LSTM).

Bu proje, IMDB film yorumları veri seti üzerinde gerçekleştirilmiş bir duygu analizi (sentiment analysis) çalışmasıdır. Projede temel amaç, film yorumlarını olumlu ya da olumsuz olarak sınıflandırmak için farklı kelime temsilleri (embedding) ve makine öğrenmesi/dinamik derin öğrenme modellerinin performansını karşılaştırmaktır.

🔍 Kullanılan Teknikler ve Modeller
🔡 Bag of Words (CountVectorizer) + Naive Bayes

✍️ TF-IDF + Logistic Regression

🤖 Öğrenilebilir Embedding + DNN

📦 GloVe Embedding + LSTM

📈 Değerlendirme Kriterleri
✔️ Karışıklık Matrisi (Confusion Matrix)

📉 ROC Eğrileri ve AUC Skorları

📚 Öğrenme Eğrisi (Learning Curve)

🔎 Word Embedding Görselleştirmesi (TensorBoard ile)

📦 Veri Kümesi
IMDB film yorumları veri kümesi (Keras üzerinden yüklendi veya GloVe uyumlu metin verisi ile dışardan hazırlandı).

Her bir yorum olumlu (1) ya da olumsuz (0) olarak etiketlenmiştir.

⚙️ Proje İçeriği
preprocessing.ipynb: Veri hazırlama ve ön işleme

embedding_models.ipynb: Tüm modellerin eğitimi ve karşılaştırması

visualizations.ipynb: ROC eğrisi, karışıklık matrisi ve öğrenme eğrisi çizimi

tensor.tsv / metadata.tsv: Word Embedding görselleştirme dosyaları
