# spam-call-shield

**İstenmeyen satış aramaları ve SMS'lerle yasal yoldan mücadele etmek için yapay zekâ ajan paketi.**

Claude, ChatGPT ya da Gemini'yi şu işlerde sana yardım eden dikkatli bir asistana dönüştürür:

1. Ülkenin resmî sisteminde ticari aramaları **reddetmek**
2. Yine de gelen her istenmeyen aramayı ve SMS'i, şikâyette işe yarayacak biçimde **kaydetmek**
3. Numaranın arkasında gerçekte kim olduğunu, yalnızca herkese açık kaynaklarla **bulmak**
4. Şikâyet dilekçesini ya da ihtarnameyi **hazırlamak**

Ajan hiçbir şeyi kendi başına göndermez, dosyalamaz, kimseyi aramaz. Her adımın kontrolü sendedir.

> Fikir, birinin yapay zekâ ajanına numarasını ABD'nin "Aramayın" listesine kaydettirdiği viral bir paylaşımdan çıktı. Ajan sınırlarını kendisi açıkça söylemişti: sahte (VoIP) numaraların izi mahkeme kararı olmadan sürülemez ve izin almadan hiçbir şey dosyalamaz. Bu paket o dürüstlük üzerine kuruldu.

## Bölgeni seç

| Bölge | Gerçekçi olarak ne elde edersin | Durum | Başla |
|---|---|---|---|
| 🇹🇷 **Türkiye** | Firma **idari para cezası** alır; para devlete gider, sana ödenmez | ✅ Hazır | [regions/tr](regions/tr/README.md) |
| 🇺🇸 **ABD** | TCPA'ya göre arama başına **500 $'a kadar** tazminat (kasıtlıysa mahkeme takdiriyle 3 katına kadar) | ✅ Hazır | [regions/us](regions/us/README.md) |
| 🇪🇺 **AB** | GDPR hakları: "Numaramı nereden aldın?" diye sorma, silme isteme, kuruma şikâyet | 🤝 **Katkı bekleniyor** | [regions/eu](regions/eu/README.md) |

## Nasıl kullanılır (5 dakika)

**A yolu: herhangi bir sohbet botu (kurulum yok)**
1. `regions/tr/promptlar/ajan-prompt.md` dosyasındaki metni kopyala.
2. Claude, ChatGPT ya da Gemini'ye ilk mesaj olarak yapıştır.
3. Arama günlüğünü `regions/tr/sablonlar/arama-gunlugu.csv` şablonunda tut (Excel ya da Google E-Tablolar ile açılır).

**B yolu: Claude Code**
`claude-skill/spam-call-shield/` klasörünü `~/.claude/skills/` içine kopyala ve `/spam-call-shield` yaz.

## Başlamadan önce oku

- **Hukuki tavsiye değildir.** [DISCLAIMER.md](DISCLAIMER.md). Kaynaklar ve kontrol tarihleri her bölge klasöründe yazıyor.
- **Gizlilik.** Arama günlüğünde kişisel veri var. Yapay zekâya bir şey yapıştırmadan önce [PRIVACY.md](PRIVACY.md) dosyasını oku.
- **Arama kaydı suç olabilir.** Türkiye'de karşı tarafın rızası olmadan, katıldığın bir konuşmayı bile kaydetmek suçtur (TCK 133/2). Rehber, kanıtı güvenli yoldan nasıl tutacağını anlatıyor.
- **Dolandırıcılık ayrı bir konu.** Arayan seni dolandırmaya çalışıyorsa polise ya da savcılığa bildir. Bu paket ticari aramalar içindir.

## Lisans

[MIT](LICENSE)
