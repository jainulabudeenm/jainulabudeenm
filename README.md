## Hey, I'm Zain

Product designer. I build agent tooling for Claude Code, mostly skills that encode a way of
thinking rather than a feature.

### Skills you can install

Two routes, same skill. In Claude Code, install as a plugin, which also gives you the
skill's `/<name>-init` setup command:

```
/plugin marketplace add jainulabudeenm/<name>
/plugin install <name>
```

Anywhere else, including Claude.ai, install the skill on its own:

```
npx <name>
```

Add `--project` to that second one to install into the current repo instead of your home
directory, so you can commit it and share it with a team.

One exception: `what-to-watch` was taken on npm, so that one is `npx @jainulabudeenm/what-to-watch`.
The plugin route uses the plain name like the rest.

| Skill | What it does |
|---|---|
| [cart-cop](https://github.com/jainulabudeenm/cart-cop) | Makes you defend a purchase before it approves one |
| [company-recon](https://github.com/jainulabudeenm/company-recon) | Investigates a company before you interview, from employee chatter rather than PR |
| [mobile-screen-eval](https://github.com/jainulabudeenm/mobile-screen-eval) | Audits a mobile screen against Nielsen's 10 heuristics, WCAG 2.1 AA, and iOS HIG plus Material guidelines |
| [name-cop](https://github.com/jainulabudeenm/name-cop) | Kills your weak name candidates instead of ranking them, using Alexandra Watkins' SMILE and SCRATCH frameworks |
| [tool-librarian](https://github.com/jainulabudeenm/tool-librarian) | Keeps a library of the tools you already vetted, clustered by the state of mind you reach for them in |
| [vault-keeper](https://github.com/jainulabudeenm/vault-keeper) | Three skills for a markdown vault: capture a note, save a chat, and groom the indexes and links so you never hand-maintain them |
| [what-to-watch](https://github.com/jainulabudeenm/what-to-watch) | Recommends from your own watch history rather than what is trending, with importers for Letterboxd, MUST and Trakt |

### Also here

- [unjargon](https://github.com/jainulabudeenm/unjargon), a plain-language glossary of dev tooling,
  because most explanations assume you already know the thing

### Elsewhere

[Portfolio](https://www.jainulabudeen.com) for the design work: case studies, and the AI
interventions I have shipped at work.

Most of what I learn ends up on LinkedIn before it ends up here.
