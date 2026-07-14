# Application Submission

FM Radio for Flipper Zero. Controls TEA5767 and Si4703 FM tuner boards over I2C with automatic chip detection, seek/fine tuning, volume control (Si4703), and editable station preset files on the SD card. See `.catalog/CHANGELOG.md` in the source repo for what changed in this version.

# Extra Requirements

- Requires an external FM tuner board: TEA5767 or Si4703, wired to the I2C pins (Si4703 additionally uses A4 for RST).

# Author Checklist (Fill this out)

- [x] I've read the [contribution guidelines](../blob/HEAD/documentation/Contributing.md) and my PR follows them
- [x] I own the code I'm submitting or have code owner's permission to submit it
- [x] I have performed a self-review of my own code
- [x] I have commented my code, particularly in hard-to-understand areas
- [x] I [have validated](../blob/HEAD/documentation/Contributing.md#validating-manifest) the manifest file(s) with `python3 tools/bundle.py --nolint applications/CATEGORY/APPID/manifest.yml bundle.zip`

# AI usage disclosure (Fill this out):

- [x] Partially AI assisted (clarify below which code was AI assisted and briefly explain what it does).
- [ ] Fully AI generated (explain what all the generated code does in moderate detail).

- AI assistance was used for portions of the app code and for preparing/validating this catalog manifest and submission. The app tunes TEA5767/Si4703 FM radio chips over I2C and manages station presets on the SD card.
