# SQLite ve LocalDB kavramları
## LocalDB
LocalDB , kullanıcı modunda isteğe bağlı ve çalışır durumda başlayan SQL Server Express veritabanı altyapısının hafif bir sürümüdür. LocalDB, veritabanlarıyla . mdf dosyaları
olarak çalışmanıza olanak sağlayan SQL Server Express özel bir yürütme modunda çalışır. Genellikle, LocalDB veritabanı dosyaları bir Web projesinin uygulama _ verileri klasöründe
tutulur.
SQL Server Express üretim Web uygulamalarında kullanılması önerilmez. LocalDB, IIS ile çalışmak üzere tasarlanmadığı için bir Web uygulamasıyla üretim için kullanılmamalıdır. 
Ancak, bir LocalDB veritabanı SQL Server veya SQL Azure kolayca geçirilebilir.
Visual Studio 2017 ' de, LocalDB, Visual Studio ile varsayılan olarak yüklenir.
Varsayılan olarak Entity Framework, nesne bağlamı sınıfıyla aynı adlı bir bağlantı dizesi arar ( MovieDBContext Bu proje için). Daha fazla bilgi için bkz. ASP.NET Web uygulamaları
Için bağlantı dizeleri SQL Server.

## Sqlite
iOS platformu da diğer mobil platformlar gibi veritabanı olarak SQLite kullanımını tercih etmektedir. Hem SQL komutlarını çalıştırabilmesi hem de mobil cihazlar gibi 
düşük kapasiteli ortamlarda kolayca çalışabilmesi SQLite’ı Android ve iOS platformlarında bir numaralı tercih haline getirmiştir.
http://www.sqlite.com adresinden indirebileceğiniz SQLite’ı komut satırından çalıştırabilirsiniz. Terminal penceresinde aşağıdaki komutu girdiğinizde yeni bir veritabanı 
yaratılacak ve bellekte aynı isimle bir dosya oluşturulacaktır.

# Lazy Loading kavramı hakkında temel bir araştırma yapınız.
Lazy Loading bilgisayar programlamasında ve çoğunlukla bir nesnenin başlatılmasını ihtiyaç duyulan noktaya kadar ertelemek için çoğunlukla web tasarımı ve geliştirmede
kullanılan bir tasarım modelidir . Düzgün ve uygun şekilde kullanılırsa, programın işleyişinde verimliliğe katkıda bulunabilir. Bu, ağ içeriğine erişildiği ve web
sayfalarında olduğu gibi başlatma sürelerinin minimumda tutulduğu kullanım durumlarında idealdir . Lazy Loading tersi, istekli yüklemedir . Lazy Loading, 
web sayfalarının daha hızlı yüklenmesini sağlamak için yalnızca ihtiyaç duyulduğunda görünmelerini sağlamak için web'deki görsellerde büyük ölçüde kullanılır..

Lazy Loading, uygulamadaki farklı anlarda ortaya çıkabilir, ancak genellikle kaydırma ve gezinme gibi bazı kullanıcı etkileşimlerinde olur. 
