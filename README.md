<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=180&color=0:0B1021,45:2563EB,100:7C3AED&text=SG%20Core%20Mods&fontColor=ffffff&fontAlignY=35&fontSize=36&desc=The%205-mod%20Sturmgrenadier%20server%20stack%20for%20Space%20Engineers&descAlignY=57&descSize=15" />
</p>

<p align="center">
  <a href="https://sghq.org/"><img src="https://img.shields.io/badge/Sturmgrenadier-server%20community-1F2937?style=for-the-badge" alt="SG HQ" /></a>
  <a href="https://github.com/gitpush-mod/se-sg-core-mods/issues/new?template=bug_report.md&labels=bug"><img src="https://img.shields.io/badge/Report%20a%20bug-red?style=for-the-badge&logo=github&logoColor=white" alt="Report a bug" /></a>
  <img src="https://img.shields.io/badge/Space%20Engineers-1-0EA5E9?style=for-the-badge" alt="SE1" />
  <img src="https://img.shields.io/badge/5%20mods%20bundled-checkmark-10B981?style=for-the-badge" alt="5 mods" />
</p>

> **"The stack that makes an SG server feel like an SG server."**

Bundle repo for the **Sturmgrenadier (SG) Core** mod family — five coordinated Space Engineers mods that together define the SG server experience. Each mod is standalone-usable on Steam Workshop, but they're designed and maintained as a set.

## 🧩 The five mods

| Mod | Subfolder | Steam Workshop |
|---|---|---|
| **SG Core Mod** — foundation blocks + tweaks | [`Sturmgrenadier Core Mod/`](./Sturmgrenadier%20Core%20Mod) | [2799678177](https://steamcommunity.com/sharedfiles/filedetails/?id=2799678177) |
| **SG Core Power** — power generation + storage rework | [`Sturmgrenadier Core Power/`](./Sturmgrenadier%20Core%20Power) | [3362282194](https://steamcommunity.com/sharedfiles/filedetails/?id=3362282194) |
| **SG Core Production** — refining + assembly rework | [`Sturmgrenadier Core Production/`](./Sturmgrenadier%20Core%20Production) | [3369236046](https://steamcommunity.com/sharedfiles/filedetails/?id=3369236046) |
| **SG Core Survival** — survival-loop mechanics | [`Sturmgrenadier Core Survival/`](./Sturmgrenadier%20Core%20Survival) | [3361326081](https://steamcommunity.com/sharedfiles/filedetails/?id=3361326081) |
| **SG Core Vanilla Combat** — combat balance tweaks | [`Sturmgrenadier Core Vanilla Combat/`](./Sturmgrenadier%20Core%20Vanilla%20Combat) | [3364273324](https://steamcommunity.com/sharedfiles/filedetails/?id=3364273324) |

Each subfolder is a fully self-contained mod (its own `modinfo.sbmi`, `thumb`, `Data/`, and Steam Workshop item).

## 🚀 Install

**As a full stack:** subscribe to all five on Steam Workshop, enable in load order (Core Mod first).

**Individually:** each Workshop item can be subscribed and used on its own, but they're tuned to work together and playing with only one may feel unbalanced.

## ⚠️ Server operators — critical

- **Never upload the repo's `Sandbox` files to a live SG server.** The live server auto-pulls dependencies at runtime; overwriting Sandbox files from the repo will wipe those pulls and **crash the server**. Use the pull-from-live workflow when syncing.
- See the `AGENTS.md` in this repo for the full server-safety protocol.

## 🎯 Compatibility

- ✅ **Space Engineers 1** — actively maintained by the SG community + Chris
- ✅ **Multiplayer + dedicated servers** — this is what SG runs on
- ⚠️ **Mod load order matters** — Core Mod first, then the specialized ones
- ⚠️ **May conflict with other block-adjustment mods** — SG Core covers a lot of ground

## 🐛 Found a bug?

- **[Open an issue with the bug template](https://github.com/gitpush-mod/se-sg-core-mods/issues/new?template=bug_report.md&labels=bug)** — mention which of the five mods it involves
- **Comment on the specific Workshop page** for quick feedback

## 🙌 Credits

- **Author + maintainer:** [Chris Carpenter (Godimas101)](https://github.com/Godimas101)
- **Community:** [Sturmgrenadier Hosting](https://sghq.org/) — the SE server the stack runs on
- **Companion mods (not bundled, tuned to work with SG Core):** [NJFL](https://github.com/gitpush-mod/se-not-just-for-looks), [Mod Adjuster Mods](https://github.com/gitpush-mod/se-mod-adjuster-mods)

## 🧡 Support

Free and always will be. **Patreon** for the ongoing project log.

[![Support on Patreon](https://raw.githubusercontent.com/Godimas101/personal-projects/main/patreon/images/buttons/patreon-medium.png)](https://patreon.com/Godimas101)

---

*Part of the [`gitpush-mod`](https://github.com/gitpush-mod) mod collection. Made with ♥ (and a lot of coffee) by Godimas + Claude.*
