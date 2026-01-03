# MTP Bypass Redirect Pages

Bu klasör, MTP Bypass aracı için Android Intent URI yönlendirme sayfalarını içerir.

## GitHub Pages Kurulumu

1. **Yeni GitHub Deposu Oluştur:**
   - GitHub'da yeni bir public repo oluşturun (örn: `mtp-bypass-pages`)
   
2. **Bu Klasörü Yükle:**
   ```bash
   cd github_pages
   git init
   git add .
   git commit -m "Initial commit"
   git remote add origin https://github.com/KULLANICI_ADI/mtp-bypass-pages.git
   git push -u origin main
   ```

3. **GitHub Pages'i Aktifleştir:**
   - Repo Settings > Pages
   - Source: "Deploy from a branch"
   - Branch: "main" / "(root)"
   - Save

4. **URL'yi Not Al:**
   - Örnek: `https://KULLANICI_ADI.github.io/mtp-bypass-pages/`

## Sayfalar

| Dosya | Açıklama |
|-------|----------|
| `index.html` | Ana sayfa (opsiyonel) |
| `settings.html` | Android Ayarlar |
| `adb.html` | Geliştirici Seçenekleri |
| `browser.html` | Tarayıcı Açma |
| `files.html` | Dosya Yöneticisi |
| `store.html` | Play Store |
| `dialer.html` | Telefon Tuş Takımı |
