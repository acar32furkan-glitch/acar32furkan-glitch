<div align="center">

# Furkan Acar

**Full-stack geliştirici · e-ticaret otomasyonu ve AI araçları** — Isparta, Türkiye · uzaktan çalışmaya açık  
**Full-stack developer · e-commerce automation & AI tooling** — Isparta, Türkiye · open to remote


**[Web CV](https://acar32furkan-glitch.github.io/cv/)** · [Özet görünüm](https://acar32furkan-glitch.github.io/cv/#r=1) · [LinkedIn](https://www.linkedin.com/in/furkan-acar-dev/)

</div>

Küçük işletmeler için canlı sistemler kuruyorum (Shopify ve pazaryeri entegrasyonları, restoran operasyon paneli,
kurumsal siteler) ve Türkiye'de e-ticaret operasyonunu ile çeviri kalitesini **ölçen, kanıtlayan ve
otomatikleştiren** açık kaynak araçlar yayınlıyorum: pazaryeri verisini açan araçlar, deterministik kalite
kapıları ve kanıt göstermeyen çıktı üretmeyen çıkarım araçları.

## Şu an

- **Arıyorum:** Shopify ve pazaryeri entegrasyonu (Trendyol, n11, Hepsiburada, Amazon.com.tr) işlerinde uzaktan veya hibrit
  pozisyonlar ve seçilmiş freelance projeler.
- **Üzerinde çalışıyorum:** açık kaynak araçlarımın bakımı (MCP sunucuları, kalite kapıları) ve küçük işletmeler için canlı
  sistemler.
- **Currently:** open to remote or hybrid roles and selected freelance work in e-commerce integration; contact below.

## Öne çıkan projeler

| Proje | Ne yapar | Kanıt |
|---|---|---|
| [**clause-cite**](https://github.com/acar32furkan-glitch/clause-cite) [![CI](https://github.com/acar32furkan-glitch/clause-cite/actions/workflows/ci.yml/badge.svg)](https://github.com/acar32furkan-glitch/clause-cite/actions) | Sözleşme/şartname metnini **birebir alıntı + `dosya:satır`** kanıtıyla aksiyon maddelerine çeviren deterministik CLI. Alıntısı gösterilemeyen madde çıkarılmaz; `must`/`should`/`may` asla birleştirilmez. | 241 test · %100 kapsam · alıntı doğrulaması 48/48 · altın set 5/5 |
| [**trendyol-mcp**](https://github.com/acar32furkan-glitch/trendyol-mcp) [![CI](https://github.com/acar32furkan-glitch/trendyol-mcp/actions/workflows/ci.yml/badge.svg)](https://github.com/acar32furkan-glitch/trendyol-mcp/actions) | Trendyol/Hepsiburada satıcı verisini (stok, fiyat, SLA, yorum, iade) **salt-okunur** MCP sunucusu olarak açan araç — yazma ucu yok. | 104 test · %93 kapsam · iki pazaryeri adaptörü |
| [**pazaryeri-denetci-mcp**](https://github.com/acar32furkan-glitch/pazaryeri-denetci-mcp) [![CI](https://github.com/acar32furkan-glitch/pazaryeri-denetci-mcp/actions/workflows/ci.yml/badge.svg)](https://github.com/acar32furkan-glitch/pazaryeri-denetci-mcp/actions) | Pazaryeri ürün kataloğunu **17 deterministik kuralla** denetleyen, bulguları önem sırasına göre raporlayan ve bunu **7 araçlı MCP sunucusu** (stdio + Streamable HTTP) olarak AI ajanlarına açan araç. LLM yalnızca düzeltme **önerisi** üretir. | 286 test · eval precision/recall %100 (1000 sentetik ürün) · 10.000 ürün 1,36 sn · [canlı demo](https://pazaryeri-denetci-demo.vercel.app) |
| [**locale-gate**](https://github.com/acar32furkan-glitch/locale-gate) [![CI](https://github.com/acar32furkan-glitch/locale-gate/actions/workflows/ci.yml/badge.svg)](https://github.com/acar32furkan-glitch/locale-gate/actions) | TR↔EN ürün metinleri için deterministik çeviri kalite kapısı: terminoloji, yer tutucu/ölçü, diakritik, uzunluk. **Hiçbir ölçüm LLM'e bağlı değil.** | 168 test · %97 kapsam · altın set 3/3 |
| [**marketplace-sentinel**](https://github.com/acar32furkan-glitch/marketplace-sentinel) [![CI](https://github.com/acar32furkan-glitch/marketplace-sentinel/actions/workflows/ci.yml/badge.svg)](https://github.com/acar32furkan-glitch/marketplace-sentinel/actions) | Aynı ürünün kanallar arası çakışmasını (liste yok, fiyat sapması, stok) yakalayıp yalnızca **değişeni** bildiren Türkçe nöbetçi. | 157 test · %98 kapsam · durum + dedupe |

Beşi de: **MIT** · CI yeşil · `v0.1.0` release. Pazaryeri verisine bağlanan araçlar **salt-okunur tasarımlıdır**
(yazma ucu yok; bkz. [ADR-0001](https://github.com/acar32furkan-glitch/trendyol-mcp/blob/main/docs/adr/0001-read-only-by-design.md)).
Python projeleri: ruff · `mypy --strict` · pytest (3.12 + 3.13) · TS/Node projesi: ESLint · Prettier ·
`tsc` strict · Vitest + eval kapısı. Test ve kapsam sayıları `main` üzerindeki son CI koşularından alınmıştır (17 Kas 2026).

## Diğer işler

| Proje | Ne |
|---|---|
| [net-kod](https://github.com/acar32furkan-glitch/net-kod) | AI kodlama ajanları için çıktı protokolü: aksiyon önce, gürültü yok (spesifikasyon) |
| [sa-printpro](https://github.com/acar32furkan-glitch/sa-printpro) | Trendyol satıcıları için %100 statik, white-label vitrin şablonu (Astro + Cloudflare Pages) |
| [ceviri-kalite-kontrol](https://github.com/acar32furkan-glitch/ceviri-kalite-kontrol) | AI destekli çeviri kalite kontrol prototipi (Next.js) · [canlı demo](https://ceviri-kalite-kontrol.vercel.app) |
| [arvonya-website](https://github.com/acar32furkan-glitch/arvonya-website) | Müşteri kurumsal sitesi — TanStack Start (SSR) + Supabase · [canlı](https://arvonya-site.vercel.app) |
| [enorpa-eclectic-web](https://github.com/acar32furkan-glitch/enorpa-eclectic-web) | Bir kazan üreticisinin WordPress sitesini, talep edilmeden kendi girişimimle çok dilli (TR/EN/RU) bir siteye ve içerik paneline dönüştüren yeniden tasarım demosu (müşteri işi değil); 301 + JSON-LD · [canlı demo](https://enorpa-eclectic-web.vercel.app) |
| [smart-second-brain-tr](https://github.com/acar32furkan-glitch/smart-second-brain-tr) | Smart Second Brain Obsidian eklentisinin Türkçe sürümü: arayüz yerelleştirmesi, en/tr i18n katmanı ve **ölçülebilir yerelleştirme kapısı** ([kurulabilir 2.3.1 sürümü](https://github.com/acar32furkan-glitch/smart-second-brain-tr/releases/tag/2.3.1)) — orijinal: [s2b-dev](https://github.com/s2b-dev/smart-second-brain), MIT |

Kodu özel olan canlı işler: Shopify mağaza operasyonu ve pazaryeri entegrasyonları (n11, Amazon.com.tr, Hepsiburada),
bir restoran için PHP/MySQL operasyon paneli, kişiye özel ürün satan bir e-ticaret sitesi (Next.js + Supabase).

## Nasıl çalıştığım

- **Deterministik ve kanıtlı:** her rakam bir kaynağa bağlanır (komut çıktısı, `dosya:satır`, API yanıtı).
  Ölçülemeyen şey "belirsiz" olarak işaretlenir — tahmin edilmez, uydurulmaz.
- **Salt-okunur ve ToS'a saygılı:** pazaryeri entegrasyonlarında yazma ucu yok; entegrasyonlar resmî
  API ve kullanıcı onayıyla çalışır.
- **CI kapısı:** ruff · `mypy --strict` · pytest + kapsam eşiği · çoklu Python matrisi. Yeşil olmayan iş yayınlanmaz.
- **AI destekli geliştirme:** spesifikasyonu, kabul testlerini ve incelemeyi ben yaparım; kodu yapay zekâ
  kodlama asistanlarıyla (ör. Claude Code) yazdırırım. Testlerin ve CI kapısının zorunlu olmasının sebebi budur.
- **Karar kaydı:** her projede `docs/adr/` (Python) veya `docs/DECISIONS.md` (TS) altında "ne yapıyoruz,
  neyi **yapmıyoruz** ve neden".

**Stack:** Python (FastAPI, pydantic, uv) · TypeScript (React/Next, Svelte) · PHP/MySQL · Shopify (Admin API, Liquid) ·
GitHub Actions · MCP · SQL/Supabase · Vercel

---

## English

Full-stack developer in Isparta, Türkiye (open to remote). I build and run small-business software — Shopify and
marketplace integrations (Trendyol, n11, Hepsiburada, Amazon.com.tr), a restaurant operations panel, client
websites — and publish tested open-source tooling for Turkish e-commerce. Everything below is MIT-licensed with CI.

- **[pazaryeri-denetci-mcp](https://github.com/acar32furkan-glitch/pazaryeri-denetci-mcp)** — audits a product catalogue against 17 deterministic rules and exposes it to AI assistants read-only via MCP · 286 tests · [live demo](https://pazaryeri-denetci-demo.vercel.app)
- **[trendyol-mcp](https://github.com/acar32furkan-glitch/trendyol-mcp)** — read-only MCP server that turns a seller's orders, returns, stock and reviews into a daily Turkish action report · 104 tests
- **[clause-cite](https://github.com/acar32furkan-glitch/clause-cite)** — CLI that extracts action items from contracts and tenders, each with a verbatim quote and line numbers (no network, no LLM) · 241 tests
- **[locale-gate](https://github.com/acar32furkan-glitch/locale-gate)** — deterministic TR↔EN translation quality gate for e-commerce text · 168 tests
- **[marketplace-sentinel](https://github.com/acar32furkan-glitch/marketplace-sentinel)** — watches stock/price mismatches for the same product across marketplaces and reports only what changed · 157 tests

I write the specs and acceptance tests and direct AI coding assistants; test and CI gates are mandatory for that reason.
Test counts come from the latest CI runs on `main` (17 Nov 2026).

**İletişim / Contact:** acar32furkan@gmail.com · [LinkedIn](https://www.linkedin.com/in/furkan-acar-dev)
