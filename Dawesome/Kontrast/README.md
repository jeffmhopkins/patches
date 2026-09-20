# Dawesome Kontrast

Patches for [Kontrast](https://www.dawesome.ch) by Dawesome (distributed by Tracktion).

Kontrast patches use the `.kontrast` extension. They are a single binary file
that embeds everything the patch needs — including wavetable data — so
individual files can run to several megabytes. There are no separate sample
dependencies to install.

## Patches

| Patch | Tags | Macros |
|---|---|---|
| [JMH_STRING_PAD](JMH_STRING_PAD) | pad, sustained, warm | SINGLE REED · WEIGHT · TIMBRE |

## Installing

The reliable, version-independent way is to import through the plugin itself:

1. Download the raw `.kontrast` file (use GitHub's **Download raw file** button,
   or clone the repo — don't "Save As" from the HTML page).
2. Open Kontrast and go to its preset browser.
3. Use the browser's import / load-from-file option and point it at the file.

Kontrast will place the patch in its own user-preset location and it will show
up in the browser under the patch name embedded in the file.

If you'd rather drop the file into the user-preset folder directly, use the
plugin's preset browser to reveal that folder on your system rather than
guessing at a path — the location differs between macOS and Windows and has
moved between Kontrast versions.

## Notes

- Patch files are binary. Don't open them in a text editor and re-save — it
  will corrupt them. This repo's `.gitattributes` marks them binary so Git
  won't normalize line endings in them either.
- The filename and the `PATCH_NAME` stored inside the file match. If you rename
  the file, the name shown in Kontrast's browser may not follow.
