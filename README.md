# Puente Studio

An example workspace for building web applications in **Puente OS**.

Install the official Puente OS skills from the [`puente-os/agent-skills`](https://github.com/puente-os/agent-skills) marketplace.

We strongly recommend installing the skills before working in this workspace.

## Install in Codex

```bash
codex plugin marketplace add puente-os/agent-skills
codex plugin add puente-os@skills
```

Start a new Codex task after installation.

## Install in Claude Code

Run these commands inside Claude Code:

```text
/plugin marketplace add puente-os/agent-skills
/plugin install puente-os@skills
```

Restart Claude Code after installation.

## Project configuration

```bash
cp .env.example .env
```

Set the required variables without committing credentials to Git:

```env
BASE_URL=<base_url>
STUDIO_KEY=<puente_studio_placeholder>
```

See the [official marketplace](https://github.com/puente-os/agent-skills) for update instructions and the latest documentation.
