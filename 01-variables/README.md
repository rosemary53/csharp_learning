# Yazılımda temel amacımız nedir?
- Yazılım geliştiricileri, elinde var olan veriyi işleyerek doğru bir çıktı elde etmek ister.
- Örneğin bir insanın temel verileri şunlardır: ad, yaş, cinsiyet, kilo vb.
- Bu verileri kullanmak amacıyla yazılım geliştirirken, verileri gerekli yerlerde işleyip depolamak isteriz.

# Peki veri nerede depolanır?
- Veriler kaynak kodda depolanmaz. Bir işlem yapılırken veriler öncelikle RAM’de tutulur.
- Ancak veriler doğrudan RAM’e yerleştirilmez. Bunun için bir aracıya ihtiyaç vardır.
- Bu aracı da değişkenlerdir.
- Değişkenler, yazılımda kullanılan verilerin RAM’de tutulmasını sağlar.

# RAM depolanacak olan veriyi nasıl kabul eder?
- RAM, kendisine gelen verinin türünün ne olduğunu bilmez.
- Bu nedenle, verinin türünü ve RAM’de ne kadar alan kaplayacağını bilmek ister.
- Örneğin, RAM’e doğrudan 5 değerini koyamazsınız çünkü bu değer tek başına anlamsızdır.
- RAM şu soruyu sorar: Bu 5 bir sayı mı, karakter mi, yoksa başka bir şey mi?
- Buna göre 4 byte mı, 8 byte mı alan ayıracağını belirlemek ister.
- Bu yüzden değişkenler kullanılır.
- int yas = 5; ifadesinde, 5 artık anlamlıdır çünkü bir yaş değerini temsil eder.
- Aynı zamanda türü `int` olduğu için bellekte 4 byte alan ayrılır.
