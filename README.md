# Introduction_to_DS-Patika-

## Makine Öğrenmesi Nedir?

- Bilgisayar ile iletişim örnekler üzerinden gerçekleşir. 
- Komutlar üzerinden iletişim kurulmaz.
- Bu iletişim tekniğine "makine öğrenmesi" denir.

## Veri Bilimi Nedir?

- Veriyi kullanışlı hale getirme bilimidir. 
  - Veri Analisti 
  - İstatistikçi
  - ML Analisti

## ML: Uygulama ve Araştırma 

- Teori iyiyse pratik de iyi olur. 
- İki alanda da bilgi sahibi olunması önemlidir. 
- Aşçı ve mutfak gereçleri geliştiricisi örneğindeki gibi iyi bir aşçı neyin ...
- geliştirilmesi gerektiğini de bilir. 

## Supervised and Unsupervised Learning

- Supervised: Örneklerin dışardan verildiği model kurma biçimidir. 
- Unsupervised: Gruplama yapılır.
  - Benzerliklerine göre
  - Model iyi değilse değişiklik yapılabilir
  - İnsan denetimi en sonda devreye girer. 
  - BIAS modele girer.

## Regression-Classification

- Tahmin edilmeye çalışılan şeyler sürekli değişkenler ise ...
- "Regression"(boy,fiyat,vs)
- Tahmin edilmeye çalışılan şeyler kategorik ise ...
- "Classification"(kedi,köpek)

##Classification = Regression

- İki modelde de PC sayısal output verir.
- Sayısal outputların anlamlandırılmasında classification yapılır. 
- Temelde iki model de aynı sayılabilir.

## Model Seçimi

- Kesin bir cevabı yoktur. 
- Deneme - yanılma 
- Zaman ve denenebilecek model sayısı önemlidir.

## Temel Veri Tipleri 

- Algılanan ve tanımlanan her şey olarak düşünülmelidir.
- Numeric Data:
  - Continuous
  - Discrete
  - Interval: 
      1.  Referans noktası yok.
      2.  Gerçek sıfır yok.
      3.  Sıcaklık örneği.(Celcius)

  - Ratio:
      1.  Kelvin örneği(sıfır var)

  - Categoric Data (sayısal ifade var)
      - Binary(İki kategori)
      - Multi-class(ikiden daha çok)

  - Nominal: Özellik gözetilir.(Identifying)
  - Ordinal: Sıralama gözetilir.
  - Cardinal: Sayı gözetilir.(adet)

## Continuous Variable Yoktur!

- Veriler sonsuza gitmez.
- İfadeler sonludur.
- Virgülden sonra sonludur.
- Ölçüm cihazının precision'ı değerin continuous olmamasını sağlıyor.

## Prediction - Mantık

- ELdeki verilerle tahmin yürütme.
- Ortak olarak "mapping" bulunur. 
- f(x) -> y, f(x,y) -> z
- Gerçek değerlerle tahmin değerleri arasındaki fark az olmalıdır. 
- f(x1,x2,x3) -> y' -> ML  y->gerçek değer
- Her farklı duruma göre "error function" tanımlanır. e(y',y) -> error function
- Amaç error function'u en az verecek modeli üretmek.

## Veriyi Bölmek 

- Üretilen tahmin modelinin eğitilen verilerle doğru çalışmasının yanında hiç görmediği verilerle de düzgün çalışması önemlidir. 
- Bu yüzden test mantığı geliştirilmelidir. 
- Model, train'de gördüğü noktalardan pattern çıkarmak(genellemek) yerine ezberliyorsa "overfitting" yapıyor. 
- Test sonuçlarını iyileştirmek için train'de çalışan model parametrelerini değiştirmek de "dolaylı" yoldan test'e overfitting yapmak oluyor.
- Validation ve test, gerçek hayatta gözlemlenmesini beklediğimiz verilerden oluşmalıdır. 

## Artificial Intelligence BIAS

- Modelin sistematik olarak taraflı sonuçlar üretmesidir.
- Örneğin bir işe alım modelinin erkekleri öne çıkarması BIAS'tır.
- Modeli oluşturan kişilerin biaslarını taşır.
- Veri setleri de bias taşır.
- Bias'ı oluşturan yapı insandır.

## BIAS Nasıl Azaltılabilir?

- Çeşitlilik, bias'ı azaltabilir.
- Farklı biaslara sahip kişiler birbirlerinin biaslarını kapatacaktır.

## Başkasının Verisini Kullanmak

- En ideali probleme yönelik veriyi kendimiz oluşturmaktır. Ancak bu her zaman mümkün değildir.
- Verinin toplanış amacı önemlidir.
- Veri toplama süreci güvenilir olmalıdır.
- Veriyi oluşturanların "bias"ı varsa dikkate alınmalıdır.
- Verinin dökümantasyonu yeterli olmalıdır.



