# Fish Station

**An original monophonic subtractive bass synth for macOS — VST3 + CLAP, Apple Silicon.**

### ⬇︎ [Download the latest installer](https://github.com/jamcgrath/fish-station/releases/latest/download/Fish-Station.pkg)

Or grab it from the [Releases](https://github.com/jamcgrath/fish-station/releases) page.
The `.pkg` is signed with a Developer ID and notarized by Apple, so it installs with no Gatekeeper
warnings.

**Install:** open the `.pkg`, follow the installer (it drops the VST3 + CLAP into
`/Library/Audio/Plug-Ins`), then rescan plug-ins in your DAW and add **Fish Station** to a track.

**Requires:** macOS on Apple Silicon (arm64).

---

3 oscillators (saw/square + sub, detune, hard sync) → Moog-style ladder filter (12/24 dB, resonance
to self-oscillation) → amp VCA, with two ADSR envelopes, an LFO (free or tempo-synced), and an
arpeggiator. Resizable UI (100 / 150 / 200 %).

This repository hosts the download page and releases only; it is built from scratch in Rust and is
not a port or reverse-engineering of any existing product.
