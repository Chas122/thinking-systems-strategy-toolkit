# Thinking Systems Strategy Toolkit

Structured strategic analysis for small and medium-sized businesses, as a plugin for Claude.

Most businesses look at a decision from one or two angles. This toolkit gives you a structured way to look at it from several, with each analysis checked before you see it and every claim marked with where it came from.

## What it does

The plugin adds six skills to Claude.

| Skill | Use it when you ask |
|---|---|
| **Strategy guide** | "Help me think through this decision" or "Where do I start?" |
| **PESTEL analysis** | "What outside forces could affect my business?" |
| **Five Forces analysis** | "How competitive is my market?" |
| **Value chain analysis** | "Where is my business strong, and where does it leak?" |
| **SWOT analysis** | "What are my strengths, weaknesses, opportunities and threats?" |
| **Growth options analysis** | "How should my business grow?" (the Ansoff Matrix) |

You can ask for any analysis on its own. If you are not sure which you need, the strategy guide asks a few questions, chooses the analyses that fit your decision, and runs them in an order that lets each one feed the next: the wider world first, then your industry, then inside your business, then a SWOT where they meet, then your options.

## How it differs from just asking for a SWOT

- **It starts with the decision.** Each analysis asks what you are trying to decide, over what period, and with what constraints, before it begins.
- **It checks its own work.** Every analysis is drafted, tested against a checklist for that framework, and revised. For example, the SWOT check moves anything internal out of Opportunities, and removes strengths that every competitor would also claim.
- **It shows its sources.** Each claim is marked as coming from you, from a web search, from general knowledge, or from an assumption.
- **It rates its confidence.** Key findings are rated High, Medium or Low, with a reason.
- **It says what it does not know.** Each analysis ends with open questions and limits.
- **Analyses build on each other.** Each one ends with a findings table that later analyses pick up, so a SWOT run after a competitor analysis uses what that analysis found.

## Example prompts

- "Run a SWOT analysis on my business. We are a four-person accountancy practice losing clients to online services, and I am deciding whether to move to fixed monthly packages."
- "How should my business grow? I own a cafe near a railway station, busy in the morning and quiet after 2pm. I have a small budget and do not want a second site."
- "I need help with a decision and do not know where to start. A housebuilder has asked my joinery firm to fit out their show homes, which could double our turnover."
- "Do a PESTEL for a domiciliary care agency in Wales over the next three years."

## How to use it

1. Install the plugin. Version 0.2.0-beta is a private beta and is not in the Claude directory: install it from the plugin file you were given.
2. Start a conversation and describe your business and the decision you are facing. Or name the analysis you want.
3. Answer the few questions Claude asks. The more you tell it about how your business really works, the better the result.
4. Correct anything that is wrong. Your corrections are the best evidence it has.

Turn on web search if you have it. The analyses use it to check current facts about your market and competitors. Without it, they still run, and mark those points as general knowledge or assumptions.

## What data it uses

- The plugin contains instructions only. It has no code, no connectors and no servers.
- It does not connect to your accounts, files or business systems.
- It does not send anything anywhere. It works only with what you type or attach in your conversation with Claude, and with web search if you have turned that on.
- Your conversation is handled by Claude under your existing Claude terms, as it would be without the plugin.
- An analysis may ask whether you have a document that would help, such as your latest profit and loss account or a tender pack. Sharing one is your choice. You can remove staff and customer names first, or type the main figures instead.
- Where you are not sure of a figure, it may use a typical range for businesses like yours. It marks these as general knowledge, never as your own figures, and tells you whether the answer depends on them.

## Limits

- This is structured thinking support, not professional advice. For legal, tax, financial or regulatory decisions, check with a qualified adviser.
- An analysis is only as good as its evidence. Where most findings are low confidence, the right next step is to find things out, not to decide.
- These frameworks were developed mainly in large-company and Western business-school settings. The skills adapt them for smaller businesses and say so when one fits poorly.

## About the frameworks

PESTEL, Five Forces, the value chain, SWOT and the Ansoff Matrix are standard, widely published strategy frameworks. The wording, checklists and method in this plugin are original to Thinking Systems. The plugin is not affiliated with or endorsed by the originators of any framework.

## Want a person involved?

The toolkit helps you structure your thinking. For a tailored analysis with human judgement, book a conversation at [thinkingsystems.uk](https://thinkingsystems.uk).

## Support

Questions and problems: open an issue on this repository, or email charlie@thinkingsystems.uk.

## Licence

MIT. See [LICENSE](LICENSE).

## Version

0.1.0: first release. Five analyses and the strategy guide. More analyses are planned.
