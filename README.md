# Veri Madenciliği Üzerine Bir Araştırma: LDA ile Konu Modelleme Analizi

Bu proje, veri madenciliği tekniklerini kullanarak haber makalelerinden elde edilen bilgileri analiz etmeyi amaçlamaktadır. Temel olarak, **Latent Dirichlet Allocation (LDA)** algoritması ile metin verileri içerisindeki gizli konu yapıları ortaya çıkarılmıştır. Ek olarak, duygu analizi ve zaman serisi analizi gibi yöntemlerle de verinin farklı yönleri incelenmiştir.

## Yazarlar

* **Cansu Kahve** 
* **Melike Tengilimoğlu** 

## Özet (Abstract)

Bu çalışmada, veri madenciliği tekniklerinden Konu Modelleme (Topic Modeling) yöntemi kullanılarak haber makaleleri üzerinden metinler içerisindeki gizli konu yapılarının ortaya çıkarılması amaçlanmıştır. Özellikle Latent Dirichlet Allocation (LDA) algoritması odak noktasıdır. Çalışma kapsamında, belirlenen bir haber makalesi veri seti üzerinde LDA algoritması uygulanarak elde edilen konular analiz edilmiş, model performansı değerlendirilmiş ve referans alınan "Performance analysis of topic modeling algorithms for news articles" başlıklı makalenin bulguları ile karşılaştırılmıştır. Ayrıca, konu modelleme sonuçlarının duygu analizi ve zaman serisi analizi gibi ek analizlerle nasıl zenginleştirilebileceği de incelenmiştir. Elde edilen bulgular, haber makaleleri metinlerinin derinlemesine anlaşılması ve farklı açılardan yorumlanması için konu modellemenin ve ek analizlerin potansiyelini ortaya koymaktadır.

## Amaç

* Haber makalelerindeki gizli konu yapısını LDA algoritması ile belirlemek.
* Konu modelleme sonuçlarını duygu analizi ile zenginleştirmek.
* Zaman serisi analizi ile haber yayın trendlerini incelemek.
* Model performansını değerlendirmek ve referans makale ile karşılaştırmak.

## Kullanılan Teknolojiler ve Kütüphaneler

* **Programlama Dili:** Python
* **Veri Analizi ve İşleme:** Pandas, NumPy
* **Doğal Dil İşleme (NLP):** NLTK, TextBlob
* **Konu Modelleme:** Gensim, pyLDAvis
* **Görselleştirme:** Matplotlib, pyLDAvis

## Veri Seti

Projede kullanılan veri seti, Kaggle'dan temin edilen **BBC News** veri setidir. Bu veri seti, farklı kategorilerdeki haber makalelerini içermektedir.

* **Kaynak:** [Gpreda. (2024). BBC News. Kaggle.](https://www.kaggle.com/datasets/gpreda/bbc-news)

## Kurulum ve Çalıştırma

1.  **Depoyu Klonlama:**
    ```bash
    git clone [DEPO_URL_ADRESİNİZ]
    cd [DEPO_ADI]
    ```
2.  **Gerekli Kütüphaneleri Kurma:**
    Projenin gerektirdiği kütüphaneleri kurmak için aşağıdaki komutu kullanabilirsiniz:
    ```bash
    pip install -r requirements.txt
    ```
    (Eğer bir `requirements.txt` dosyası oluşturmadıysanız, bunu `pip freeze > requirements.txt` komutu ile kolayca oluşturabilirsiniz.)
3.  **Veri Setini Ekleme:** `data` klasörünün içine `bbc_news.csv` dosyasını eklediğinizden emin olun.
4.  **Notebookları Çalıştırma:**
    * LDA Analizi için: `LDA.ipynb`
    * Duygu Durumu Analizi için: `DuyguDurumuAnalizi.ipynb`
    * Zaman Serisi Analizi için: `ZamanSerisiAnalizi.ipynb`

    Bu notebookları Jupyter Notebook, JupyterLab veya Google Colab gibi bir ortamda çalıştırabilirsiniz.
    *Not: Notebook içindeki dosya yolları (`C:\Users\...`) GitHub ortamına uygun olarak `data/bbc_news.csv` gibi göreceli yollara güncellenmelidir.*

## Sonuçlar

* [Burada elde ettiğiniz anahtar konuları ve duygu analizi sonuçlarını özetleyebilirsiniz.]
* [Zaman serisi analizinden elde ettiğiniz trendler hakkında kısa bir bilgi verebilirsiniz.]

## Kaynakça

1.  Rajasundari, T., Subathra, P., & Kumar, P. N. (2017). Performance analysis of topic modeling algorithms for news articles. *Journal of Advanced Research in Dynamical and Control Systems*, *9*(Special Issue 12), 2267-2275.
2.  Gpreda. (2024). BBC News. Kaggle. [https://www.kaggle.com/datasets/gpreda/bbc-news](https://www.kaggle.com/datasets/gpreda/bbc-news)
3.  Gensim. (n.d.). Gensim: Topic modelling for humans. [https://radimrehurek.com/gensim/](https://radimrehurek.com/gensim/)
4.  NLTK. (n.d.). Natural Language Toolkit. [https://www.nltk.org/](https://www.nltk.org/)
5.  Pandas development team. (n.d.). pandas: powerful Python data analysis and manipulation. [https://pandas.pydata.org/](https://pandas.pydata.org/)
6.  NumPy community. (n.d.). NumPy: the fundamental package for scientific computing with Python. [https://numpy.org/](https://numpy.org/)
7.  Matplotlib development team. (n.d.). Matplotlib: Visualization with Python. [https://matplotlib.org/](https://matplotlib.org/)
8.  Sievert, C., & Shirley, K. (2014). LDAvis: A method for visualizing and interpreting topics. *Proceedings of the Workshop on Interactive Language Learning, Visualization, and Interfaces*, 63-70.
