---
title: Netlify CLI dev command
description: Run netlify dev locally
---

# `dev`

<!-- AUTO-GENERATED-CONTENT:START (GENERATE_COMMANDS_DOCS) -->
Local dev server
The dev command will run a local dev server with Netlify's proxy and redirect rules


**Usage**

```bash
netlify dev
```

**Flags**

- `command` (*option*) - command to run
- `port` (*option*) - port of netlify dev
- `functionsPort` (*option*) - port for functions server
- `dir` (*option*) - dir with static files
- `functions` (*option*) - Specify a functions folder to serve
- `offline` (*boolean*) - disables any features that require network access
- `live` (*boolean*) - Start a public live session

| Subcommand | description  |
|:--------------------------- |:-----|
| [`dev:exec`](/commands/dev#devexec) | Exec command  |


**Examples**

```bash
$ netlify dev
$ netlify dev -c "yarn start"
$ netlify dev -c hugo
```

---
## `dev:exec`

Exec command
Runs a command within the netlify dev environment, e.g. with env variables from any installed addons


**Usage**

```bash
netlify dev:exec
```

**Examples**

```bash
$ netlify exec npm run bootstrap
```

---

<!-- AUTO-GENERATED-CONTENT:END -->
