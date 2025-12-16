# Value Type -Primitive Type
# Genel Özet
C# programlama dilinde RAM'de veriyi tutabilmek için değişkenlerden yararlanıyorduk. 
Veriyi RAM'de tutarken RAM'e değişkenin türünü bildirmemiz gerekiyor.

# Tür neye göre bildirilir?
Elimizdeki veriyi alırız
-Metinsel
-Sayısal
-Mantıksal
-Karaktersel
olup olmadığını inceleyip karar veririz.

# Değişken İçerisinde Ne Tutar?
Değişken içerisinde veri ,değer tutar.

# Value Type Nedir?
Tanımladığımız değişkenle RAM'de alan tahsisinde bulunduğumuzda buna değer türlü değişken deriz.
örneğin; ad,soyad,dogum tarihi vb.

# Primitive Type
En ilkel tür diyebiliriz.
Örneğin: byte,int primitive türdür. Decimal ise int'ten türeyerek elde edilmiştir.

# Sayısal verileri hangi türde tanımlamalıyım?
Sayısal türleri tanımlarken genel olarak kullanacağımız türler şunlardır:
-byte
-short
-int
-float
-double
-decimal
Sayısal bir değişken tanımlarken seçtiğiniz türe bellek açısından dikkat etmeniz gerekir.
# Örnek1: Yaş verisini sayısal bir türde tutmak isteyelim
Öncelikle burada ben elimdeki veriyi hangi aralıkta tanımlasam yeterli olur diyebilmeniz gerekir.
Yaş özelliğini 0-255 arasında ifade edebilirim bu yüzden tercihimiz byte olur.
byte : 1 byte -> 8 bit -> Byte
short: 2 byte -> 16 bit -> int16
int:  4 byte -> 32 bit -> int32
long: 8 byte -> 64 bit -> int64
# Örnek2: 1000 sayısını hangi türde saklamamız gerekir.
byte : 0-255 arası olduğu için bu aralıkta tanımlayamayız.
short: -32.768 - 32.767 olduğu için bu aralıkta tanımlayabiliriz.
