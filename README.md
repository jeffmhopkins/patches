# patches

Synthesizer and effect patches I've made, collected in one place so I can share them.

Everything in this repository is my own work — patches I built myself for the
plugins and instruments I use. Nothing here is a factory preset, a
repackaged commercial pack, or someone else's patch.

Copyright © 2026 Jeff M. Hopkins. **Licensed under
[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).** Use them in your
music, commercially or not — no attribution needed for your tracks. See
[Licensing](#licensing) below.

---

## Layout

Patches are organized by **vendor → plugin → patch**:

```
<Vendor>/<Plugin>/<PATCH_NAME>/
├── <PATCH_NAME>.<ext>     # the patch file itself
├── README.md              # what it is, how it's built, how to load it
└── (optional) demo.flac, screenshot.png, notes.md
```

Each patch gets its own folder so there's somewhere to put a description,
a screenshot of the patch, and a short audio demo alongside the file.

Vendor and plugin folders use the name as the maker brands it (`Dawesome`,
`Kontrast`). Patch folders use the patch name exactly as it appears inside the
plugin, so the folder always matches what you'll see in the browser.

## Contents

| Vendor | Plugin | Patch | Tags |
|---|---|---|---|
| [Dawesome](Dawesome) | [Kontrast](Dawesome/Kontrast) | [JMH_STRING_PAD](Dawesome/Kontrast/JMH_STRING_PAD) | pad, sustained, warm |

## Installing a patch

Copy the patch file into the plugin's user-preset folder. The exact path
varies by plugin — each plugin folder has a README with its specific location.

Two general notes:

- **Download the raw file, not the GitHub HTML page.** Use the "Download raw
  file" button on the file's page, or clone the repo. Right-click → Save As on
  a GitHub page will give you a broken preset.
- **Don't rename the file** unless you also expect the name to change in the
  plugin's browser. Some plugins key off the filename, others off a name
  embedded in the file, and a few off both.

## Licensing

These are creative works, not source code, so an MIT/GPL-style license would be
a poor fit. They're released under the
[Creative Commons Attribution 4.0 International license](LICENSE) (CC BY 4.0) —
the standard choice for shared preset packs.

- ✅ Use these patches in your music — released, sold, streamed, licensed, whatever. **No attribution needed for your tracks.**
- ✅ Modify them, build on them, make them your own.
- ✅ Redistribute them, or a preset pack based on them — just credit me and link the license.

Attribution is only required when you redistribute **the patches themselves**
(or modified versions of them) as patches. A track you made using one isn't a
redistribution of the patch, so it needs no credit.

To credit a redistribution:

> Patches by Jeff M. Hopkins — https://github.com/jeffmhopkins/patches — licensed under CC BY 4.0

One request, which is *not* a license term and not legally binding: please
don't use these in material made to promote hate, violence, or harassment.
CC BY 4.0 doesn't permit adding that as an actual restriction, so it's asked
rather than enforced.

## Contributing

This is a personal collection of my own patches, so I'm not accepting patch
submissions. Issues and corrections are welcome — bad file, wrong install
path, a patch that won't load, a typo.
