## DepremKit: İnsan ve ChatGPT Etiketli Türkçe Deprem Veri Kümesi

6 Şubat 2023’te gerçekleşen Kahramanmaraş merkezli deprem sonrasında insanlar; yardım çağrıları, ihtiyaç talepleri ve bağış duyurularını paylaşmak için Twitter’ı etkin olarak kullanmıştır. DepremKit çalışmasında, paylaşılan tweetlerin analiz edilmesi ve elde edilen bilgilerin depremden etkilenen insanlara verimli şekilde yardım ulaştırılmasına katkıda bulunacak bir veri kümesi oluşturulması hedeflenmiştir.

## Problem Tanımları

Veri kümesi aşağıdaki problemler için etiketlenmiştir.

* **İkili Sınıflandırma** Enkaz altında bulunan insanların tespit edilmesi için tanımlanmıştır.
* **Çoklu Sınıflandırma:** Tweet’lerin “Yardım Çağrısı”, “Bilgi Paylaşımı”, “Bağış ve Gönüllülük”, “İhtiyaç” ve “Konu Dışı” kategorilerine ayrılması için tanımlanmıştır.
* **Varlık İsim Tanıma:** Tweet’lerde geçen “İl”, “İlçe”, “İhtiyaç”, “Kişi”, “Kişi Durumu” ve “Adres” bilgilerini tespit etmek için tanımlanmıştır.


## Altın Veri Kümesi

İnsanlar tarafından etiketlenmiş olan 3.750 veriyi içermektedir.

## Gümüş Veri Kümesi

ChatGPT API üzerinden GPT-3.5 modeli kullanılarak etiketlenmiş olan 50.000 veriyi içermektedir.

## İstemler

ChatGPT etiketlemesinin yüksek performansla gerçekleştirilebilmesi için modele verilen istemler; İkili Sınıflandırma, Çoklu Sınıflandırma ve Varlık İsim Tanıma problemleri için ayrı ayrı paylaşılmıştır.
