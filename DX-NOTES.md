# Developer experience notes

Setting up Midnight on macOS with Claude Code, 30 Oct 2026.

## What worked
- Midnight Expert's doctor command clearly listed what was missing and offered fixes.
- Claude Code created and compiled a hello-world contract in about 30 seconds (compiler v0.35.0).
- `disclose()` makes privacy the default: the compiler forces you to declare anything that becomes public.

## Friction
1. Adding the plugin marketplace didn't install any plugins. The commands only appeared after a separate install step.
2. Claude Code needed a login before anything worked.
3. The doctor offered the latest compiler, while the installation docs advise pinning a version that matches the target network. These looked inconsistent to me.
4. The doctor showed red FAILs for optional plugins. A new developer could read that as a broken setup.

## What I'd measure
- Time from first install command to first successful compile
- Share of new developers who reach a first compile without help
- Most common failure point during setup
