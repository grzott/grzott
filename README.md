# Grzegorz Otto

**Senior React Native engineer and mobile tech lead.** I build Flare - a cross-platform 2D engine that runs the same TypeScript on Web (CanvasKit) and React Native (Skia), for high-performance animation, gamification, and interactive UI.

> I build engines that respect the frame budget.

Sole architect and lead of Poland's national public-broadcaster mobile app (150k+ downloads, 99.9% crash-free), built end-to-end in React Native + Expo. I work solo with AI-directed agent infrastructure, shipping monorepo-scale output at team velocity. I write about cross-platform Skia rendering, data-oriented engine design, and the workflow that makes solo monorepo development possible.

---

## Now / Next

- **Now** - Flare `0.2.1`: 40 `@flare-engine/*` packages, 2,288 passing tests (measured 2026-07-04), a strict 7-tier dependency graph with zero circular dependencies. Private beta on restricted npm, not yet publicly installable.
- **Now** - Pan Tvardowski, Flare's showcase shmup: 2,048 tests, content-complete at 0.1.x, not yet on the app stores.
- **Next** - public open-source launch under Apache-2.0, targeted October 2026. Follow it at [flareengine.dev](https://flareengine.dev).

---

## Selected work

**[Flare](https://flareengine.dev)** - modular 2D engine in TypeScript for Web (CanvasKit) + React Native (Skia). Hybrid archetype ECS with bitmask queries and zero-allocation hot paths; 40 tree-shakeable packages on a strict downward-only dependency graph. Benchmarked on real Android devices (Galaxy A54/A55, Pixel 6/10) at 60 fps inside a 16 ms budget on mid-tier Android (A54, release build). Apache-2.0 at the October 2026 public launch.

**Pan Tvardowski** - a Polish-folklore vertical shoot-'em-up and Flare's hardest stress-test, localized EN/PL and built entirely on `@flare-engine/*`. Its own repository, 2,048 tests across 266 files. PolyForm Noncommercial; not yet on the app stores.

**Polskie Radio** (production) - Poland's national public-broadcaster app. Clean Architecture, a command-driven playback state machine, and custom Expo native modules (Swift + Kotlin) for CarPlay, Android Auto, lock-screen, and Chromecast; the app family re-architected into a shared Turborepo monorepo.

Most of this work lives in private repositories until Flare's launch. [grzegorzotto.dev](https://grzegorzotto.dev) carries the full case studies (problem to approach to architecture to result).

---

## Writing

Cross-platform Skia rendering, data-oriented engine design, and AI-directed engineering, at [grzegorzotto.dev/blog](https://grzegorzotto.dev/blog):

- [Skia Atlas in React Native: batching 2,000 sprites into one draw call per texture](https://grzegorzotto.dev/blog/skia-atlas-2000-sprites-react-native)
- [Archetype ECS in TypeScript: why I didn't use bitECS or miniplex](https://grzegorzotto.dev/blog/archetype-ecs-typescript)
- [40 packages, 1 dev: Turborepo + Bun + Biome monorepo stack](https://grzegorzotto.dev/blog/turborepo-bun-biome-40-package-monorepo)

---

## Stack

- **Languages** - TypeScript (strict) · Swift · Kotlin · C++
- **Mobile** - React Native (0.66 → 0.81, New Architecture / Fabric) · Expo · React Native Skia · Reanimated
- **Systems** - archetype ECS · zero-allocation hot loops · state machines · command bus · Clean / Hexagonal architecture
- **Tooling** - Bun · Turborepo · Biome · GitLab CI + Fastlane · Sentry

---

## Elsewhere

- Portfolio - [grzegorzotto.dev](https://grzegorzotto.dev)
- Flare - [flareengine.dev](https://flareengine.dev)
- LinkedIn - [in/grzegorz-otto](https://linkedin.com/in/grzegorz-otto)
- Email - [grzott@gmail.com](mailto:grzott@gmail.com)

Open to freelance, collaboration, and advisory work.

<!--
  Optional single stats card. It renders on the profile as an external image
  (proxied through GitHub's camo cache), so uncommenting WILL make it appear.
  Caveat: nearly all of your work is in private repos, so this understates you -
  weigh omitting it (senior restraint reads better than a weak number). If you
  keep it, enable "Include private contributions" in profile settings.

  ![GitHub stats](https://github-readme-stats.vercel.app/api?username=grzott&show_icons=true&hide_border=true&count_private=true&theme=transparent)
-->
