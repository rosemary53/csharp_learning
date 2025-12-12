 # Main Fonksiyonu Nedir?

 - Herhangi bir uygulama ayağa kalktığında yani çalıştırıldığında tetiklenen ilk fonksiyon 'main' fonksiyonudur.
 - Main fonksiyonunun  uygulama türü çeşidi fark etmeksizin bulunması zorunludur.
 - Her uygulamada yalnızca 1 adet main fonksiyonu  bulunur.
 - C# uygulamalarında main fonksiyonu Program.cs dosyasında bulunur.
 - Main fonksiyonu, işletim sistemi ile iletişim kurar.
 - İşletim sistemi main fonksiyonuna değer gönderebilir.
 - Bu değer main fonksiyonunun parametresi olan args dizisinde tutulur.Yani args dizisi,işletim sistemi tarafından komut satırından uygulamaya gönderilen değerleri tutar.

 - Main fonksiyonu kodu :
   
    static void Main(string[] args) {
    }

     - dotnet run rosemary 23 
     - args dizisine rosemary ve 23 değerleri gelir.
     - args dizisinin tipi String[]'tir. Yani elemanlar String olarak tutulur.
     - args == ["rosemary","23"] şeklindedir.
     - args[0] = "rosemary"
     - args[1] = "23"  olur.
     

