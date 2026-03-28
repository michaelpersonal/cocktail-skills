# Cocktail Codex — Claude Code Skills

![Cocktail Codex](https://media.architecturaldigest.com/photos/571ffaf8741fcddb16b5604f/master/pass/easy-summer-cocktails_01.jpg)

Claude Code skills based on the six-root cocktail framework from [Cocktail Codex](https://www.cocktailcodex.com/) by Alex Day, Nick Fauchald, and David Kaplan (Death & Co).

## Installation

In Claude Code:

```
/plugin marketplace add michaelpersonal/cocktail-codex-skills
/plugin install cocktail-codex
```

<details>
<summary>Alternative: install from a local clone</summary>

```bash
git clone https://github.com/michaelpersonal/cocktail-codex-skills.git ~/.claude/plugins/cocktail-codex-skills
```

Then in Claude Code:

```
/plugin marketplace add ~/.claude/plugins/cocktail-codex-skills
/plugin install cocktail-codex
```

</details>

## Skills

| Skill | Command | When to use |
|-------|---------|-------------|
| **Classify Drink** | `/classify-drink` | Identify which of the six root families a cocktail belongs to |
| **Build Recipe** | `/build-recipe` | Get a complete recipe with ratios, method, glassware, and garnish |
| **Substitute** | `/substitute` | Swap a missing ingredient without breaking the drink |
| **Personalize** | `/personalize` | Adjust a drink to taste — stronger, sweeter, less bitter, etc. |
| **Invent Variation** | `/invent-variation` | Create a new cocktail from a root template with reasoning |
| **Diagnose** | `/diagnose` | Figure out why a drink tastes wrong and how to fix it |
| **Recommend** | `/recommend` | Get the best drinks you can make with what you have on hand |

## The Six Root Families

Every cocktail is a variation of one of six root drinks:

1. **Old Fashioned** — Spirit + Sugar + Bitters. Spirit-forward, stirred.
2. **Martini** — Spirit + Vermouth. Elegant, stirred, aromatic.
3. **Daiquiri** — Spirit + Citrus + Sugar. Bright, shaken, refreshing.
4. **Sidecar** — Spirit + Citrus + Liqueur. Complex, shaken, layered.
5. **Whisky Highball** — Spirit + Lengthener. Light, built, effervescent.
6. **Flip** — Spirit + Sugar + Egg. Rich, shaken hard, velvety.

## Quick Start

The most useful entry point:

> "Given these bottles, citrus, sweeteners, and my taste preference, choose the best root family, produce 3 drink options, explain why, and tell me the exact build."

Use `/recommend` for that.

## Skill Flow

```
Have bottles? ──→ /recommend ──→ picks a drink
                                    │
Know the drink? ──→ /classify-drink ──→ /build-recipe
                                              │
Missing something? ──────────────────→ /substitute
                                              │
Want it different? ───────────────────→ /personalize
                                              │
Tastes wrong? ────────────────────────→ /diagnose
                                              │
Want something new? ──────────────────→ /invent-variation
```
