# gym — Claude Code ile spor salonu koçu

Kurulum ve kullanım (Claude Code içinde, repo kökünden):

| Komut | Ne zaman | Ne yapar |
|---|---|---|
| `/gym-kurulum` | Bir kez | Sana sorular sorar, `profil.md` ve `program.md`'yi doldurur |
| `/gym-bugun` | Salona girmeden | Geçmişine göre bugünkü seansı ağırlıklarıyla planlar |
| `/gym-kaydet bench 60 3x8 ...` | Set aralarında / sonunda | Söylediğini `log/` altına tabloya işler |
| `/gym-hafta` | Hafta sonunda | İlerlemeyi değerlendirir, programı günceller |

Telefondan: Claude uygulamasında bu repoyla bir cloud oturumu aç, komutları yaz.
Her seanstan sonra Claude değişiklikleri commit'leyip push'lar, böylece veriler kaybolmaz.

İleride: Hevy / Apple Health / Garmin kullanırsan ilgili MCP sunucusunu ekleyip verileri otomatik çekebilirsin
(`chrisdoc/hevy-mcp`, `neiltron/apple-health-mcp`, `Nicolasvegam/garmin-connect-mcp`).
