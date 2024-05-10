## KURAL TABANLI MÜŞTERİ SEGMENTASYON ANALİZİ (RULE BASED CUSTOMER SEGMENTATION PROCESS)

- Müşteri Segmentasyon Süreci, müşterilerin benzer özelliklere, ihtiyaçlara ve davranışlara göre gruplandırılması / segmente edilmesi ve her gruba özel pazarlama stratejilerinin oluşturulmasını içerir.

- Müşteri segmentini çeşitli kurallara göre oluştururuz. Örneğin müşterinin yaşı, yaşadığı şehir, harcama tutarına göre segment oluşturabiliriz. 

- Müşteri segmentasyonunun amacı, yeni müşterilerin hangi segmentte yer aldığını belirleyerek, pazarlama stratejilerini desteklemek ve bu müşterilerin ortalama getiri beklentisini hesaplamaktır.

______________________________


### 1. İŞ PROBLEMI / PROJE HEDEFİ

Bir oyun şirketi, müşteri özelliklerine dayanarak, seviye tabanlı yeni müşteri tanımları (persona) oluşturmayı ve bu tanımlara göre müşterileri segmentlere ayırmayı amaçlıyor.
Ardından, bu segmentlere göre potansiyel yeni müşterilerin, şirkete ortalama gelir getirisini tahmin etmek istiyor.

Örneğin: Türkiye’den IOS kullanan 25 yaşındaki bir erkek kullanıcının, ortalama getirisinin belirlenmesi hedefleniyor.

Proje Hedefleri:
- Müşterileri ortak özelliklere göre segmentlere ayırmak
- Her müşteri segmentinin potansiyel gelirini tahmin etmek
- Şirketin pazarlama stratejilerine destek olmak için aydınlatıcı bilgiler sağlamak


______________________________

### 2. PROJE AŞAMALARI


- Veri setinin incelenmesi ve anlaşılması
- Veri manipülasyonu
- Müşteri tanımlarına göre segmentlerin oluşturulması (Segmentasyon işlemi)
- Her bir segment için ortalama gelir tahmininin yapılması
- Sonuçlara göre, yeni müşterilerin sınıflandırılması ve ne kadar gelir getirebileceğinin tahmin edilmesi


______________________________

### 3. PROJE SONUÇLARI

#### Uygulama Öncesi DataFrame:
<img width="412" alt="Screen Shot 2024-01-30 at 2 53 37 PM" src="https://github.com/gozdemadendere/miuul_data_science_bootcamp/assets/90986708/328f1002-8a69-4134-b45c-da60bb2fa84d">


#### Uygulama Sonrası DataFrame:
AGE_CAT isimli yeni bir yaş kategorisi sütunu, CUSTOMERS_LEVEL_BASED isimli yeni bir müşteri persona tanımı sütunu, SEGMENT isimli yeni bir müşteri segmenti sütunu oluşturuldu. 

<img width="771" alt="Screen Shot 2024-01-30 at 2 58 10 PM" src="https://github.com/gozdemadendere/miuul_data_science_bootcamp/assets/90986708/2fcc0545-f0d5-4eb2-856d-6b1ad7f03b59">

#### Müşteri Grubu Bazında Ort. Fiyat & Segment Analizi:
Her CUSTOMERS_LEVEL_BASED müşteri persona grubu için, ortalama alışveriş fiyatı ve fiyat segmenti görülmektedir.

<img width="441" alt="Screen Shot 2024-01-30 at 3 02 25 PM" src="https://github.com/gozdemadendere/miuul_data_science_bootcamp/assets/90986708/a25a862f-54c7-402a-84b1-1a4339403aa2">

#### Müşteri Segmenti Bazında Fiyat Analizi:
Her SEGMENT için, alışveriş fiyat ortalaması, fiyat toplamı, min ve max fiyatlar görülmektedir.


<img width="433" alt="Screen Shot 2024-01-30 at 3 02 55 PM" src="https://github.com/gozdemadendere/miuul_data_science_bootcamp/assets/90986708/6ae280d3-c04e-4fce-b162-f28992f2b9f5">

#### Yeni / Potansiyel Müşteriler için Segment Belirleme ve Gelir Tahminlemesi yapma 
**Potansiyel Müşteri:**

33 yaşında, ANDROID kullanan bir Türk kadını hangi segmente aittir ve ortalama ne kadar gelir kazandırması beklenir?

**Analiz:**

Bu müşteri "TUR_ANDROID_FEMALE_31_40" müşteri grubunda olup, A müşteri segmentinde yer alır ve alış veriş başına ortalama gelir getiri tahmini 41.83 liradır.

<img width="763" alt="Screen Shot 2024-01-30 at 3 26 07 PM" src="https://github.com/gozdemadendere/miuul_data_science_bootcamp/assets/90986708/d84b497c-d2a2-4cb1-94ca-d601a61a8010">

<img width="173" alt="Screen Shot 2024-01-30 at 3 30 20 PM" src="https://github.com/gozdemadendere/miuul_data_science_bootcamp/assets/90986708/9402e5fd-9767-4ccd-bc57-4fec072a5e21">


### Proje Sonuçları:

- Müşterileri Anlamak: Müşteri verilerini analiz etmek bize onların tercihleri ​​ve davranışları hakkında değerli bilgiler verdi.
- Gelir Tahmini: Yeni müşteriler için gelir potansiyelini tahmin etmek, yüksek değerli müşterilere odaklanarak kaynakların daha iyi kullanılmasına yardımcı olabilir.
- Genel olarak bu proje, müşteri davranışını anlama ve iş büyümesini artırma konusunda veriye dayalı karar vermenin gücünü vurguladı.
