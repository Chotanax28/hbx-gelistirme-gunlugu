# HBX geliştirme günlüğü

HBX’i üretim emirlerini, stok kullanımını ve maliyetleri tek yerden takip etmek için geliştiriyorum. İlerledikçe burada neleri değiştirdiğimi ve nasıl test ettiğimi paylaşacağım.

## ERP sarfı ve maliyet takibi

ERP’den gelen sarfı üretim emrine bağladım. Aynı belge satırı tekrar gelirse ikinci kayıt oluşmuyor. Sarf zaten ERP’de işlendiği için HBX stoktan bir daha düşmüyor.

ERP’de maliyet sonradan değiştiğinde önceki ve yeni değerleri yan yana görebiliyorum. Mamul veya fire bildirimi yapılmadan önce incelenen maliyet farkını gerekçesiyle emre işleyebiliyorum. Miktar da değişmişse ekran maliyet düzeltmesinin neden kullanılamadığını gösteriyor.

Bu akışı örnek verilerle test ettim. Sırada miktar farklarını ve mamul bildirimi sonrası değerlemeyi ele almak var.
