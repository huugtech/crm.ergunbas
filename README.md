# ERGÜNBAŞ CRM — GitHub Pages

**Bu klasördeki `index.html` dosyası GitHub'a yüklenecek dosyadır.** GitHub Pages yalnızca kullanıcıyı güncel Apps Script CRM paneline yönlendirir; burada müşteri bilgileri veya gizli anahtar bulunmaz.

## GitHub üzerinde güncelleme

1. GitHub hesabına giriş yap ve CRM web sayfanın bulunduğu depoyu (repository) aç.
2. **Code → Add file → Upload files** seç.
3. Bu klasördeki **`index.html`** dosyasını deponun **ana dizinine** yükle. Mevcut `index.html` varsa bununla değiştir.
4. Altta **Commit changes** diyerek kaydet.
5. GitHub Pages henüz açık değilse: **Settings → Pages → Build and deployment → Deploy from a branch → main → /(root) → Save**.
6. GitHub Pages bağlantını aç: otomatik olarak Apps Script'teki **güncel CRM** ekranına yönleneceksin.

> Ana uygulamanın kendisi `Code.gs` ve `Index.html` ile Google Apps Script'te kalır. **Code.gs** dosyasını GitHub'a yükleme: özel erişim anahtarı içeriyor olabilir.

## Bir sonraki sürümde sıralama

1. Apps Script'teki `Code.gs` ve `Index.html` güncelle.
2. Apps Script'te **Yeni sürüm → Yeniden dağıt**.
3. `/exec` bağlantısı değiştiyse GitHub `index.html` içindeki bağlantıyı güncelle ve GitHub'a tekrar yükle. Aynı dağıtım güncellendiyse Github tarafını tekrar yayımlaman gerekmez.

> GitHub Pages ve Apps Script herkese açık ise, site bağlantısını bilenler CRM uygulamasına erişebilir. Gerçek kimlik doğrulama ve yetkilendirme ayrıca gereklidir.
