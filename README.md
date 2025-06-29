Puzzle Drag & Drop Oyunu
Bu proje, kullanıcıların parçaları doğru yerlere sürükleyerek bir bulmacayı çözmesini sağlayan basit bir HTML, CSS ve JavaScript tabanlı oyun uygulamasıdır. Oyun, doğru ve yanlış hamleleri sayarak oyuncuya sonuç bildirimi verir.

Proje Yapısı
css
Kopyala
Düzenle
game/
 index.html
 style.css
 script.js
 js/
dragDrop.js
elements.js
positionElements.js
images/
     img-1.jpg
     img-2.jpg
     ...


Nasıl Çalıştırılır?
Projeyi indirin veya ZIP dosyasını çıkarın:
index.html dosyasını bir web tarayıcısında açın:

Windows: index.html dosyasına çift tıklayın.

VS Code kullanıyorsanız "Live Server" eklentisi ile çalıştırabilirsiniz.

Oyunu oynayın: Parçaları doğru yerlere sürükleyerek yerleştirin.

Oyun Mantığı
Kullanıcı, resim parçalarını doğru kutulara sürüklemelidir.

Her doğru yerleştirme puan kazandırır.

Tüm parçalar doğru yerleştirildiğinde bir modal pencere ile başarı mesajı gösterilir.

Toplam yanlış hamle sayısı da gösterilir.

 Kullanılan Teknolojiler
HTML – Yapı

CSS – Stil

JavaScript (ES6 Modules) – Oyun mantığı ve sürükle bırak işlevselliği

 Notlar
dragDrop.js, sürükle-bırak olaylarını ve oyun akışını kontrol eder.

elements.js, DOM elementlerini merkezi olarak yönetir.

positionElements.js, oyun ızgarasını ve yerleştirme alanlarını düzenler.
