# 📝 Kullanıcı Kayıt Formu

Kullanıcı adı ve şifre alanlarını kontrol eden basit bir kayıt formu. UIKit ile geliştirilmiş bir iOS uygulamasıdır.

## Özellikler

- **Form doğrulama:** Kullanıcı adı boşsa, şifre boşsa ya da iki şifre birbirini tutmuyorsa hata mesajı gösterir.
- **Uyarı pencereleri:** Sonuçlar `UIAlertController` ile kullanıcıya gösterilir.
- Uyarı oluşturma işi tek bir yardımcı fonksiyonda (`makeAlert`) toplanmıştır.

## Teknolojiler

| | |
|---|---|
| Dil | Swift |
| Arayüz | UIKit, Storyboard |
| Kullanılanlar | `IBOutlet`, `IBAction`, `UITextField`, `UIAlertController` |

## Çalıştırma

1. Depoyu klonlayın:
   ```bash
   git clone https://github.com/hilaltezcannn/KullaniciKayitFormu.git
   ```
2. `KullaniciKayitFormu.xcodeproj` dosyasını Xcode ile açın.
3. Bir iPhone simülatörü seçip **▶︎ Run** ile çalıştırın.
