---
title: Gizlilik Politikası
nav_order: 3
permalink: /privacy.tr/
---

# Habion — Gizlilik Politikası

_Yürürlük tarihi: 20 Mayıs 2026_
_Son güncelleme: 20 Mayıs 2026_

Habion ("uygulama", "biz") **Ininia** ("geliştirici") tarafından geliştirilen bir alışkanlık takip uygulamasıdır. Bu Gizlilik Politikası, uygulamanın hangi verileri nasıl işlediğini açıklar.

Habion **yerel öncelikli** çalışacak şekilde tasarlandı. Hesap, kayıt veya bulut senkronu gerektirmez. Oluşturduğun alışkanlıklar, tamamlamalar ve ayarlar **cihazında kalır**.

---

## 1. Topladıklarımız

### 1.1 Yalnızca cihazında saklanan veriler

- Alışkanlık tanımları (başlık, renk, ikon, plan, isteğe bağlı hatırlatma saati)
- Tamamlama geçmişi (her check-in için tarih ve saat)
- Uygulama tercihleri (dil, saat formatı, bildirim aç/kapat, hafta başlangıcı)

Bu veriler telefonunda şifrelenmiş yerel depolamada (MMKV) tutulur. **Sunucularımıza hiçbir zaman aktarılmaz** — çünkü bir sunucumuz yok. Uygulamayı kaldırmak tüm bu veriyi kalıcı olarak siler.

### 1.2 Tanılama (yalnızca yayın sürümlerinde)

Uygulama yayın sürümünde çökerse veya beklenmedik bir hata alırsa, [Sentry](https://sentry.io) üzerinden anonim bir hata raporu alıyoruz. Bu raporlar şunları içerebilir:

- Çökme stack trace'i ve hataya yol açan kısa olay günlüğü
- Cihaz modeli, işletim sistemi sürümü, uygulama sürümü
- Anonim bir kurulum kimliği (ilk açılışta üretilen rastgele UUID)
- IP adresi (Sentry tarafından kısa süreliğine kaba konum için kullanılıp [Sentry'nin saklama politikasına](https://docs.sentry.io/security-legal-pii/security/ip-address-retention/) göre atılır)

Bu raporları **yalnızca** hata bulup düzeltmek için kullanırız. Kimliğinle ilişkilendirmeyiz (zaten kimliğini bilmiyoruz).

Tanılama, **geliştirme sürümlerinde devre dışıdır**. Sadece App Store / Play Store sürümlerinde aktiftir.

Sentry gizlilik politikası: <https://sentry.io/privacy/>

### 1.3 Toplamadıklarımız

- E-posta, ad, telefon, adres, yaş veya başka kişisel bilgi yok
- Konum verisi yok
- Rehber, fotoğraf, takvim, mikrofon veya kamera erişimi yok
- Reklam kimliği yok (IDFA / GAID)
- Üçüncü taraf analiz veya izleme SDK'sı yok
- Sosyal medya bağlantısı yok
- Biyometrik veri yok
- Tuş veya ekran kaydı yok

---

## 2. Bildirimler

Habion, alışkanlık hatırlatmaları ve günlük motivasyon için **yerel bildirimler** zamanlar. Bildirimler iOS / Android tarafından senin cihazında üretilir — push bildirim sunucumuz yoktur.

Bildirimleri sistem ayarlarından veya Habion içinden (**Ayarlar → Bildirimler**) kontrol edebilirsin.

---

## 3. İzinler

| İzin | Neden gerekli |
| --- | --- |
| Bildirimler | Yerel alışkanlık hatırlatmaları ve motivasyon bildirimleri için |

Konum, kamera, mikrofon, rehber, fotoğraf veya başka hassas izin istemiyoruz.

---

## 4. Üçüncü taraf hizmetler

| Hizmet | Amaç | Paylaşılan veri |
| --- | --- | --- |
| [Sentry](https://sentry.io) | Hata tanılama (yalnızca yayın sürümleri) | Anonim çökme raporları, cihaz bilgisi, uygulama sürümü |
| [Expo](https://expo.dev) | Uygulama geliştirme / çalışma platformu | Çalışma anında yok |
| [Apple](https://www.apple.com/legal/privacy/) / [Google](https://policies.google.com/privacy) | Sistem düzeyinde bildirim ve uygulama dağıtımı | Apple / Google tarafından doğrudan yönetilen standart platform telemetrisi |

**Hiçbir reklam ağıyla ortaklığımız yoktur.** Verini **kimseye satmıyor, kiralamıyor veya takas etmiyoruz**.

---

## 5. Çocukların gizliliği

Habion 4+ yaş için uygundur. Çocuklar dahil hiç kimseden bilerek kişisel veri toplamıyoruz. 13 yaş altıysan (veya bölgendeki eşdeğer asgari yaş altıysan), uygulamayı yalnızca veli iznini alarak kullan.

---

## 6. Haklarınız

Tüm alışkanlık verilerin cihazında olduğundan:

- **Bir alışkanlığı sil** — alışkanlığın detay sayfasına git → "Alışkanlığı sil"e dokun. Alışkanlık ve tüm geçmişi kalıcı olarak silinir.
- **Her şeyi sil** — uygulamayı kaldır. Tüm yerel veri otomatik olarak silinir.
- **Tanılama verisi silme** — aşağıdaki e-postaya yaz, talebine eşleşen anonim kurulum kimliğini 30 gün içinde Sentry'den temizleriz.

AB / Birleşik Krallık (GDPR), Kaliforniya (CCPA / CPRA) ve benzeri düzenlemelerin geçerli olduğu bölgelerin sakinleri, veri koruma haklarını (erişim, silme, taşınabilirlik, itiraz) kullanmak için aşağıdaki adresten bize ulaşabilir. Kullanıcı hesabı tutmadığımız için çoğu talep uygulamayı kaldırarak veya yukarıdaki tanılama silme süreciyle karşılanır.

---

## 7. Veri saklama

| Veri | Yer | Saklama süresi |
| --- | --- | --- |
| Alışkanlıklar, tamamlamalar, tercihler | Cihazın | Sen silene veya uygulamayı kaldırana kadar |
| Çökme tanılaması | Sentry | Sentry saklama politikasına göre en fazla 90 gün |

---

## 8. Güvenlik

Cihazındaki yerel veri, işletim sisteminin standart sandbox'ı ve MMKV'nin yerleşik şifrelemesi ile korunur. Sentry'ye giden tanılama verisi TLS ile şifrelenir.

Hiçbir sistem %100 güvenli değildir. Endüstri standardı uygulamalara uymaya çalışıyoruz ancak mutlak güvenliği garanti edemeyiz.

---

## 9. Politikadaki değişiklikler

Veri işleme şeklimizi önemli ölçüde değiştirirsek, sayfanın üstündeki "Son güncelleme" tarihini değiştirir ve değişikliği uygulamanın sürüm notlarında duyururuz. Bir değişiklikten sonra uygulamayı kullanmaya devam etmek, güncellenmiş politikanın kabulü anlamına gelir.

---

## 10. İletişim

Sorular, silme talepleri veya geri bildirim:

📧 **support@habion.app**

> **Geliştiriciler: App Store / Play Store'a sunmadan önce yukarıdaki e-postayı izlediğin gerçek bir adresle değiştir.** Apple ve Google denetçileri buradan ulaşır.
