# Clubs-Nation-League
KÜRESEL KULÜP LİGİ — MODÜLER GITHUB PAGES YAYINI

DOSYALAR
1. index.html       : Uygulama motoru. Normal güncellemelerde değiştirmeniz gerekmez.
2. tournament.json : Canlı turnuva verisi. Siteyi güncellemek için yalnızca bu dosyayı değiştirin.
3. serve_local.bat  : Windows üzerinde yerel test sunucusu.

GITHUB PAGES
- index.html ve tournament.json dosyalarını deponun aynı klasörüne yükleyin.
- Canlı veriyi değiştirmek için uygulamadaki “tournament.json İndir” düğmesini kullanın.
- İndirilen dosyayı GitHub'daki mevcut tournament.json dosyasının üzerine yükleyin.
- Uygulama her açılışta JSON'u önbelleksiz kontrol eder; dosya içeriği değişmişse IndexedDB otomatik yenilenir.

ÖNEMLİ
- Dosya adı küçük harflerle tam olarak tournament.json olmalıdır. GitHub Pages dosya adlarında büyük/küçük harfe duyarlıdır.
- tournament.json şifreli yedek olamaz; “Okunabilir JSON” biçimi kullanılmalıdır.
- index.html dosyasını çift tıklayarak file:// ile açarsanız tarayıcı JSON fetch işlemini güvenlik nedeniyle engeller. Yerel testte serve_local.bat kullanın.
- Yerel görünüm tercihleri (tema, animasyon, ses gibi) yeni JSON senkronunda korunur; turnuva verisi JSON'dan güncellenir.
