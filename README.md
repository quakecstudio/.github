# quakecstudio/.github

Organization-wide files for [QuakeC Studio](https://www.quakecstudio.com).

- `profile/README.md`: the profile shown on [github.com/quakecstudio](https://github.com/quakecstudio).
- Default community health files, used by every repository that doesn't have its own: `CODE_OF_CONDUCT.md`, `CONTRIBUTING.md`, `SECURITY.md`, `SUPPORT.md`, `ISSUE_TEMPLATE/` and `PULL_REQUEST_TEMPLATE.md`.
- `brand/`: the logo and the images uploaded to GitHub by hand.

## Brand assets

| File | Use |
| --- | --- |
| `brand/logo.svg` | The logo, transparent background. |
| `brand/favicon.svg` | Simplified mark for 16–64 px. |
| `brand/apple-touch-icon.png` | 180×180 home-screen icon. |
| `brand/avatar.png` | 500×500 organization avatar. |
| `brand/social/<repo>.jpg` | 1280×640 social preview for each repository. |

GitHub's API can't set the organization avatar or a repository's social
preview, so upload them by hand:

- Avatar: organization **Settings → Profile picture**, `brand/avatar.png`.
- Social preview: each repository's **Settings → General → Social preview**,
  `brand/social/<repo>.jpg` (`dot-github.jpg` for this one).

The palette matches the site: ember `#ff8a1f`, gold `#e3b65a`, rust
`#a8461a` and text `#d8c8a8` on `#0b0907`. Text uses Silkscreen and VT323
(SIL Open Font License 1.1).
