Puzzle Game
Bu proje, bir görseli parçalara ayırarak kullanıcıya sunduğu parçaları doğru yerlere sürükleyip bırakma (drag and drop) mantığıyla oynanabilen bir interaktif puzzle oyunudur. Oyun, HTML, CSS ve JavaScript ile geliştirilmiş olup, hem masaüstü hem mobil cihazlarla uyumlu olacak şekilde responsive tasarlanmıştır.

 Projenin Amacı
Bu projenin temel amacı, kullanıcıların dikkat ve görsel hafıza becerilerini geliştirebilecekleri bir oyun ortamı sağlamaktır. Özellikle HTML5 ve JavaScript'in etkileşimli yapısı kullanılarak sürükle bırak (drag & drop) mekanizması üzerinden keyifli bir deneyim sunulması hedeflenmiştir.

 Temel Özellikler
 5x4 grid yapısında puzzle alanı
 Sürükle & bırak (drag and drop) etkileşimi
 Doğru yerleştirme kontrolü ve başarılı çözümde modal popup bildirimi
 Oyun sonunda yapılan deneme sayısını gösterme
 Responsive ve kullanıcı dostu arayüz
 Yükleme ekranı (loader) ile başlangıç animasyonu
 Kendi görselini yükleyerek puzzle oluşturabilme (opsiyonel)

| Teknoloji            | Açıklama                                                                                     |
| -------------------- | -------------------------------------------------------------------------------------------- |
| HTML            | Sayfa yapısı ve içerik oluşturma                                                             |
| CSS             | Stil ve düzen (Grid, Flexbox, Animasyonlar)                                                  |
| JavaScript  | Dinamik içerik ve oyun mantığı                                                               |
| Modüler JS       | `app.js`, `drag.js`, `drop.js`, `helper.js`, `loader.js` dosyalarına ayrılmış mantıksal yapı |


 puzzle-game/
│
├──  css/
│   └── style.css               → Tüm stil dosyaları burada
│
├──  js/
│   ├── app.js                  → Ana oyun motoru
│   ├── drag.js                 → Sürükleme işlemleri
│   ├── drop.js                 → Bırakma işlemleri
│   ├── helper.js               → Yardımcı işlevler
│   └── loader.js               → Yükleme animasyonu kontrolü
│
├──  images/
│   └── img-1.jpg               → Oyun başlangıç görseli
│
├── index.html                  → Ana HTML sayfası
└── README.md                   → Proje açıklama dosyası


Geliştirme Süreci
Bu proje geliştirilirken:

HTML ve CSS ile responsive ve modern bir arayüz tasarlandı.

JavaScript kullanılarak sürükle-bırak mekanizması sıfırdan inşa edildi.

Oyun mantığı için konum karşılaştırma, deneme sayısı, başarı kontrolü gibi işlevler geliştirildi.

Kod yapısı, modüler ve okunabilir olacak şekilde organize edildi.

Geliştiricinin isteğine göre farklı görsellerle kolayca yeniden oynanabilir hale getirildi.


Öğrenilenler & Kazanımlar
Bu proje sayesinde:

dragstart, dragover, drop gibi olay dinleyicilerinin nasıl çalıştığı öğrenildi.

CSS Grid ve Flexbox kullanılarak düzenli ve esnek arayüzler tasarlandı.

DOM üzerinde dinamik manipülasyon teknikleri geliştirildi.

Proje modülerliği ve yeniden kullanılabilir kod yapıları hakkında bilgi sahibi olundu.


Bilinen Eksikler ve Geliştirme Fikirleri
Kullanıcının kendi görselini yükleyerek puzzle oluşturması (kısmen entegre, geliştirilebilir)

Zorluk seviyesi (farklı grid boyutları) eklenmesi

Parçaların rastgele karıştırılma mantığının daha sofistike hale getirilmesi

Skor sistemi ve zamanlayıcı gibi özelliklerin eklenmesi
