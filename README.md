# Audacy

API Evangelist profile of **Audacy, Inc.**, the U.S. multi-platform audio and entertainment company that operates the country's second-largest radio group alongside the Audacy streaming app, a major podcast network, and the Amperwave audio ad-tech platform.

- Corporate site: https://www.audacyinc.com
- Consumer hub: https://www.audacy.com
- Ad-tech platform: https://amperwave.com

## Organization

Audacy, Inc. — formerly **Entercom Communications Corporation**, rebranded to Audacy on March 30, 2021 — is headquartered in New York City and is led by President and CEO **Kelli Turner**.

| Metric | Value |
|---|---|
| Radio brands | 230+ |
| Media markets | 47 |
| Monthly listeners (total) | 200 million+ |
| Monthly digital audio listeners | 60 million |
| Monthly podcast listeners | 44 million |
| Annual podcast downloads | ~2 billion |
| Employees | 4,000+ |

### Executive team

- **Kelli Turner** — President and CEO
- **Chris Oliviero** — Chief Business Officer
- **Rick Rosenthal** — Chief Financial Officer
- **Steve Rollins** — Chief Information Officer
- **Michael Dash** — EVP, Chief Legal Officer, Secretary
- **Jenny Nelson** — Chief Marketing Officer
- **Bob Phillips** — Chief Revenue Officer
- **Jeff Sottolano** — Chief Programming Officer
- **Elizabeth Bramowski** — Chief Accounting Officer & Controller

## Post-bankruptcy status

| Event | Date | Detail |
|---|---|---|
| Rebrand from Entercom | 2021-03-30 | Entercom Communications becomes Audacy |
| Chapter 11 filing | 2024-01-07 | Prepackaged Chapter 11 to address debt load |
| Emergence | 2024-09-30 | Privately held; Soros Fund Management holds controlling interest |
| Debt equitized | — | ~$1.6 billion of funded debt converted to equity |
| Net debt reduction | — | From ~$1.9 billion to ~$350 million (~80% reduction) |

Audacy is now a **privately held company** following its September 30, 2024 emergence from Chapter 11.

## Surfaces profiled

This repo profiles the consumer, content, broadcaster, and advertiser surfaces of Audacy. None of these surfaces expose a public developer API; all integration is sales-led or via partner programmatic platforms.

### 1. Audacy Streaming App
- Live radio, podcasts, sports play-by-play, exclusive stations
- iOS, Android, web, connected devices
- https://www.audacy.com

### 2. Audacy Podcast Network
- ~2 billion annual downloads, 44 million monthly listeners
- Flagship shows: *Office Ladies*, *The Moth*, *The Draymond Green Show*, *The Late Show Pod*, *How We Made Your Mother*
- Eight genres: Lifestyle, True Crime, Entertainment & Celebrity, Society & Culture, History, Sports, Comedy, News/Business/Finance
- Distributed via Apple Podcasts, Spotify, Audacy app, per-show RSS
- https://www.audacyinc.com/podcasts

### 3. Amperwave (ad-tech and audio distribution)
- Cloud-based hosting, streaming distribution, dynamic ad insertion
- Three products: **Amperwave Streaming**, **Amperwave Podcasting**, **Ad Decisioning Engine**
- Nielsen-compatible simulcasting, frequency capping, real-time analytics
- Sold to third-party broadcasters outside Audacy itself
- https://amperwave.com

### 4. Audacy Advertising Solutions
- Direct, branded, and programmatic ad sales across broadcast, streaming, podcasts, events
- Amazon DSP programmatic partnership
- https://www.audacyinc.com/advertise

### 5. Audacy Radio Stations Network
- ~230 brands across 47 markets
- News, sports, talk, music formats
- https://www.audacy.com/stations

## Owned content and ad-tech brands

| Brand | Function |
|---|---|
| **Cadence13** | Premium podcast studio |
| **Pineapple Street Studios** | Narrative podcast studio |
| **Podcorn** | Influencer-creator podcast marketplace |
| **BetMGM Network** (formerly BetQL) | Sports-betting audio network |
| **2400Sports** | Sports content production studio |
| **Audacy Creator Lab** | Internal creator and branded-content arm |
| **Amperwave** | Third-party audio hosting and ad-tech |

## Partners

- **Sonos Radio** — exclusive U.S. sales and distribution partnership
- **Amazon DSP** — programmatic audio advertising
- **Podscribe** — podcast attribution measurement
- **MOGL** — NIL (college athlete) brand partnerships

## Developer surface

Audacy publishes **no public developer API, OpenAPI definition, AsyncAPI, JSON Schema, SDK, or CLI**. The `github.com/audacy` organization exists but holds **no public repositories** (and points to an unrelated Paris-based organization, not Audacy, Inc.).

Programmatic integration with Audacy is brokered through:
- Partner ad-tech platforms (Amazon DSP, Adswizz-style programmatic exchanges)
- The Amperwave platform (sales-led integration for broadcasters)
- Standard per-show podcast RSS feeds for content syndication

As a result, this repo intentionally does **not** ship `openapi/`, `asyncapi/`, `json-schema/`, `capabilities/`, `rules/`, or `examples/` directories — there is no public spec material to back them.

## Files in this repo

- [`apis.yml`](apis.yml) — full APIs.json-style index of Audacy's organization, surfaces, leadership, owned brands, partners, and post-bankruptcy posture
- [`README.md`](README.md) — this file

## API Evangelist tier

- **x-type:** company
- **x-tier:** 3
- **x-tier-reason:** no-apis — Audacy is a large, post-bankruptcy media company with no public developer-facing APIs. The profile is organizational and structural.
