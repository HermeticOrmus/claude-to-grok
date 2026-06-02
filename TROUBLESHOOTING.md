# Troubleshooting (Claude to Grok Migration)

## claude-exorcist refuses to start (no covenant)

See the skill's own TROUBLESHOOTING.md and sacred rules. Intent must be declared.

## Skills not appearing after git clone to ~/.grok/skills/

Restart the Grok session / TUI. Check `~/.grok/docs/user-guide/08-skills.md`.

Some skills have frontmatter triggers — use those phrases or the dir name.

## Old Claude handoffs / memory don't transfer perfectly

Use ormus-pickup on a HANDOFF.md written by the Claude version. It is designed to be robust. For full memory, use absorb + manual review of CLAUDE.md / MEMORY.md (then exorcise them).

## Want the old claude-code-skills behavior?

The claude-code-skills repo is still maintained for hybrid or reference use. The grok-* collections are the forward path.

## More help

- Official: `~/.grok/docs/user-guide/`
- Specific skill: its USAGE.md or SKILL.md
- The linked repos (exorcist, grok-code-skills, ormus-*)
