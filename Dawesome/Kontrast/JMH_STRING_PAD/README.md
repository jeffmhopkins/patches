# JMH_STRING_PAD

A warm, sustained **MPE string patch** for **Dawesome Kontrast**, built and
played on the **LinnStrument**.

| | |
|---|---|
| **Vendor** | Dawesome |
| **Plugin** | Kontrast |
| **Patch name** | `JMH_STRING_PAD` |
| **Author** | JEFFM (Jeff M. Hopkins) |
| **Tags** | `PAD` · `SUSTAINED` · `WARM` |
| **Expression** | MPE — built for the LinnStrument |
| **File** | [`JMH_STRING_PAD.kontrast`](JMH_STRING_PAD.kontrast) (9.1 MB) |
| **SHA-256** | `b260d70a5f5941f938a8858fa53c5f0eed7f682f8e0959d644ccae8db24ffba6` |

## Hear it

[![SJ-084 - Linnstrument + Kontrast - Harmonic Minor 12 of 19 TET](https://i.ytimg.com/vi/C7RwmxHXH4w/hqdefault.jpg)](https://www.youtube.com/watch?v=C7RwmxHXH4w)

**[SJ-084 — Linnstrument + Kontrast — Harmonic Minor 12 of 19 TET](https://www.youtube.com/watch?v=C7RwmxHXH4w)**

This patch played from a LinnStrument, in harmonic minor tuned to 12 notes of
19-TET.

## Playing it

This is an MPE patch. It's written to be played expressively from an MPE
controller — a LinnStrument in my case — so per-note expression is doing a lot
of the work you hear in the demo.

You'll want an MPE-capable setup to get the most out of it:

- Run Kontrast in a host with MPE enabled, or standalone with an MPE controller
  connected.
- On a non-MPE keyboard the patch still plays, but it will sit much flatter.
  Drive the three macros by hand to make up for the expression you're missing.

## Macros

The three macro controls are the other half of the performance:

1. **SINGLE REED**
2. **WEIGHT**
3. **TIMBRE**

Each macro runs through its own modulation curve and amount stage, so the
response is shaped per-destination rather than mapped linearly.

## Under the hood

- **EQ** block in the first FX slot
- **Clouds** granular FX
- Three macro modulation chains (curve + amount per macro)
- Embeds its own wavetable data — this is why the file is ~9 MB. Nothing
  external to install.

## Installing

See the [Kontrast install notes](../README.md#installing). Short version:
download the raw file, then import it through Kontrast's own preset browser.

## License

[CC BY 4.0](../../../LICENSE) — use it in your music freely, commercial or
not, no attribution required for your tracks.
