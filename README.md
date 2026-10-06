<div align="center">

# Furkan Acar

**İstanbul'da full-stack geliştirici.** Türkiye'de e-ticaret operasyonunu ve çeviri kalitesini
**ölçen, kanıtlayan ve otomatikleştiren** açık kaynak araçlar yazıyorum: pazaryeri verisini açan
araçlar, deterministik kalite kapıları ve kanıt göstermeyen çıktı üretmeyen çıkarım araçları.

</div>

## Öne çıkan projeler

| Proje | Ne yapar | Kanıt |
|---|---|---|
| [**clause-cite**](https://github.com/acar32furkan-glitch/clause-cite) [![CI](https://github.com/acar32furkan-glitch/clause-cite/actions/workflows/ci.yml/badge.svg)](https://github.com/acar32furkan-glitch/clause-cite/actions) | Sözleşme/şartname metnini **birebir alıntı + `dosya:satır`** kanıtıyla aksiyon maddelerine çeviren deterministik CLI. Alıntısı gösterilemeyen madde çıkarılmaz; `must`/`should`/`may` asla birleştirilmez. | 217 test · %100 kapsam · alıntı doğrulaması 48/48 · altın set 5/5 |
| [**trendyol-mcp**](https://github.com/acar32furkan-glitch/trendyol-mcp) [![CI](https://github.com/acar32furkan-glitch/trendyol-mcp/actions/workflows/ci.yml/badge.svg)](https://github.com/acar32furkan-glitch/trendyol-mcp/actions) | Trendyol/Hepsiburada satıcı verisini (stok, fiyat, SLA, yorum, iade) **salt-okunur** MCP sunucusu olarak açan araç — yazma ucu yok. | 84 test · %91 kapsam · iki pazaryeri adaptörü |
| [**locale-gate**](https://github.com/acar32furkan-glitch/locale-gate) [![CI](https://github.com/acar32furkan-glitch/locale-gate/actions/workflows/ci.yml/badge.svg)](https://github.com/acar32furkan-glitch/locale-gate/actions) | TR↔EN ürün metinleri için deterministik çeviri kalite kapısı: terminoloji, yer tutucu/ölçü, diakritik, uzunluk. **Hiçbir ölçüm LLM'e bağlı değil.** | 119 test · %96 kapsam · altın set 3/3 |
| [**marketplace-sentinel**](https://github.com/acar32furkan-glitch/marketplace-sentinel) [![CI](https://github.com/acar32furkan-glitch/marketplace-sentinel/actions/workflows/ci.yml/badge.svg)](https://github.com/acar32furkan-glitch/marketplace-sentinel/actions) | Aynı ürünün kanallar arası çakışmasını (liste yok, fiyat sapması, stok) yakalayıp yalnızca **değişeni** bildiren Türkçe nöbetçi. | 149 test · %97,9 kapsam · durum + dedupe |

Dördü de: **MIT** · CI yeşil (Python 3.12 + 3.13 · ruff · mypy strict · pytest) · `v0.1.0` release ·
salt-okunur tasarım ([ADR-0001](https://github.com/acar32furkan-glitch/trendyol-mcp/blob/main/docs/adr/0001-read-only-by-design.md)).

## Diğer işler

| Proje | Ne |
|---|---|
| [net-kod](https://github.com/acar32furkan-glitch/net-kod) | AI kodlama ajanları için çıktı protokolü: aksiyon önce, gürültü yok (spesifikasyon) |
| [sa-printpro](https://github.com/acar32furkan-glitch/sa-printpro) | Trendyol satıcıları için %100 statik, white-label vitrin şablonu (Astro + Cloudflare Pages) |
| [ceviri-kalite-kontrol](https://github.com/acar32furkan-glitch/ceviri-kalite-kontrol) | AI destekli çeviri kalite kontrol prototipi (Next.js + DeepSeek) |
| [arvonya-website](https://github.com/acar32furkan-glitch/arvonya-website) | Müşteri kurumsal sitesi — TanStack Start (SSR) + Supabase · [canlı](https://arvonya-site.vercel.app) |
| [enorpa-eclectic-web](https://github.com/acar32furkan-glitch/enorpa-eclectic-web) | Çok dilli (TR/EN/RU) kurumsal site + içerik paneli; WordPress göçü, 301 + JSON-LD · [canlı](https://enorpa-eclectic-web.vercel.app) |
| [smart-second-brain-tr](https://github.com/acar32furkan-glitch/smart-second-brain-tr) | Smart Second Brain Obsidian eklentisinin Türkçe sürümü: arayüz yerelleştirmesi, en/tr i18n katmanı ve **ölçülebilir yerelleştirme kapısı** ([kurulabilir 2.3.1 sürümü](https://github.com/acar32furkan-glitch/smart-second-brain-tr/releases/tag/2.3.1)) — orijinal: [s2b-dev](https://github.com/s2b-dev/smart-second-brain), MIT |

## Nasıl çalıştığım

- **Deterministik ve kanıtlı:** her rakam bir kaynağa bağlanır (komut çıktısı, `dosya:satır`, API yanıtı).
  Ölçülemeyen şey "belirsiz" olarak işaretlenir — tahmin edilmez, uydurulmaz.
- **Salt-okunur ve ToS'a saygılı:** pazaryeri entegrasyonlarında yazma ucu yok; entegrasyonlar resmî
  API ve kullanıcı onayıyla çalışır.
- **CI kapısı:** ruff · `mypy --strict` · pytest + kapsam eşiği · çoklu Python matrisi. Yeşil olmayan iş yayınlanmaz.
- **Karar kaydı:** her projede `docs/adr/` altında "ne yapıyoruz, neyi **yapmıyoruz** ve neden".

**Stack:** Python (FastAPI, pydantic, uv) · TypeScript (React/Next, Svelte) · GitHub Actions · MCP ·
SQL/Supabase · Vercel

---

<details>
<summary><b>English</b></summary>

Full-stack developer based in Istanbul. I build open-source tooling that **measures and automates**
Turkish e-commerce operations and localization quality: read-only marketplace data servers,
deterministic quality gates, and extraction tools that prove every claim with a citation.
See the four projects above — all MIT-licensed, CI-green, with tests, ADRs and releases.

</details>

**İletişim:** acar32furkan@gmail.com · [trendyol-mcp](https://github.com/acar32furkan-glitch/trendyol-mcp) · [locale-gate](https://github.com/acar32furkan-glitch/locale-gate) · [marketplace-sentinel](https://github.com/acar32furkan-glitch/marketplace-sentinel) · [clause-cite](https://github.com/acar32furkan-glitch/clause-cite)
