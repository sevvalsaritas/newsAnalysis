# 🧠 Turkish NLP Text Analysis

Bu projede Türkçe bir haber metni üzerinde çeşitli **Doğal Dil İşleme (Natural Language Processing - NLP)** teknikleri uygulanarak metnin dilsel ve anlamsal yapısı analiz edilmiştir.
Projenin amacı bir metni **veriye dönüştürmek**, metindeki önemli kelimeleri, varlıkları ve dilsel ilişkileri ortaya çıkarmaktır.

---

## 🚀 Kullanılan Teknolojiler

Projede aşağıdaki Python kütüphaneleri kullanılmıştır:

- 🐍 Python  
- 📚 NLTK  
- 🤖 Stanza  
- 🧮 Pandas  
- 📊 Scikit-learn  

Bu araçlar metin temizleme, dilsel analiz ve metin vektörleştirme işlemlerinde kullanılmıştır.

---

## 📰 Veri Kaynağı

Analizde kullanılan metin **BBC Türkçe**'de yayınlanan bir [yapay zeka haberinden](https://www.bbc.com/turkce/articles/c9vdklzee47o) alınmıştır.

Metin yapay zekanın geleceği ve olası etkileri üzerine bir senaryoyu ele almaktadır.

Analiz sürecinde metin cümlelere ayrılmış ve çeşitli NLP teknikleri uygulanarak incelenmiştir.

---

## 🧹 Metin Ön İşleme (Text Preprocessing)

Metnin analiz edilebilir hale gelmesi için çeşitli **veri temizleme işlemleri** uygulanmıştır.

Uygulanan işlemler:

- 🔤 Tüm harflerin küçük harfe dönüştürülmesi
- ❌ Noktalama işaretlerinin kaldırılması
- 🔢 Sayı ve özel karakterlerin temizlenmesi
- 🚫 Stopwords (anlamsal katkısı düşük kelimeler) temizliği
- 🌱 Lemmatization (kelimelerin köklerinin bulunması)

Lemmatization işlemi **Stanza NLP kütüphanesi** kullanılarak gerçekleştirilmiştir.

---

## 📏 Cümle ve Kelime Analizi

Metin cümlelere ayrılmış ve her cümlede bulunan kelimeler analiz edilmiştir.

Bu aşamada:

- 📌 Her cümledeki kelimeler listelenmiştir
- 📌 Cümle başına kelime sayısı hesaplanmıştır
- 📌 Metindeki toplam kelime sayısı belirlenmiştir
- 📌 Benzersiz kelime sayısı hesaplanmıştır

Bu analiz metnin temel yapısının anlaşılmasını sağlamıştır.

---

## 📊 TF-IDF Analizi

Metindeki kelimelerin önemini belirlemek için **TF-IDF (Term Frequency – Inverse Document Frequency)** yöntemi uygulanmıştır.

TF-IDF yöntemi bir kelimenin:

- Bir belgede ne kadar sık geçtiğini
- Diğer belgelerde ne kadar nadir olduğunu

dikkate alarak kelimenin **önem skorunu** hesaplar.

Bu projede:

- Her cümle bir belge olarak ele alınmıştır
- TF-IDF vektörleri oluşturulmuştur
- Her cümledeki **en önemli 10 kelime** belirlenmiştir
- Tüm metinde en yüksek TF-IDF skoruna sahip kelimeler analiz edilmiştir

---

## 🔗 N-Gram Analizi

Metindeki kelimeler arasındaki bağlam ilişkisini incelemek için **N-gram analizi** uygulanmıştır.

Bu analiz kapsamında:

- **Bigram (2 kelimelik gruplar)**
- **Trigram (3 kelimelik gruplar)**

oluşturulmuştur.

Ardından bu kelime gruplarının metinde **kaç kez geçtiği hesaplanmıştır.**

Bu sayede metinde en sık kullanılan kelime kombinasyonları belirlenmiştir.

---

## 🏷 Named Entity Recognition (NER)

Metindeki önemli varlıkları tespit etmek için **Named Entity Recognition (NER)** analizi uygulanmıştır.

NER yöntemi sayesinde metinde geçen:

- 🌍 Konumlar
- 🏢 Organizasyonlar
- 📅 Tarihler
- ⏱ Zaman ifadeleri

otomatik olarak belirlenmiştir.

Örnek tespit edilen varlıklar:

- BBC  
- ABD  
- Washington  
- AI2027  
- 2027  

---

## 🧩 Dependency Parsing (Bağımlılık Analizi)

Metindeki cümlelerin dilbilgisel yapısını incelemek için **Dependency Parsing** yöntemi uygulanmıştır.

Bu analiz ile:

- Kelimelerin cümledeki rolü
- Hangi kelimenin hangi kelimeye bağlı olduğu
- Dilbilgisel ilişki türleri

belirlenmiştir.

Bu sayede cümlelerin **sözdizimsel yapısı analiz edilmiştir.**

---

## 🎯 Projenin Amacı

Bu projenin amacı Türkçe bir metin üzerinde temel NLP tekniklerini uygulayarak metnin:

- Kelime yapısını
- Dilsel ilişkilerini
- Önemli varlıklarını
- Sözdizimsel yapısını

incelemektir.

---

## 📌 Sonuç

Bu çalışma kapsamında Türkçe bir haber metni üzerinde çeşitli NLP teknikleri uygulanmıştır.

Analiz sonucunda:

- Metindeki önemli kelimeler belirlenmiş
- Kelime ilişkileri ortaya çıkarılmış
- Metindeki varlıklar tespit edilmiş
- Cümlelerin dilbilgisel yapısı analiz edilmiştir.

Bu tür analizler **metin madenciliği, bilgi çıkarımı, arama motorları, chatbotlar ve yapay zeka uygulamaları** gibi birçok alanda kullanılmaktadır.

---

⭐ Eğer projeyi faydalı bulduysan repo'ya **star bırakmayı unutma!**
