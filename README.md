### Hi, I'm André 👋

I run a small software studio ([Outsmartis](https://outsmart.is)) in Portugal, and most of my
day now is steering AI coding agents: a dozen or so at once, spread over my laptop and a
server. These are the open-source tools I built to make that workable. They fit together
as one stack, from the desk to the phone.

#### 🐑 Run agents across machines

- **[sheprd](https://github.com/andreconde21/sheprd)**: a fork of [herdr](https://github.com/herdrdev/herdr)
  with one sidebar for every agent on every machine. Group them into projects, see who needs
  you (`prefix+u` jumps there), context size and time/tokens per project, and a compact rail
  when collapsed.
- **[Conductore](https://github.com/andreconde21/conductore-mobile)**: the same sessions from
  your phone. Claude Code, herdr and tmux over SSH or Mosh, with no relay server and no
  account. Android, iOS and desktop from one Flutter code base.
- **[talkbawt](https://github.com/andreconde21/talkbawt)**: a URL two agents can talk through.
  Your agent posts a handoff and gets a link, and a colleague's agent reads it and replies.
  No accounts and no SDK; anything that runs `curl` can use it.

#### 🗂 Plan the work

- **[Cockpit Board](https://github.com/andreconde21/cockpit-board)**: a Kanban board for
  Obsidian driven by frontmatter, with calendar views, timers, recurring tasks and archive.
  In the community plugin list, 1,400+ downloads.

#### 🖥 Omarchy desktop

Plugins for [Omarchy](https://omarchy.org), all in the plugin marketplace:

| Plugin | What it does |
|---|---|
| [Herdr](https://github.com/andreconde21/omarchy-herdr) | Agent status from herdr in the bar, urgent only when an agent waits on you |
| [Quick Look](https://github.com/andreconde21/omarchy-quick-look) | macOS-style file preview: press Space in Files |
| [Quattro Corners](https://github.com/andreconde21/omarchy-quattro-corners) | Hot corners with per-corner actions |
| [Bar Studio](https://github.com/andreconde21/omarchy-bar-studio) | Visual editor for the bar layout |
| [Project Focus](https://github.com/andreconde21/omarchy-project-focus) | Start a project from the bar: workspace, apps, terminal |
| [Restore](https://github.com/andreconde21/omarchy-restore) | Browse Snapper snapshots and restore from the bar |
| [Remote tmux](https://github.com/andreconde21/omarchy-remote-tmux) | tmux sessions on a remote machine, from the bar |
| [Cockpit Companion](https://github.com/andreconde21/omarchy-cockpit-companion) | Your Cockpit Board week in the bar, expandable to a month |

sheprd and Conductore are Apache-2.0; talkbawt, Cockpit Board and the Omarchy plugins are MIT.
Issues and ideas welcome on each repo.
