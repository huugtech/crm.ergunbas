# ERGUNBAS Group — GitHub Pages yayın paketi

Bu klasör, sağlanan `index.html` dosyasını değiştirmeden GitHub Pages üzerinden yayımlamak içindir.

## Yayımlama

1. GitHub'da yeni bir depo (repository) oluşturun.
2. `index.html` ve `.nojekyll` dosyalarını **deponun ana dizinine** yükleyin (ZIP dosyasını doğrudan yüklemeyin; önce açın).
3. Depoda **Settings → Pages → Build and deployment** bölümünü açın.
4. **Source: Deploy from a branch**, **Branch: main**, **Folder: /(root)** seçin ve **Save** butonuna tıklayın.
5. GitHub Pages bölümünde yayın bağlantısı görüntülenecektir. Tipik adres: `https://KULLANICI-ADI.github.io/DEPO-ADI/`.

## Önemli: Veri bağlantıları ve güvenlik

- HTML içinde Google Sheets kimliği ve dış bağlantılar vardır. GitHub Pages'te yayınlanan HTML kodu **herkese açıktır**.
- Google Apps Script `Code.gs` sunucu kodu bu pakete dahil değildir: yüklenen dosyada yoktur. CRM senkronizasyonu, WhatsApp kayıtları, telefon düzeltmeleri ve tüm kullanıcılarda ortak ayarlar, mevcut **Apps Script web uygulamasının** doğru yapılandırılmış ve erişilebilir olmasına bağlıdır.
- **API erişim anahtarını bu HTML dosyasına, GitHub deposuna veya README'ye yazmayın.** Panel bu anahtarı kullanıcıdan alıp tarayıcı oturumunda tutuyor; statik barındırma tek başına kullanıcı yetkilendirmesi sağlamaz.
- Bu panel müşteri verileri işlediği için, erişim denetimi ve sunucu tarafı izinleri doğrulanmadan herkese açık yayımlanması önerilmez. GitHub Pages özel bir yönetim paneli için erişim kontrollü barındırma sağlamaz.
- Google Fonts ve favicon internet bağlantısına ihtiyaç duyar.
