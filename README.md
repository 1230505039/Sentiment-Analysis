# Vibe Coding Sentiment Analysis Projesi

## Proje Hakkında

Bu proje, Twitter API'si kullanılarak belirli bir konu veya hashtag üzerine çekilen tweetlerin duygu analizi (sentiment analysis) yapılmasını amaçlamaktadır. Python dili ile geliştirilmiş olan bu projede; **Tweepy**, **Pandas**, **VADER Sentiment Analyzer**, **Matplotlib** ve **Seaborn** kütüphaneleri kullanılarak verilerin çekilmesi, işlenmesi, analiz edilmesi ve görselleştirilmesi sağlanmaktadır.

Ayrıca, projede **Vibe Coding** yaklaşımı benimsenmiştir. Yani, katı metodolojilerden ziyade esnek, yaratıcı ve deneysel bir kodlama süreciyle hızlı prototipleme yapılmaktadır.

## Özellikler

- **Tweet Çekimi:** Twitter API aracılığıyla belirlenen bir sorgu (örn. "Maldini") üzerinden tweetler çekilir.
- **Veri İşleme:** Çekilen veriler Pandas DataFrame formatına dönüştürülerek analiz için uygun hale getirilir.
- **Sentiment Analizi:** VADER kullanılarak her tweet için duygu skorları hesaplanır ve tweetler pozitif, negatif veya nötr olarak sınıflandırılır.
- **Görselleştirme:** Analiz sonuçları Matplotlib ve Seaborn kullanılarak grafiklerle sunulur.
- **Rate Limit Yönetimi:** Twitter API'nin istek sınırları kontrol edilerek, aşım durumunda bekleme mekanizması devreye sokulmuştur.
- **Vibe Coding Yaklaşımı:** Esnek ve deneysel kodlama yöntemleriyle, anlık geri bildirim ve hızlı iterasyon sağlanmaktadır.

## Kullanılan Teknolojiler ve Kütüphaneler

- **Python 3.x**
- **Tweepy:** Twitter API ile iletişim için.
- **Pandas:** Veri işleme ve analiz için.
- **VADER Sentiment Analyzer:** Metin duygu analizi yapmak için.
- **Matplotlib & Seaborn:** Veri görselleştirme için.
- **Time:** API rate limit yönetimi için.

## Kurulum

### Gereksinimler

Projeyi çalıştırmak için aşağıdaki kütüphanelerin sisteminizde yüklü olması gerekmektedir:

- Python 3.x
- tweepy
- pandas
- vaderSentiment
- matplotlib
- seaborn

### Adımlar

1. **Proje Dosyalarını Klonlayın:**

   ```bash
   git clone https://github.com/kullanici_adiniz/proje_adi.git
   cd proje_adi
   ```

2. **Sanal Ortam Oluşturun (Opsiyonel):**

   ```bash
   python -m venv venv
   source venv/bin/activate  # Windows için: venv\Scripts\activate
   ```

3. **Gerekli Kütüphaneleri Yükleyin:**

   ```bash
   pip install tweepy pandas vaderSentiment matplotlib seaborn
   ```

4. **API Anahtarlarınızı Ayarlayın:**

   Projede yer alan `vibecoding.py` dosyasında, `YOUR_API_KEY`, `YOUR_API_SECRET` ve `YOUR_BEARER_TOKEN` alanlarını kendi Twitter API bilgilerinizle güncelleyin.

## Kullanım

Projeyi çalıştırmak için terminal veya komut satırında proje dizinine gidip aşağıdaki komutu çalıştırın:

```bash
python vibecoding.py
```

Bu komut, belirlediğiniz sorgu için tweetleri çekecek, duygu analizini yapacak ve sonuçları grafikler aracılığıyla görselleştirecektir.

## Vibe Coding Yaklaşımı

"Vibe Coding", geleneksel yazılım geliştirme süreçlerinin katı kurallarına bağlı kalmadan, daha esnek, yaratıcı ve sezgisel kodlama yöntemlerini benimsemektir. Bu projede:

- **Esnek Prototipleme:** Veri çekme, işleme ve analiz süreçlerinde hızlı deneyler yapılarak en uygun yöntemler belirlenmiştir.
- **Yaratıcılık:** Kodlama süreci sırasında standart kalıpların dışına çıkılarak geliştiricinin anlık ilhamı ve içgüdüleri ön planda tutulmuştur.
- **Dinamik İterasyon:** Geliştirme sürecinde sık sık ara sonuçlar alınarak, bu sonuçlara göre kodda gerekli değişiklikler yapılmıştır.

Bu yaklaşım, özellikle fikirlerin hızla test edilmesi ve prototip geliştirme aşamalarında önemli avantajlar sağlar; ancak, büyük ölçekli projelerde dokümantasyon ve yapılandırılmış süreçlerin eksikliği dezavantaj oluşturabilir.

## Katkıda Bulunma

Projeye katkıda bulunmak isterseniz, aşağıdaki adımları takip edebilirsiniz:

1. Bu projeyi fork'layın.
2. Yeni bir branch oluşturun (`git checkout -b yeni_ozellik`).
3. Değişikliklerinizi commit edin (`git commit -m 'Yeni özellik ekledim'`).
4. Branch'i GitHub'a push edin (`git push origin yeni_ozellik`).
5. Bir pull request oluşturun.
---

Herhangi bir sorunuz veya geri bildiriminiz olursa, lütfen iletişime geçmekten çekinmeyin.
```
