# PilotGuard SmartWatch

> **CDSA Projesi — Aşama 0 · Uçuş Öncesi ve Uçuş İçi İzleme**
> Pilot hazırlık ve stres izleme simülatörü

🔗 **Canlı Demo:** [orfeomete.github.io/pilotguard-app-](https://orfeomete.github.io/pilotguard-app-)

---

## Hakkında

PilotGuard, pilotun uçuş öncesi ve uçuş esnasındaki fizyolojik ve psikolojik hazırlık durumunu kalp atış hızı, HRV, stres indeksi ve uyku kalitesi parametreleriyle gerçek zamanlı olarak izleyen bir akıllı saat simülatörüdür.

Uygulama, **Tamamlayıcı Tanısal Emniyet Yaklaşımı (CDSA)** projesinin bireysel izleme katmanını oluşturur. ATAConf'25 konferansında sunulan *"Mekanikten Yapay Zekaya Evrilen Pilot Saatlerinin Uçuş Emniyetindeki Yeni Rolü"* başlıklı bildiride teorik temelleri açıklanmaktadır.

---

## Özellikler

- 🌐 **TR/EN dil desteği** — sağ üstteki butonla tam arayüz değişimi
- ⚙️ **Korona düğmesi** — gerçek akıllı saat tasarım estetiği
- 🔄 **Canlı simülasyon** — 4 saniyede bir gerçekçi veri güncellemesi
- 👆 **Sol tık / Sağ tık** — ekranlar arası geçiş

**Ekranlar:** Ana Ekran · Kalp Atış Hızı · Stres Seviyesi · Uyku Kalitesi · Uçuş Durumu · Öneriler

---

## İzlenen Parametreler

- **Kalp Atış Hızı (KA)** — BPM cinsinden anlık değer
- **HRV** — Kalp atış değişkenliği (ms), yorgunluk ve stres göstergesi
- **Stres İndeksi** — 1–10 arası yapay zekâ tabanlı skor
- **Uyku Kalitesi** — Uçuş öncesi dinlenme kalitesi (%)
- **Uçuş Hazırlığı** — Tüm parametrelerin birleşik hazırlık skoru

---

## CDSA Ekosistemi

```
PilotO2          →  Hipoksi ve risk tahmini
PilotGuard       →  Uçuş öncesi hazırlık ve stres izleme (bu repo)
PilotReflect EFB →  Uçuş sonrası kişisel değerlendirme
PilotSense AUTH  →  Kriptografik çoklu imza (Aşama 1)
PilotSense OPS   →  Anonim filo izleme (Aşama 2)
```

---

## Teknik Altyapı

- **React 18** · **Tailwind CSS** · **Babel Standalone** · **GitHub Pages**
- Harici bağımlılık yok, tek dosya (`index.html`)

---

## Kaynak

- Cantekin, M. (2025). *Mekanikten Yapay Zekaya Evrilen Pilot Saatlerinin Uçuş Emniyetindeki Yeni Rolü*. ATAConf'25, Yayın No: 10232620.
- Cantekin, M. (2025). *Tamamlayıcı Tanısal Emniyet Yaklaşımı (CDSA) Kapsamında Giyilebilir Teknolojiler ve Uçuş Emniyeti Optimizasyonu*.

---

> ⚠️ **Sadece eğitim ve araştırma amaçlıdır.** Tüm veriler sentetiktir.

*CDSA Projesi · ICAO Ek-13 · GDPR Madde 9*
