# Profile artwork

Banners and project cards for the bilingual GitHub profile, added 2026-10-03.

- AIOS icon: reused from [apps/demo/public/favicon.svg](https://github.com/jonghyun0000/aios/blob/main/apps/demo/public/favicon.svg).
- JH CUT Studio icon: reused from [Resources/Brand/JHCutStudio-icon-master.png](https://github.com/jonghyun0000/JHCutStudio/blob/main/Resources/Brand/JHCutStudio-icon-master.png).
- Chuncheon Gwating icon: reused from [public/icons/icon-512.png](https://github.com/jonghyun0000/chuncheon-dating5.0/blob/main/public/icons/icon-512.png).
- Poseidon wave symbol: new vector artwork made for this profile. It does not change the app icon in the Poseidon project.
- Banner layout and project illustrations: original vector layout for this profile. PNGs keep the typography consistent across GitHub themes and operating systems.

Korean and English assets share the same layout. The surrounding README retains text descriptions, source links, and expandable implementation details.

## Link buttons

Updated 2026-10-03. The `btn-*` images replace the earlier 48px `button-*` images.

- Display size 28px high, rendered at 2x. Light and dark versions are switched with `<picture>` and `prefers-color-scheme`.
- Icons: [Lucide](https://lucide.dev) `arrow-up-right` (try it), `code` (source), `terminal` (run locally). ISC License.
- Typeface: [Pretendard](https://github.com/orioncactus/pretendard) SemiBold, SIL Open Font License 1.1.

## Dark card variants

Added 2026-10-03. `aios-*-dark.png` and `chuncheon-*-dark.png` are shown on GitHub's dark theme through `<picture>` and `prefers-color-scheme`. They were derived from the light cards by inverting lightness in the Lab color space while keeping hue, so typography and layout match the originals. The Chuncheon Gwating app icon keeps its original pixels. JH CUT Studio and Project Poseidon are already dark and have no separate variant.
