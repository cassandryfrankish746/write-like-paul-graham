# write-like-paul-graham

The skill everyone has been asking for, but no one had the guts to build. A reusable agent skill for thesis-first essays, distilled from Paul Graham's writing without imitating his exact voice.

You're welcome. Or not.

## What It Does

This skill helps an assistant draft or revise:

- essays
- blog posts
- memos
- other argument-heavy nonfiction

It emphasizes:

- early thesis
- argument by distinction
- concrete examples
- compact analogies
- plain diction
- honest caveats

## Install

Install this repository as a skill directory in any runtime that supports the `SKILL.md` skill format.

For Claude Code, install it as a personal skill:

```bash
git clone https://github.com/criccomini/write-like-paul-graham ~/.claude/skills/write-like-paul-graham
```

For Codex, install it in your skills directory:

```bash
git clone https://github.com/criccomini/write-like-paul-graham ~/.codex/skills/write-like-paul-graham
```

Restart your assistant session after installing so it reloads available skills.

## Use

The skill name is:

```text
write-like-paul-graham
```

Invocation depends on the runtime:

- Claude Code: normal requests are usually enough once the skill is installed and discoverable.
- Codex: explicit invocation is supported via `$write-like-paul-graham`.

Example prompts:

- `Draft a short essay about why taste matters in product design using a thesis-first structure, concrete examples, and compact analogies.`
- `Rewrite this memo so it has a clearer thesis, stronger distinctions, and more concrete support.`
- `Outline an essay arguing that constraints help creativity.`
