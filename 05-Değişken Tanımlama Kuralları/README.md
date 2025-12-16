# Değişken Tanımlama Kuralları
#  Anlamlı İsimlendirme
  Değişken ismini tanımlarken bu kodun başkaları tarafından okunabileceğini göz önünde bulundurarak tanımlama yapmalıyız.

# Örnek1,: Hasta kayıt girişiyle ilgili bir uygulamada hasta bilgilerini alırken 
  string x = "ayse";
  int y = 25;
  gibi tanımlamalardan kaçınmamız gerek.
  string ad = "ayse";
  int yas = 25;

# Keywordleri değişken adı olarak nasıl kullanabiliriz?
 Eğer bir keyword'ü değişken ismi oalrak kullanmak istiyorsanız o keyword'ün önüne @ işareti koymanız gerekir.
- int @int = 5;
- Console.WriteLine(@int);

# Tanımlanmış değişkene değer atama
- int sayi; burada değişkenimizi tanımladık türünü derleyiciye bildirdik o da RAM'e bildirip runtime'da alan tahsisi yapacak
- int sayi = 23; burada ise değişkenimizi tanımlama aşamasında başlattık.
- int sayi;
- sayi = 25; burada ise değişkenimizi tanımladıktan sonra değer ataması gerçekleştirdik.

# Değişkenin genel özellikleri
- Bir değişken adından da anlaşıldığı üzere değişen bir yapıdır.Bundan dolayı türüne uygun birden fazla değer alabilir.
- Değişkene atanan son değer geçerlidir.
- - int yas = 23;
- - yas = 28;
- - Ekran çıktısı : 28 olur.
- Değişkene değer atandıkça STACK'te yeniden oluşmaz.Değişkenin bellek adresine gidilir o hücrede önceki değer yerine yenisi yazılır.

# Değişkene Değer Atama

# Metinsel değerler
- string(referans türlü) : metinsel ifadeleri "" içerisinde tutar.
- char(değer türlü) : karaktersel ifadeleri '' içerisinde tutar.
  - Metinsel türlerin varsayılan değerleri
  - string : null
  - char : '\0'
# Mantıksal değerler
- bool(değer türlü): mantıksal ifadeleri tutmak için kullanılır.
- 2 değer alabilir.
  -- true
  -- false
  - Mantıksal türlerin varsayılan değeri : false
# Sayısal değerler
# Dikkat 1: Sayısal bir değer başlangıçta varsayılan olarak 'integer' kabul edilir.
# Dikkat 2: Ondalıklı bir değer başlangıçta varsayılan olarak 'double' kabul edilir.

# Tuple türüyle değer atama
- Prototipi şu şekildedir.
  - (tür değişken1,tür değişken2,..) = (değişken1 değer,değişken2 değer,..)
# Örnek 1:
- int sayi1 = 20;
- int sayi2 = 30;
- (int sayi1,int sayi2) sayilar = (20,30);
# Örnek 2: Bir kişiyi tanımlayan temel özellikleri tuple ile ifade ediniz.
-(string ad,string soyad,int yas,bool medeniHal) kisiBilgisi = ("ayse","yilmaz","23","false");

# Değeri olmayan değişkenler
- Class içerisinde tanımlanan değişkenlere varsayılan değer otomatik atanır.
- Ancak main içerisinde tanımlanan başlatılmayan değişkenlere derleyici otomatik varsayılan değer atamaz.
- Değer atanmadığı için de işlem yapılamaz.
- Sonuç olarak main içindeki değişkenlerimizi manuel olarak başlatmaya dikkat edelim.

# tür değişkenAdi = değer Özeti
-int a ; // tanımlandı ancak değer atanmadı
- a = 23; //artık değer atandı.
- Önemli : burada assign(atama) operatörünün solundaki a aslında Stackteki bellek adresini ifade ederken sağındaki 23 ise değeri ifade eder.
 
