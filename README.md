# ukraine_vs_russia_twitter_sentiment_analysis
Overview
This project analyzes tweets to classify their sentiment as positive, negative, or neutral. Implemented in Python on Google Colab, it leverages natural language processing (NLP) techniques and visualization tools to extract insights from Twitter data.

Key Features
Cleans and preprocesses tweet text for sentiment analysis.
Visualizes word distributions using word clouds for positive and negative tweets.
Performs sentiment analysis using the VADER Sentiment Analyzer.
Summarizes sentiment data into a structured format for easy interpretation.

Python Libraries:
pandas, matplotlib, seaborn: For data manipulation and visualization.
nltk, SentimentIntensityAnalyzer: For NLP and sentiment analysis.

Data Loading and Cleaning:

Load a CSV file containing tweet data with columns like username, tweet, and language.
Preprocess text by removing punctuation, links, and stopwords using the nltk library.
Text Cleaning Function:

Define a clean() function to standardize and stem the text for further processing.
Word Cloud Visualization:

Generate word clouds for the entire dataset, positive tweets, and negative tweets.
These visualizations help identify frequently used words.
Sentiment Analysis:

Use VADER Sentiment Analyzer to calculate sentiment scores (Positive, Negative, Neutral) for each tweet.
Append these scores to the dataset for structured analysis.
Visualization of Sentiment Trends:

Use sentiment scores to extract and visualize word clouds for each sentiment type.

Genel Bakış
Bu proje, tweet'leri pozitif, negatif veya nötr olarak sınıflandırmak için analiz eder. Python kullanılarak Google Colab üzerinde uygulanan bu proje, doğal dil işleme (NLP) tekniklerini ve görselleştirme araçlarını kullanarak Twitter verilerinden içgörüler çıkarır.

Temel Özellikler
Tweet metnini duygu analizi için temizler ve işler.
Pozitif ve negatif tweet'ler için kelime bulutları oluşturarak kelime dağılımlarını görselleştirir.
VADER Duygu Analizörü ile duygu analizi yapar.
Duygu verilerini kolay yorumlama için yapılandırılmış bir biçimde özetler.

Python Kütüphaneleri:
pandas, matplotlib, seaborn: Veri manipülasyonu ve görselleştirme için.
nltk, SentimentIntensityAnalyzer: Doğal dil işleme ve duygu analizi için.
wordcloud: Metin verileri için kelime bulutları oluşturmak amacıyla.

Veri Yükleme ve Temizleme:
username, tweet, ve language gibi sütunları içeren bir CSV dosyası yüklenir.
nltk kütüphanesi kullanılarak noktalama işaretleri, bağlantılar ve durdurma kelimeleri kaldırılarak metin işlenir.

Metin Temizleme Fonksiyonu:
Metni standartlaştırmak ve kök forma getirmek için bir clean() fonksiyonu tanımlanır.

Kelime Bulutu Görselleştirme:
Tüm veri seti, pozitif tweet'ler ve negatif tweet'ler için kelime bulutları oluşturulur.
Bu görselleştirmeler sık kullanılan kelimeleri tespit etmeye yardımcı olur.

Duygu Analizi:
Her bir tweet için duygu skorlarını (Positive, Negative, Neutral) hesaplamak amacıyla VADER Duygu Analizörü kullanılır.
Bu skorlar veri setine eklenir.

Duygu Eğilimlerinin Görselleştirilmesi:
Her duygu türü için kelime bulutları çıkarılır ve görselleştirilir.
