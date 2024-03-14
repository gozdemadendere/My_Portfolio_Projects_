
### A/B Testing - Bidding (Teklif Verme) Yöntemlerinin Dönüşümünün Karşılaştırılması

A/B testi, bir ürünün, yöntemin veya hizmetin iki versiyonunu karşılaştırarak hangisinin daha iyi performans gösterdiğini belirlemek için kullanılan bir tekniktir. 

Genellikle web sitesi tasarımını, uygulama tasarımını, reklamcılığı, fiyatlandırmayı ve kullanıcı deneyiminin diğer yönlerini geliştirmek için kullanılır.

2 grup karşılaştırmasında temel amaç, olası farklılıkların şans eseri ortaya çıkıp çıkmadığını test etmektir.

______________________________


### 1. İŞ PROBLEMİ / PROJE HEDEFİ 

Facebook kısa bir süre önce mevcut "maximumbidding" adı verilen teklif verme türüne alternatif olarak yeni bir teklif türü olan "average bidding"’i tanıttı.

Müşterilerimizden biri, bu yeni özelliği test etmeye karar verdi ve averagebidding'in maximumbidding'den daha fazla dönüşüm getirip getirmediğini anlamak için bir A/B testi yapmak istiyor.

A/B testi 1 aydır devam ediyor ve şimdi bizden bu A/B testinin sonuçlarını analiz etmemizi bekliyor.
Şirket için nihai başarı ölçütü satın alma (Purchase)'dır. Bu nedenle, istatistiksel testler için Purchase metriğine odaklanılmalıdır.

______________________________

### 2. PROJE AŞAMALARI

1. İş Problemi     (Business Problem)
2. Veriyi Anlama & Hazırlama   (Data Understanding & Preparing)
3. A/B Testing     (Bağımsız İki Örneklem T Testi / Independent Two-Sample T-Test)

______________________________

### 3. PROJE SONUÇLARI

Hipotez testi sonucunda, Kontrol grubu (Maximum Bidding) ve Test grubu (Average Bidding) satın alma (purchase) ortalamaları arasında, istatistiksel olarak anlamlı bir fark olmadığını belirledik.

Yani, bu iki teklif stratejisi arasında belirgin bir performans farkı gözlemlenmemiştir.
Bu test sonucuna göre, müşterinin bir teklif verme yöntemini diğerine tercih etmesi için bir neden yoktur.



__________________________________

#### Öneriler:
- A/B Testing sadece 80 gözlem için gerçekleştirildi. Bu gözlem sayısı arttırılabilir, farklı gruplar üzerinde de test işlemi devam ettirilebilir.
- Diğer faktörler de dikkate alınarak daha kapsamlı bir analiz yapılabilir:
- Earning metriği de incelenebilir ve farklı teklif stratejilerinin gelir üzerindeki etkisi değerlendirilebilir.
- Impression (reklam görüntüleme sayısı): Bu metrik üzerinde ek bir analizle, 2 teklif stratejisinin reklam performansı üzerindeki etkisi değerlendirilebilir.

