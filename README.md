# iPhone Duo skills for Capacitor and Ionic

Agent skills for adapting **Capacitor** apps to iPhone Duo and Android foldables: laying out around the crease, reading the hinge angle and posture, window size classes, the Device Posture and Viewport Segments polyfill, the outer display, and moving an Ionic tab bar to the edge iOS puts native bars on.

The other iPhone Duo skills cover SwiftUI, UIKit and AVFoundation. This one covers the web view: Capacitor, Ionic, Angular, React and Vue.

Works with Claude Code, and with any agent that reads `SKILL.md` files.

## Install

```bash
npx skills add erkamyaman/iphone-duo-capacitor-skills@capacitor-foldable
```

Or copy `skills/capacitor-foldable` into your project's skills directory.

## What it covers

| Reference | What it answers |
| --- | --- |
| [`SKILL.md`](skills/capacitor-foldable/SKILL.md) | Install, the API at a glance, which platform reports what |
| [`css-layout.md`](skills/capacitor-foldable/references/css-layout.md) | Keeping content out of the crease with `--fold-*`, two-pane layouts, safe areas |
| [`api.md`](skills/capacitor-foldable/references/api.md) | Every method and event, and what each platform actually returns |
| [`ionic.md`](skills/capacitor-foldable/references/ionic.md) | Ionic specifics, including the vertical tab bar |
| [`iphone-duo.md`](skills/capacitor-foldable/references/iphone-duo.md) | Measured geometry, vertical bars, the keyboard, what iOS reports when |
| [`android.md`](skills/capacitor-foldable/references/android.md) | `androidx.window`, rear display, dual screen |
| [`testing.md`](skills/capacitor-foldable/references/testing.md) | The iPhone Duo simulator and Android foldable emulators |

## Status

Beta. Everything was checked against the plugin source and measured on the iPhone Duo simulator, not on hardware, since the device ships on 23 October 2026. [Report anything that misleads you.](https://github.com/erkamyaman/capacitor-foldable/issues)

The skill documents [`@erkamyaman/capacitor-foldable`](https://github.com/erkamyaman/capacitor-foldable), which is what supplies the fold state to a Capacitor web view.

## Licence

MIT.
