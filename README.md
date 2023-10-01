# Veri Kümesi Üzerinde One-Hot Encoding Kullanımı

Bu örnek, Python ve Pandas kütüphanesi kullanarak bir veri kümesi üzerinde "One-Hot Encoding" işlemini nasıl uygulayacağınızı gösterir. "One-Hot Encoding," kategorik verilerin sayısal verilere dönüştürülmesi için yaygın olarak kullanılan bir yöntemdir.

### Kod Açıklaması

1. İlk adımda, örnek bir veri kümesi oluşturulur. Bu veri kümesi öğrencilerin cinsiyetini, sınıfını ve yaşadığı şehri içerir.

2. Ardından, Pandas kütüphanesi kullanılarak "One-Hot Encoding" işlemi gerçekleştirilir. `pd.get_dummies()` fonksiyonu kullanılarak, "Cinsiyet," "Sınıf," ve "Şehir" sütunları ayrı ayrı ele alınır ve her bir kategori benzersiz bir sütuna dönüştürülür. Sonuç, orijinal veri çerçevesinin yerine geçen yeni bir veri çerçevesi olan `df_encoded` değişkenine atanır.

3. Son olarak, dönüştürülmüş veri çerçevesi ekrana yazdırılır.

### Nasıl Kullanılır?

Bu kod örneği, bir veri çerçevesi üzerinde "One-Hot Encoding" işlemi gerçekleştirmenin temel adımlarını göstermektedir. Kendi veri kümesinizi kullanarak veya bu kod örneğini geliştirerek kategorik verilerinizi sayısal verilere dönüştürebilirsiniz.

### Gereksinimler

Bu kod örneğini çalıştırmak için Python ve Pandas kütüphanelerinin yüklü olması gereklidir.
