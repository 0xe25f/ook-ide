# Ook!++ IDE

[![GitHub Repo stars](https://img.shields.io/github/stars/0xe25f/ook-ide?style=social)](https://github.com/0xe25f/ook-ide)

<p>
  <kbd>Offline Ready</kbd>
  <kbd>Single-file HTML</kbd>
  <kbd>No CDN</kbd>
  <kbd>No Server</kbd>
  <kbd>Embedded Assets</kbd>
  <kbd>MIT Licensed</kbd>
</p>

**Do androids dream of orangutans?**

Ook!++ IDE is a single-file, offline, no-server programming playground for Ook!++: a friendly helper dialect that can be interpreted directly, suggested, prettified, debugged, and compiled back into original Ook!, Bf*, JavaScript, or Dragon Palm assembly/cart output.

If this project made you smile, taught you something odd, or helped you make a tiny programme, please star it. Stars are small, harmless, and surprisingly motivational.

* GitHub Repository: [0xe25f/ook-ide](https://github.com/0xe25f/ook-ide)

## Features

- All-in-one `ook-ide.html`: no CDN, no build step, no server, and no external assets required.
- Modern responsive IDE inspired by VS Code and JetBrains, with movable panels and saved layout preferences.
- Hot-swappable English, German, and Spanish interface.
- Dark, light, and automatic colour themes.
- Page font and editor text-size preferences.
- Prettified, coloured Ook!++ editor with line numbers and red-dot breakpoints.
- Suggest button beside Prettify, with deterministic suggestions enabled by default.
- Deterministic suggestions can creatively repair or improve local code without an LLM: helper typos, missing prefixes, raw text, `console.log(...)`, raw Bf*, unquoted `say`, missing output, and unmatched loops.
- Optional OpenAI-compatible LLM suggestion service settings in Preferences, with endpoint, model, secret key, and an accordion-hidden system prompt.
- Notification overlay for suggestion errors and successful LLM responses, with a Copy Details button that copies verbose diagnostics.
- Built-in interpreter with input, output, tape viewer, diagnostics, and step limit protection.
- Debugger with start, step, continue, reset, and line breakpoint support.
- Compiler output modes for JavaScript, Bf*, original Ook!, and Dragon Palm assembly.
- Dragon Palm `.dgc` cartridge saving.
- Manual overlay with copyable code blocks, tutorial pages, Credits, and MIT License pages.
- On-boarding tutorial and categorized achievement badges with level progress.
- Ook! Mascot appears in the desktop top bar, can be disabled in Preferences, idles locally, snacks occasionally, celebrates successful runs/compiles/achievements, and gets angry on compile/debug/breakpoint errors.
- Orangutan Fact of the Day, selected from an embedded local fact bank and disableable in Preferences.
- Local persistence for progress, achievements, theme, language, layout, breakpoints, suggestions, and preferences.
- WCAG-minded controls, labels, focus states, and keyboard-friendly modal behaviour.

## Quick Start

Open [ook-ide.html](https://0xe25f.github.io/ook-ide/ook-ide.html) in a modern browser. That is it.

Try this:

```ook
Ook!++ say "Hi!"
```

Then switch the compiler to `Ook!` to see the same tiny programme as classic paired-token Ook!.

Try `Suggest` on rough input too:

```text
console.log("OOK")
prnt
loop
addd 2
```

With deterministic suggestions enabled, the IDE rewrites that into valid, annotated Ook!++ locally. If you enable the LLM service in Preferences, the response is validated as Ook!++ before it replaces the editor content.

## Interesting Fact

Orangutans often build a fresh sleeping nest high in the trees, bending and weaving branches into a platform before settling in. Good software also benefits from a comfortable place to think.

## Credits

Ook! was created by David Morgan-Mar. This IDE builds a friendly Ook!++ workshop around that classic esolang idea and includes Dragon Palm cart support for the supplied fantasy handheld target.

- Ook!: <https://esolangs.org/wiki/Ook%21> and <https://www.dangermouse.net/esoteric/ook.html>
- Bf*: <https://esolangs.org/wiki/Brainfuck>
- Dragon Palm: <https://github.com/0xe25f/dragon-palm/>
- TinyBase: <https://tinybase.org/>
- Lucide icons: <https://lucide.dev/>

Fonts use local browser and operating-system stacks. Icons are embedded inline SVGs. The app uses vanilla JavaScript plus an embedded TinyBase-style local store.

GNU Terry Pratchett

## License

Ook!++ IDE is MIT licensed.

Ookie the Orangutan used under license from Decent Enough Games. Ookie may not be reused for any other purpose than as a mascot within Ook!++ IDE without express written consent.

Copyright 2026, Agent 57951.
