# RAM'in Yapısı Nasıldır?

RAM'in birçok yapısı var ama şimdilik 2 genel temel yapısından bahsedeceğim.
- STACK
- HEAP

# STACK

STACK içerisinde genellikle 
- değer türlü değişkenleri
- metod isimlerini
- nesne referanslarını tutarız.
  
# Önemli detaylar
- Değişkenlerin türü ,adı ve değeri STACK'te tutulur.
  # int yas = 20;
  - değişken türü: int
  - değişken adı: yas
  - değişkene atanan değer: 20 
- STACK, LIFO(Last In First Out) mantığına göre çalışır. Yani son giren ilk çıkar.
- Değişkenler koda yazılır yazılmaz alan tahsisi gerçekleşmez.Runtime'da alan tahsisi gerçekleşir.




