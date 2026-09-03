# Contraband Marketplace (Legacy)

> **New installs should use [8gnc — Brand Growth Diagnostic](https://8gnc.io/products/8gnc).** The maintained successor packages the same method family behind one diagnostic router for Claude Code, ChatGPT, and Codex: <https://github.com/Branded-Mayhem-Collective-LLC/8gnc-plugin>.

“Full Mayhem Stack” is retired as the umbrella bundle name. This repository remains available so existing Claude Code installations can keep updating the six independent specialist plugins. It will not become the cross-platform aggregate.

## Existing installations

In Claude Code:

```text
/plugin marketplace add Branded-Mayhem-Collective-LLC/contraband-marketplace
/plugin install brandprint-engine@contraband
/plugin install productprint-engine@contraband
/plugin install content-creative-lab@contraband
/plugin install seo-visibility-toolkit@contraband
/plugin install conversion-architecture@contraband
/plugin install sales-accelerator@contraband
```

Verify with `/plugin list` — you should see 6 plugins enabled, totaling 37 skills.

The six specialist repositories remain public, independent, and installable on their own. They are not replaced or rewritten by the successor package.

For a new aggregate installation, use 8gnc instead:

```text
/plugin marketplace add Branded-Mayhem-Collective-LLC/8gnc-plugin
/plugin install 8gnc@8gnc
```

## What's in the stack

| Plugin | Skills | What it does |
|---|---|---|
| [`brandprint-engine`](https://github.com/Branded-Mayhem-Collective-LLC/brandprint-engine) | 10 | 6-layer brand strategy chain + deep-research engine → consulting-grade Brand Strategy & Competitive Positioning Report |
| [`productprint-engine`](https://github.com/Branded-Mayhem-Collective-LLC/productprint-engine) | 8 | 6-layer product strategy chain: Playing-to-Win cascade, Now/Next/Later roadmap, adversarial pre-mortem → Integrated Product Strategy Thesis |
| [`content-creative-lab`](https://github.com/Branded-Mayhem-Collective-LLC/content-creative-lab) | 8 | Voice profiling, humanization, narrative structure, focus-group simulation, Mayhem Method AI workflows |
| [`seo-visibility-toolkit`](https://github.com/Branded-Mayhem-Collective-LLC/seo-visibility-toolkit) | 5 | DataForSEO automation, AI-visibility tracking, local-services SEO matrix, ai-agent-readiness audits, AI-commerce data density |
| [`conversion-architecture`](https://github.com/Branded-Mayhem-Collective-LLC/conversion-architecture) | 3 | Neuro-design playbook, UX/UI choice-architecture, fairness anchor pricing ladder |
| [`sales-accelerator`](https://github.com/Branded-Mayhem-Collective-LLC/sales-accelerator) | 3 | Pitching pivot methodology, outreach-diagnosis framework, sales-simulator practice arena |

## Updates

When any individual plugin ships an update, refresh the catalog and pull:

```text
/plugin marketplace update contraband
/plugin update brandprint-engine
```

(Or `/plugin update --all` to update everything at once.)

## License

Every plugin in this marketplace is MIT-licensed. Use them, fork them, ship client work with them. Outputs you produce with the skills are yours.

## Support

- Canonical 8gnc plugin: https://8gnc.io/products/8gnc
- Email: hello@brandedmayhem.com
- Per-plugin issue trackers: see each individual repo
