# Grzegorz Otto

**Systems engineer · builds the tools he builds with.** I build [Flare Engine](https://github.com/grzott/flare-engine), an open-source 2D engine that runs the same TypeScript on Web (CanvasKit) and React Native (Skia), for high-performance animation, gamification, and interactive UI.

> I build engines that respect the frame budget.

Lead developer of Poland's national public-broadcaster mobile app from 2020 to 2026, built end-to-end in React Native + Expo. I work with an AI-directed agent workflow: coding agents implement against written contracts and cannot commit, and I own the architecture, the decisions, the gates and the review. I write about cross-platform Skia rendering, data-oriented engine design, and that workflow.

---

## Now / Next

- **Now** - Flare Engine is open source. The [repository](https://github.com/grzott/flare-engine) has been public under Apache-2.0 since 2026-10-26, and all 42 `@flare-engine/*` packages are public on npm at `0.4.5`, published from GitHub Actions with npm provenance. Start with `npm create @flare-engine my-game`.
- **Now** - Pan Tvardowski, Flare's showcase shmup: 2,522 passing tests, content-complete at `0.0.1`, not yet on the app stores. (Measured 2026-08-30 at PT `ca5860f`.)
- **Next** - B2B projects from January 2027. Flare news: [flareengine.dev](https://flareengine.dev), [releases](https://github.com/grzott/flare-engine/releases).
  
---

## Selected work

**[Flare](https://flareengine.dev)** - modular 2D engine in TypeScript for Web (CanvasKit) + React Native (Skia). An ECS with bitmask queries and zero-allocation hot paths; tree-shakeable `@flare-engine/*` packages on a strict downward-only dependency graph. Benchmarked on real Android devices - Galaxy A55, Pixel 6 and Pixel 10, every scenario inside the 60 fps frame budget (device matrix captured 2026-05-26). Apache-2.0, [public since October 2026](https://github.com/grzott/flare-engine).

**Pan Tvardowski** - a Polish-folklore vertical shoot-'em-up and Flare's hardest stress-test, localized EN/PL and built entirely on `@flare-engine/*`. Its own repository, 2,522 tests across 305 files (measured 2026-08-30 at `ca5860f`). PolyForm Noncommercial; not yet on the app stores.

**Polskie Radio** (production, 2020-2026) - Poland's national public-broadcaster app. Clean Architecture, a command-driven playback state machine, and custom Expo native modules (Swift + Kotlin) for CarPlay, Android Auto, lock-screen, and Chromecast; the app family re-architected into a shared Turborepo monorepo.

Flare Engine is public; the rest of this work lives in private repositories. [grzegorzotto.dev](https://grzegorzotto.dev) carries the full case studies (problem to approach to architecture to result).

---

## Writing

Cross-platform Skia rendering, data-oriented engine design, and AI-directed engineering, at [grzegorzotto.dev/blog](https://grzegorzotto.dev/blog):

- [Skia Atlas in React Native: batching 2,000 sprites into one draw call per texture](https://grzegorzotto.dev/blog/skia-atlas-2000-sprites-react-native)
- [Archetype ECS in TypeScript: why I didn't use bitECS or miniplex](https://grzegorzotto.dev/blog/archetype-ecs-typescript)
- [40 packages, 1 dev: Turborepo + Bun + Biome monorepo stack](https://grzegorzotto.dev/blog/turborepo-bun-biome-40-package-monorepo)

---

## Stack

- **Languages** - TypeScript (strict) · Swift · Kotlin · C++ · Go
- **Mobile** - React Native (0.66 → 0.81, New Architecture / Fabric) · Expo · React Native Skia · Reanimated
- **Systems** - ECS · zero-allocation hot loops · state machines · command bus · Clean / Hexagonal architecture
- **Tooling** - Bun · Turborepo · Biome · GitLab CI + Fastlane · Sentry

---

## Elsewhere

- Portfolio - [grzegorzotto.dev](https://grzegorzotto.dev)
- Flare - [flareengine.dev](https://flareengine.dev) · [source](https://github.com/grzott/flare-engine)
- LinkedIn - [in/grzegorz-otto](https://linkedin.com/in/grzegorz-otto)
- Email - [grzott@gmail.com](mailto:grzott@gmail.com)

B2B projects from January 2027; open to collaboration and advisory work.
