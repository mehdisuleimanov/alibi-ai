# Alibi AI — prototip

Cebindeki yapay zekâ kriz yöneticisi: sıkıcı bir buluşmadan, uzayan bir yemekten veya bitmeyen bir toplantıdan inandırıcı bir bahaneyle çıkmanı sağlar.

Tek dosyalık, tıklanabilir telefon prototipi (`index.html`, build gerektirmez).

## Neler var

- Turuncu karşılama ekranı ve 3 tanıtım slaytı
- 7 dilde arayüz: EN, ES, PT-BR, DE, FR, TR, AZ
- Yazarak veya basılı tutarak (Sesli SOS) durum anlatma
- Kaçış paketi: bahane (3 şiddet seviyesi), oyunculuk ipuçları, sahte kilit ekranı bildirimi, sahte gelen arama
- Bahane kasası ve paylaşım kartı, Alibi Pro ekranı
- Hesap menüsü: profil, kişiselleştirme, ayarlar

## Gemini

Ayarlar → **Gemini AI** bölümüne kendi Gemini API anahtarını yapıştırırsan bahaneleri Gemini yazar ve Sesli SOS gerçek mikrofonla çalışır. Anahtar yalnızca o tarayıcının `localStorage`'ında saklanır; repoya veya dosyaya yazılmaz. Anahtar yoksa uygulama hazır örnek bahanelerle demo modunda çalışır.

> Not: Tarayıcıdan doğrudan API çağrısı yapıldığı için bu kurulum yalnızca prototip içindir. Gerçek kullanıcılar için anahtar bir sunucu fonksiyonunda tutulmalıdır.

## Çalıştırma

`index.html` dosyasını tarayıcıda açman yeterli. Vercel'de statik site olarak yayınlanır, ek ayar gerekmez.
