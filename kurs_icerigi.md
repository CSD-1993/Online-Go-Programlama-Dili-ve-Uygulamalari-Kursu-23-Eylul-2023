# Online Go Programlama Dili ve Uygulama Geliştirme

## Temel kavramlar
+ Çevirici programlar, derleyiciler yorumlayıcılar
+ İşletim Sistemleri
+ IDE _(Integrated Development Environment)_ programları
+ Temel sayı sistemleri
+ Go programlama dili hakkında temel bilgiler
+ Go ortamının kurulması
+ Hello, World programı
+ Fonksiyon bildirimi
+ Fonksiyonların çağrılması

## Tür kavramı
+ Go’da temel türler
+ Tamsayı türleri, gerçek sayı türleri, _char_ türü ve _boolean_ türü
+ Değişkenler ve faaliyet alanı

## Fonksiyonlar
+ Fonksiyonların geri dönüş değerleri
+ _return_ deyimi
+ Fonksiyonların parametre değişkenleri
+ Matematiksel işlem yapan yararlı metotlar

## Sabitler
+ Sabit kavramı
+ Sabitlerin türleri
+ Tamsayı sabitleri
+ Gerçek sayı sabitleri
+ bool türden sabitleri
+ Karakter sabitleri
+ Escape sequence karakterler
+ Tamsayı sabitlerinin hexadecimal, binary ve octal gösterilişleri
+ Gerçek sayı sabitlerinin bilimsel gösterilişi
+ Sabit bildiriminde alttire karakterinin kullanımı

## Temel Operatörler
+ Operatörlerin sınıflandırılması
+ Operatör önceliği
+ Aritmetik Operatörler
+ Karşılaştırma operatörleri
+ Mantıksal operatörler
+ Mantıksal operatörlerin kısa devre davranışları
+ Atama operatörü
+ İşlemli atama operatörleri

## Kontrol deyimleri
+ _if_ deyimi
+ _for_ döngü deyimi
+ _break_ ve _continue_ deyimleri
+ _switch_ deyimi
+ _select_ deyimi
+ Örnek programlar

## Tür dönüştürmeleri
+ Farklı türlerin birbirine atanması
+ İşlem öncesi otomatik tür dönüşümleri
+ Tür dönüştürme operatörü

## Adres kavramı
+ Adres kavramı
+ Stack ve heap alanları
+ Ömür _(storage duration)_ kavramı: yerel ve parametre değişkenlerinin ömürleri
+ Göstericiler _(Pointers)_

XXXXXXXXXXXXXXX

## Yapılar
+ Yapı bildirimleri
+ Yapıların elemanları
+ Örnek yararlı yapılar

## Rasgele sayı üretimi
+ Rasgele sayı üretimi
+ Random sınfının metotları
+ Tohum değeri _(seed value)_ kavramı
+ _Random_ sınıfının tohum değeri parametreli başlangıç metodu ve _setSeed_ metodu
+ Örnek programlar

## String sınıfı
+ _Immutable_ sınıf kavramı
+ _String_ nesnesinin bellekteki durumu
+ _String_ sabitleri _(String literals)_
+ _String_ sınıfının metotları
+ _String_ işlemlerine yönelik yararlı metotların yazılması
+ Örnek programlar

## Paketler
+ Paket kavramı
+ Farklı paketlerdeki sınıflara erişim
+ İçiçe paket bildirimleri
+ Paketler ve dizinlerin ilişkisi
+ Paket isimlendirmesine ilişkin teknikler
+ Kaynak dizin _(source folder)_
+ Yazılmış olan yararlı sınıflara ilişki uygun paketler

## İsim arama
+ Niteliksiz _(unqualified)_ isim arama
+ Nitelikli _(qualified)_ isim arama
+ _import_ bildirimleri _(import on demand declaration, import single type declaration)_
+ _import static_ bildirimleri _(import static on demand declaration, import static single type declaration)_

## Diziler _(Arrays)_ ve uygulamalar
+ Dizi referansları
+ Diziye ilişkin nesnelerin bellekteki durumu
+ Dizi elemanlarına erişim
+ Dizilere ilk değer verilmesi
+ Dizilerin metotlara geçirilmesi: dizi referansı parametreli metotlar
+ Dizi referansı döndüren metotlar
+ Dizilere ilişkin temel algoritmaların yazımı
+ Dizilere ilişkin yararlı metotların yazımı
+ Dizilerde bazı sıralama algoritmaları: kabarcık sıralaması _(bubble sort)_ ve _seçerek sıralama _(selection sort)_ algoritmaları
+ _char_ türden diziler
+ _char_ türden diziler ve _String_ sınıfı
+ Referans dizileri
+ Referans dizilerine ilkdeğer verilmesi
+ _String_ türden diziler
+ Dizi dizileri
+ Dizi dizilerinin çok boyutlu dizi gibi kullanılması
+ Dizi dizilerine ilk değer verilmesi
+ Matrisler ve matrislere ilişkin algoritmalar
+ Örnek programlar

## Sınıflarda temel erişim kuralları
+ _public_ erişimcisi
+ _private_ erişimcisi
+ Erişim belirleyicilerin paketlerle ilişkisi
+ _no-modifier_ erişimcisi
+ _protected_ erişimcisi
+ Başlangıç metodunun _private_ olması durumu
+ _Singleton_ sınıf tasarımı: _lazy implementation_
+ Örnek sınıflar

## final değişkenler
+ final yerel değişkenler
+ final parametre değişkenleri
+ final veri elemanları
 + final static veri elemanları
 + final non-static veri elemanları
+ _Singleton_ sınıf tasarımı: _eager implementation_
+ immutable sınıf tasarımı
+ Örnek immutable sınıflar

## enum sınıflar
+ enum sınıflar
+ enum sabitleri
+ enum sınıfların ordinal metotları
+ enum sınıfların values static metotları
+ enum sınıfların sabit dışındaki elemanları
+ enum sınıfların başlangıç metotları (constructor)
+ enum'ların eşitlik karşılaştırması
+ enum'ların karşılaştırılması
+ enum sınıfların kullanımı
+ Örnek enum sınıflar

## Sınıflar arası ilişkiler
+ _Composition_
+ _Aggregation_
+ _Association_
+ _Inheritance_
+ Sınıflar arası ilişkilerin modellenmesi

## Türetme _(inheritance)_
+ _Super class_ (taban sınıf) ve _sub class_ (türemiş sınıf) kavramları
+ Türetme sentaksı
+ Başlangıç metodu içerisinde taban sınıfın başlangıç metodunun çağrılması
+ Başlangıç metodu içerisinde taban sınfın istenilen başlangıç metodunun çağrılması: _super_ sentaksı
+ Başlangıç metodu içerisinde başka bir başlangıç metodunun çağrılması: _this_ sentaksı
+ _protected_ bölümün anlamı
+ Object sınıfı
+ Örnek sınıflar

## Taban sınıf ve türemiş sınıf arasındaki dönüşümler
+ Yukarıya doğru dönüşüm _(upcasting)_
+ Yukarıya doğru dönüşümün anlamı
+ Referansların statik ve dinamik türleri
+ Aşağıya doğru dönüşüm _(down-casting)_
+ Haklı ve haksız dönüşüm kavramı
+ _instanceof_ opetörü
+ Sarmalayan _(wrapper)_ sınıflar
+ Number sınıfı ve metotlarının anlamı
+ Otomatik kutulama _(auto-boxing)_ ve otomatik kutuyu açma _(auto-unboxing)_
+ _final_ sınıflar
+ Örnek programlar

## Sınıflar içerisinde bloklar
+ Sınıfların _static_ blokları _(static initializers)_
+ Sınıfların _static_ olmayan blokları _(non-static initializers)_

## this referansı
+ _this_ referansının anlamı
+ _non-static_ metotlar içerisinde _this_ kullanmı
+ _this_ referansının kullanıldığı örnek durumlar: _fluent_ kalıbı
+ Örnek sınıflar

## null referans
+ _null_ adres kavramı ve _null_ sabiti
+ _null_ referansın kullanıldığı durumlar

## Çöp Toplayıcı _(garbage collector)_
+ Nesnelerin ömürleri
+ Nesnelerin seçilebilir _(garbage collected)_ duruma gelmesi
+ Çöp toplayıcı'nın çalışma biçimi
+ Nesnelerin gösteren referansların takibine yönelik tipik algoritmalar

## Temel algoritma analizi
+ Algoritmanın karmaşıklığı
+ Karmaşıklığın ölçütü
+ Karmaşıklığın gösterimine ilişkin notasyonlar
+ _Big O_ notasyonu ile çeşitli karmaşıklık durumlarının incelenmesi
+ O(1), O(logn), O(n), O(n * Logn), O(n ^ 2), O(n ^ 3), ... , O(n ^ k) karmaşıklıkları
+ O(k ^ n), O(n!) gibi özel karmaşıklıklar

## Dinamik büyüyen dizi veri yapısı
+ Dinamik büyüyen veri yapısına ilişkin temel kavramlar: _capacity_, _size_ vs.
+ Dinamik büyüyen veri yapısına ilişkin metotların karmaşıklık durumları
+ _ArrayList_ ve _Vector_ sınıfları
+ Örnek programlar
+ Örnek bir dinamik büyüyen dizi sınıfının yazılması

## Çok biçimlilik (polymorphism)
+ Çok biçimliliğin programlamaya yönelik tanımları
+ Çok biçimli mekanizma
+ Sanal metotlar
+ Sanal metotların _override_ edilmesi
+ Metotların _override_ edilmesinin anlamı
+ _super_ referansı
+ _Override_ edilen metot içerisinde taban sınıfın aynı metodunun çağrılması _(augmentation)_
+ _Override_ edilen metodun erişim belirleyicisinin erişim anlamında yükseltilmesi
+ _final_ metotlar
+ Çok biçimliliğe ilişkin örnek tasarımlar ve kodlanması

## Soyut sınıflar ve metotlar _(abstract classes and methods)_
+ Soyut sınıf ve metotların anlamı
+ Soyut metotların _override_ edilmesi
+ Soyut metotların _override_ edilmemesi durumu
+ Soyut sınıfların taban sınıf referansı olarak kullanılması
+ Soyut sınıfların başlangıç metotları
+ Örnek sınıflar

## Exception işlemleri
+ _Exception_ kavramı kullanımı
+ _Exception_ sınıf hiyerarşisi: _Throwable_, _Exception_, _Error_ ve _RuntimeException_ sınıfları
+ _throw_ anahtar sözcüğü ve bir _exception_ nesnesinin fırlatılması
+ _try_ blokları
+ _catch_ blokları
+ _catch_ blokları parametrelerine ilişkin sınıflar ve uygun _catch_ bloğunun bulunması
+ Yeniden fırlatma _(rethrow)_
+ İçiçe _try_ bloklarının bulunması durumu
+ _finally_ bloğu
+ Yakalanamayan _exception_ durumu
+ _Exception_ sınıflarının anlamı
+ _Cause exception_
+ _checked_ ve _unchecked exception_ sınıfları
+ _throws_ anahtar sözcüğü
+ Önemli _exception_ sınıfları
+ Örnek sınıfların _exception_ açısından düzenlenmesi ve genel hale getirilmesi

## Arayüzler _(interfaces)_
+ Arayüzlerin elemanları
+ Arayüzler içerisinde olabilecek elemanların Java sürümlerine göre farklılıkları
+ Bir sınıfın desteklediği arayüzler ve metotların _override_ edilmesi
+ _Marker_ arayüzler, fonksiyonel arayüzler
+ Java 8 ile eklenen arayüz içerisinde _default_ metotlar ve _static_ metotlar
+ Arayüzler ile _abstract_ sınıflar arasındaki farklar
+ Arayüzler arası tür dönüştürme ayrıntıları
+ Çok kullanılan bazı arayüzler
+ _try-with resources_ bloğu ve kullanımı: _AutoCloseable_ ve _Closeable_ arayüzleri

## Generic sınıflar ve metotlar
+ Generic sınıflar
+ Generic sınıflarda türetme işlemleri
+ Generic sınıflarda _new_ operatörü ile _<> (diamond syntax)_ kullanımı
+ Generic arayüzler
+ Generic türlerde kısıtlar: _extends_ ve _super_ anahtar sözcüğünün _generic_ parametrelerde kullanımı
+ Generic türlerde joker karakter
+ Generic sınıflarda alt sınır ve üst sınır belirlenmesi _(invariant, covariant ve contra-variant)_
+ Generic metotlar
+ Generic metotlarda parametre türlerinin tespiti
+ Generic türlerin ve metotların generic parametrelerinin arakoda _Object_ olarak aktarılması
+ Örnek sınıflar ve programlar

## Komut Satırı Argümanları
+ Program ve Process kavramları
+ Programın komut satırı argümanları
+ Progamın giriş noktası (entry point) olan main metodunun parametresi ve anlamı
+ Örnek uygulamalar

## Dosya işlemleri
+ Dosya ve dizin _(directory)_ kavramları
+ Dosya yol ifadeleri: _absolute_ and _relative_ path
+ Processin çalışma dizini _(current working directory)_
+ Metin _(text)_ ve ikili _(binary)_ dosyalar
+ Dosya üzerinde bütünsel işlemler yapan sınıflar
+ Dosyalar üzerinde ayrıntılı işlem yapan sınıflar
+ _File_ sınıfının dosya ve dizinler üzerinde işlem yapan metotlar
+ _Path_ arayüzü ve _Files_ sınıfı
+ _InputStream_ ve _OutputStream_ soyut sınıfları
+ _FileInputStream_ ve _FileOutputStream_ sınıfları
+ Dosya göstericisi _(file pointer)_ kavramı
+ Dosya göstericisinin _EOF_ durumu
+ Dosyadan okuma ve yazma işlemleri
+ Little endian ve big endian kavramları
+ Temel türlerin byte dizisine çevrilmesi ve byte dizisinin temel türlere çevrilmesi _(ByteBuffer sınıfı)_
+ _DataInputStream_ ve _DataOutputStream_ adaptör sınıfları
+ _BufferedReader_ ve _BufferedWriter_ adaptör sınıfları
+ _RandomAccessFile_ sınıfı
+ Dosya göstericisinin konumlandırılması
+ Dosya formatı kavramı
+ Örnek programlar
# Kursa Kayıt
Kursa aşağıdaki bağlantıdan ön kayıt yaptırabilirsiniz:<br>
[Kursa Kayıt](https://us02web.zoom.us/meeting/register/tZMkfumqqT8rE9X7M7_LrrQEN8X3q0QLYDPx)
