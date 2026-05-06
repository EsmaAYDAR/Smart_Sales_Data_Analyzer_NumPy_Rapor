# Smart_Sales_Data_Analyzer_NumPy_Rapor
 NumPy ile Satış Verisi Analizi
Bu proje, Python'ın en temel veri bilimi kütüphanesi olan NumPy kullanılarak, 7 günlük ve 5 farklı ürünlük bir satış matrisinin nasıl oluşturulacağını, yönetileceğini ve analiz edileceğini göstermek amacıyla hazırlanmıştır.

 Proje İçeriği
Bu çalışma kapsamında aşağıdaki temel veri manipülasyonu adımları uygulanmıştır:

Veri Simülasyonu: 7x5 boyutunda rastgele satış verisi üretimi.

Dizi Özellikleri: Matrisin boyutu (shape), veri tipi (dtype) ve boyut sayısı (ndim) analizi.

Dilimleme (Slicing): Belirli gün ve ürünlerin verilerine hızlı erişim.

İstatistiksel Analiz: Günlük ve ürün bazlı toplam/ortalama hesaplamaları.

Yeniden Şekillendirme: reshape, transpose ve flatten metodları ile verinin farklı analizlere hazırlanması.

 Kavramsal Analiz (Neden NumPy?)
 Performans ve Hız
Standart Python listeleri, verileri bellekte dağınık tutar ve her eleman için ayrı bir tip kontrolü yapar. NumPy ise verileri bitişik bellek bloklarında homojen olarak saklar. Bu sayede "Vektörizasyon" gücünü kullanarak döngülere (loop) ihtiyaç duymadan binlerce işlemi tek bir CPU döngüsünde gerçekleştirebilir.

 Array (Dizi) Mantığı
Veri analizinde veriyi sadece bir liste olarak değil, bir koordinat sisteminde (matris) görmek gerekir. NumPy dizileri, çok boyutlu veri setlerini temsil etmek için tasarlanmış matematiksel nesnelerdir. Bu yapı, lineer cebir işlemlerini doğrudan uygulamanıza olanak tanır.

 Axis (Eksen) Mekanizması
NumPy'da işlemler belirli eksenler üzerinden yürütülür:

axis=0 (Sütunlar): İşlemi yukarıdan aşağıya (satırlar boyunca) gerçekleştirir. Ürün bazlı haftalık toplamlar için kullanılır.

axis=1 (Satırlar): İşlemi soldan sağa (sütunlar boyunca) gerçekleştirir. Günlük toplam satışları bulmak için kullanılır.

 Kullanılan Teknolojiler
Python 3.x

NumPy: Veri işleme ve matris operasyonları.
