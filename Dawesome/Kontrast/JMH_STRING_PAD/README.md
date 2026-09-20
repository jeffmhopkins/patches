# JMH_STRING_PAD

A warm, sustained string-style pad for **Dawesome Kontrast**.

| | |
|---|---|
| **Vendor** | Dawesome |
| **Plugin** | Kontrast |
| **Patch name** | `JMH_STRING_PAD` |
| **Author** | JEFFM (Jeff M. Hopkins) |
| **Tags** | `PAD` · `SUSTAINED` · `WARM` |
| **File** | [`JMH_STRING_PAD.kontrast`](JMH_STRING_PAD.kontrast) (9.1 MB) |
| **SHA-256** | `b260d70a5f5941f938a8858fa53c5f0eed7f682f8e0959d644ccae8db24ffba6` |

## Macros

The three macro controls are the intended way to play this patch:

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

[JMH Patches License 1.0](../../../LICENSE) — use it in your music freely,
commercial or not, no attribution required for your tracks.
