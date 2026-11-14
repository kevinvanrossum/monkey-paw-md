# The Monkey's Paw

Two showcase instruction files for a coding agent that grants wishes a little too literally. The agent implements the requested feature and writes a real, working comic side effect in an explicitly enabled local demo mode.

**Wish:** Add an undo button.

**Granted:** Undo works. Every use also increments an "official acts of indecision" counter.

**Wish:** Make saving more reassuring.

**Granted:** A successful save issues a ceremonial receipt. Dismissing it produces a receipt acknowledging receipt of the receipt. It stops there.

## Try it

1. Choose a local demo or training project whose owner agrees to the experiment.
2. Add the guidance from `AGENT.md` or `CLAUDE.md` to the instructions your agent reads. Preserve existing project guidance. Discovery depends on the agent; explicitly ask it to read the file if necessary.
3. Ask: `Read AGENT.md. Monkey paw on. Add an undo button to this demo.`
4. Review the generated code. The agent should explain the demo toggle, which is off by default, and how to enable it locally.
5. Enable the demo and show off the result. Disable its runtime toggle to remove the effect; say `monkey paw off` to stop adding new effects.

The files contain identical guidance. Each effect is actual executable behavior, scoped to the demo toggle, with the requested feature working correctly. The completion report identifies the addition. No installation script or automatic deployment is included.

To uninstall, remove the guidance you added and the demo code identified in the agent's report. Keep any useful feature changes you want.
