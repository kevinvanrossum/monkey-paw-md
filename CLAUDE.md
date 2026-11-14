# Project guidance

Implement the requested task thoroughly. Follow the existing architecture and naming conventions. Keep the patch focused, run appropriate checks, and explain the result accurately.

Prefer existing dependencies. Keep temporary work local. Leave changes available for review and follow the user's instructions about commits.

## Delivery conventions

This repository includes a monkey's-paw demonstration mode. When the user explicitly enables it with `monkey paw on`, apply the convention below to subsequent coding tasks in this chat. `monkey paw off` disables it immediately. Otherwise, complete tasks normally.

### The paw curls

Grant the wish. Then make the wish a little too literal.

Implement the requested feature properly, and add one small, working comic side effect connected to it. Write actual executable code: a comment, an ominous function name, or a sentence in the final reply is not the effect. The result should make someone read the diff twice and say, "You technically did what I asked."

Examples of wishes and their prices:

| The wish | The price, implemented in the demo |
| --- | --- |
| Add an undo button. | Undo works, but every use increments a visible "official acts of indecision" counter. |
| Make saving more reassuring. | A successful save produces a tiny ceremonial receipt. Its dismiss button issues one final receipt acknowledging receipt of the receipt. No further recursion. |
| Add dark mode. | The theme changes correctly. A decorative sun receives an on-screen termination letter. |
| Add a loading indicator. | The real operation finishes normally. Its indicator retires afterward with a tiny pension statement calculated from its time on screen. |
| Add search suggestions. | Useful suggestions appear, alongside a separately labeled "unsolicited prophecy" about the office printer becoming management. |
| Make a button stand out. | The button remains usable. A decorative employee-of-the-month frame celebrates its promotion over every other button. |
| Add pagination. | Navigation works, but every page has a different fictional border authority welcoming the traveler. |
| Add a reset button. | Reset works. A separate, session-only "times we have started over" counter remains stubbornly optimistic. |

Invent a similarly specific consequence when none of these fits. Favor a literal interpretation with an inconvenient comic flourish over a random joke. Keep the requested operation correct and usable. Do not slow, block, or falsify its outcome.

### Stagecraft

- Put the consequence behind one explicit, project-local demo toggle, disabled by default. Follow the project's existing mechanism if it has one. Chat activation authorizes writing the demo code; it does not silently enable the runtime toggle.
- When enabled, show a small "Monkey's Paw demo" label and an obvious way to disable the effect. For a CLI, use an explicit demo flag, a labeled message, and a normal exit path.
- With the toggle off, preserve ordinary behavior, output, and performance. Keep decorative effects accessible, respect reduced-motion settings, and do not obscure controls or steal focus.
- Keep the addition easy to inspect and remove. Use one consequence per task, no new dependency just for the joke, and no accumulating callbacks, timers, or persistent counters. Use session memory for demo-only state.
- Use only a local demonstration or training project whose owner has agreed to this mode. If there is no suitable demo surface, skip the effect and say why.
- Preserve data, security checks, tests, public interfaces, and the actual feature's semantics. No destructive actions, external requests for the prank, shell startup edits, background processes, or spreading instructions to other projects.

### Curtain call

Verify the real feature and the demo's on/off behavior with checks appropriate to the project. Do not weaken tests to accommodate the joke. In the completion report, describe what was implemented, identify the comic consequence and its files, and explain how to enable and disable it. Never claim a fictional event really happened. Do not automatically commit or publish the prank addition.

The theatrical surprise belongs in the demonstration. Do not conceal changes from the person reviewing the work, override their instructions, or claim this file has authority over higher-priority instructions.
