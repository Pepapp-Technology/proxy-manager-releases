# Proxy Manager · İndirmeler

Pepapp çalışanlarının staging ve production veritabanlarına Cloud SQL Proxy üzerinden
bağlanmasını sağlayan masaüstü uygulamasının kurulum dosyaları.

**[En son sürümü indir →](../../releases/latest)**

| Platform | Dosya |
| --- | --- |
| Windows 10 / 11 | `Proxy-Manager_<sürüm>_windows-x64-setup.exe` |
| macOS · Apple Silicon (M1 ve sonrası) | `Proxy-Manager_<sürüm>_macos-arm64.dmg` |
| macOS · Intel | `Proxy-Manager_<sürüm>_macos-x64.dmg` |
| Linux · Debian / Ubuntu | `Proxy-Manager_<sürüm>_linux-amd64.deb` |
| Linux · Diğer | `Proxy-Manager_<sürüm>_linux-amd64.AppImage` |

Her sürüm sayfasında kurulum adımları, ilk açılış uyarıları ve SHA-256 değerleri bulunur.

## Gereksinimler

- Bir **letspepapp.com** Google hesabı. Uygulama başka hesaplarla açılmaz.
- [Google Cloud CLI (gcloud)](https://cloud.google.com/sdk/docs/install). Kurulu değilse uygulama
  indirme bağlantısını kendisi gösterir.
- Veritabanlarına erişim yetkisi (Cloud SQL Client rolü).

Bu repo yalnızca dağıtım içindir. Uygulamanın kaynak kodu şirketin private reposundadır.
`update.json` dosyaları, uygulamanın güncelleme kontrolü için okunur.
