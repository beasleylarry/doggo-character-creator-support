# Doggo Character Creator — Support

Public help and bug reports for **Doggo Character Creator**, a ChatGPT and Codex workflow by **Larry R. Beasley** for creating character packs for Tha Doggos Big Adventure.

## Get help

[Open a support issue](https://github.com/beasleylarry/doggo-character-creator-support/issues/new/choose) or [browse existing reports](https://github.com/beasleylarry/doggo-character-creator-support/issues).

For a useful report, include the plugin version, the step that failed, exact error text, your app/browser, and a small non-sensitive example if needed. **Issues and attachments are public.** Do not post passwords, API keys, personal contact details, private photos, or unrelated files. Redact screenshots before attaching them.

## Common fixes

- Extract the generated ZIP before importing. Select the JSON manifest and all four PNG files together in a compatible playground.
- Schema version 1 uses idle, run, jump, and bark. Idle/jump/bark are 512 × 448 PNGs; run is six frames across in a 3072 × 448 PNG.
- Use real alpha transparency. A painted checkerboard does not count as a transparent background.
- Technical checks cannot prove likeness, animation quality, or acceptance in every game level. Inspect the previews and test movement, jumping, and barking.
- Image-generation access and limits come from your ChatGPT or Codex account. This project does not run a separate image-generation service.

The plugin creates and checks artwork; it does not publish characters, grant game-account access, take payments, or unlock paid content. The plugin's public-directory submission is still being prepared.

## Privacy and scope

This repository contains support documentation only, not the game's source code. The skills-only plugin has no developer-run endpoint receiving photos, generated packs, or telemetry. If you choose to post a support report here, GitHub and the repository maintainer receive what you include, and it is public. Edit personal information out of a report and ask the maintainer for help with removal if needed.

OpenAI account, subscription, and platform-access questions belong with OpenAI support.
