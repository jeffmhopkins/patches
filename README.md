# patches

Synthesizer and effect patches I've made, collected in one place so I can share them.

Everything in this repository is my own work — patches I built myself for the
plugins and instruments I use. Nothing here is a factory preset, a
repackaged commercial pack, or someone else's patch.

**License:** [JMH Patches License 1.0](LICENSE) — Creative Commons Attribution 4.0
as the base grant, plus a binding ethical-use condition. Use them in your music,
commercially or not, no attribution needed for your tracks. See
[Licensing](#licensing) below for the details.

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
a poor fit. The license here is [CC BY 4.0](LICENSE-CC-BY-4.0.txt) as its base
grant, with one addition: it is **not** granted to hate groups, or for use in
material made to promote violence, harassment, or discrimination. That
condition is in [Section 2 of the LICENSE](LICENSE).

What this means in practice:

- ✅ Use these patches in your music — released, sold, streamed, licensed, whatever. **No attribution needed for your tracks.**
- ✅ Modify them, build on them, make them your own.
- ✅ Redistribute them or a preset pack based on them — just credit me and link the license.
- ❌ Don't use them in or for hate propaganda, or redistribute them with the ethical condition stripped out.

Because Section 2 adds a condition, this is a **custom license, not a Creative
Commons license** — GitHub won't auto-detect it, and Creative Commons doesn't
endorse it. That's a deliberate tradeoff: a plain CC license can't carry a
restriction like this, since CC BY 4.0 forbids adding terms that limit the
rights it grants. If you need the unmodified CC BY 4.0 terms for a specific
reuse, open an issue and ask.

## Contributing

This is a personal collection of my own patches, so I'm not accepting patch
submissions. Issues and corrections are welcome — bad file, wrong install
path, a patch that won't load, a typo.
