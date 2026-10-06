# Feature Wrap-up

A Codex skill for documenting a module or feature after implementation. It can produce a **branded, screenshot-led PDF for users** or a **technical SDN handoff in Markdown and PDF**. When you do not name an audience, it asks which version you want.

SDN means **Summary**, **Decisions needing answers**, and **Next available steps**. Both modes distinguish verified work from remaining work and link readers to fuller context when available.

## Install

Download the [skill ZIP](https://github.com/ojou10/feature-wrapup-skill/releases/latest/download/feature-wrapup.zip), or clone this repository. Copy the [`feature-wrapup`](feature-wrapup/) folder into your Codex skills directory (`~/.codex/skills/feature-wrapup`). Keep its `references/` and `agents/` folders with it.

## Use

You can invoke the skill explicitly or describe the job in ordinary language:

```text
Use $feature-wrapup to make a user PDF for the inventory count feature.
Show what is done and what is left, with screenshots from the demo app.
Match the app's colors and typography.
```

```text
Use $feature-wrapup for a technical SDN on the new approval flow.
Read the PR, tests, and open issues. Deliver both Markdown and PDF.
```

```text
Summarize the finished module for handoff, with pointers to the full context.
```

For the last prompt, the skill asks whether you want the user PDF, technical SDN, or both. It may also ask for access to the implementation, running app, or screenshots if those are needed to support the claims.

## Inputs and outputs

| Audience | Typical inputs | Output |
| --- | --- | --- |
| Users | Feature scope, release notes, running app or screenshots, brand cues | PDF with Done / What's left overview and screenshot-led workflow pages |
| Technical readers | Code or PR, issues, tests, design context | SDN Markdown and matching linked PDF |

The skill checks source material before calling work complete. It does not create fake screenshots of a real feature. If evidence or captures are unavailable, it states the gap in the result. The visual style adapts to the target product; the included [fictional example](examples/fictional-brief.md) is only a demonstration.

## Public examples

All example names, UI images, and feature details in this repository are fictional. No screenshots or text from the private PDF that inspired the skill are included.

- [User PDF](examples/harborboard-user.pdf)
- [Technical SDN Markdown](examples/harborboard-sdn.md) and [PDF](examples/harborboard-sdn.pdf)
- [Source brief](examples/fictional-brief.md)

## License

MIT. See [LICENSE](LICENSE).
