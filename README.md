# 絲 A Selyemút Négy Szála

**Élő oldal:** [selyemut-negy-szala.htgitacc.workers.dev](https://selyemut-negy-szala.htgitacc.workers.dev)

Egy magyar Taijiquan-, Qigong- és Daoista közösség hobbiprojektje: kínai kulturális
tudástár, amely négy szálon — **Tea, Kardok, Öltözködés, Kalligráfia** — követi
végig hét történelmi korszakot a Shang-dinasztiától napjainkig, mindig elválasztva
a dokumentált történelmet a szájhagyománytól.

> 🚧 **Az oldal folyamatosan bővül** — új korszakok, képek és tartalmi finomítások
> rendszeresen kerülnek fel.
>
> 🤖 A tartalom kutatása, szerkesztése és a kód nagy része **AI-asszisztált munka**
> (Claude Code), emberi kurátori felügyelettel — minden forrás és legenda jelölve,
> forráskritikával kezelve.

Ez a repó egy rövid bemutató a projektről; a tényleges forráskód más helyen él.

## Screenshotok

<!-- Húzd be ide a képeket a GitHub szerkesztőben, pl.:
![Főoldal](screenshots/home.png)
![Tea szál — Tang-kor](screenshots/tea-tang.png)
![Kardok szál — sötét mód](screenshots/kardok-dark.png)
-->
*(hamarosan)*

## Miről szól

- **Négy szál, hét korszak** — Shang-Zhou, Qin-Han, Wei-Jin, Tang, Song, Ming, Qing
  és egy modern (1912–napjainkig) kiegészítés, mind a négy szálon végigvezetve.
- **Réteges tartalom** — rövid összefoglaló mindenkinek, kinyitható „Mélyebbre"
  rész a gyakorlóknak.
- **Forráskritika mindenhol** — minden legenda és állítás jelölve: dokumentált
  tény, dokumentált kultusz, vagy szájhagyomány-eredetű legenda.
- **Alapfogalom-oldalak** — Három Tanítás, Daoista Panteon, WuJi → BaGua elméleti
  lánc — saját kutatással, közgyűjteményi/közkincs képanyaggal illusztrálva.
- **i18n-kész** — magyar a gyökéren, angol előkészítve.
- **Világos/sötét téma** — kézzel kapcsolható, `prefers-color-scheme` alapú
  alapértelmezéssel.

## Tech stack

- **[Astro 5](https://astro.build)** — content collections, i18n routing
- **[Cloudflare Workers](https://workers.cloudflare.com)** — hosting, SSR adapter
- **[Decap CMS](https://decapcms.org)** — Git-alapú szerkesztőfelület
- **Markdown + Zod séma** — strukturált frontmatter minden cikkhez
