<!-- This file renders on https://github.com/Don-Works -->

```
  ####   ###  #   #       #   #  ###  ####  #   #  ###
  #   # #   # ##  #       #   # #   # #   # #  #  #   #
  #   # #   # # # #       #   # #   # #   # # #   #
  #   # #   # #  ##       # # # #   # ####  ##     ###
  #   # #   # #   #       # # # #   # # #   # #       #
  #   # #   # #   #       ## ## #   # #  #  #  #  #   #
  ####   ###  #   #        # #   ###  #   # #   #  ###
```

# Don Works

**Open source by [Revitt](https://revitt.co).**

[![Website](https://img.shields.io/badge/donworks.co.uk-c6ff1a?style=flat-square&labelColor=050604)](https://donworks.co.uk)
[![License](https://img.shields.io/badge/license-AGPL--3.0-c6ff1a?style=flat-square&labelColor=050604)](https://www.gnu.org/licenses/agpl-3.0.en.html)
[![From Revitt](https://img.shields.io/badge/from-Revitt-050604?style=flat-square&labelColor=c6ff1a)](https://revitt.co)

Don Works is where we open up the tools we build at [Revitt](https://revitt.co). We make them to do our own work properly, and when one turns out to be useful beyond our own projects, we share it here for anyone to pick up and run with.

Everything lives on GitHub, free and open. As each piece proves itself, we open it up — so watch this org for the next ones landing.

---

## The tools, opened up

### `▍` MCPlexer

> The agent gateway for MCP tools.

The gateway every Revitt agent runs through. It decides which tools an agent can reach based on the folder you're working in, keeps your secrets out of the model, asks before anything risky, and keeps a record of every call. A bit like `direnv`, but for AI tools.

[![Repo](https://img.shields.io/badge/GitHub-mcplexer-2ea4e0?style=flat-square&logo=github&labelColor=050604)](https://github.com/Don-Works/mcplexer)
[![Site](https://img.shields.io/badge/mcplexer.com-2ea4e0?style=flat-square&labelColor=050604)](https://mcplexer.com)

### `▍` brw

> A real browser for AI agents.

brw drives a real, visible Chrome window so an agent can work on the actual web — signed-in tabs, real clicks and forms, and a check after every step that what it tried to do actually happened. Exposed over MCP and HTTP.

[![Repo](https://img.shields.io/badge/GitHub-brw-ff2ec4?style=flat-square&logo=github&labelColor=050604)](https://github.com/Don-Works/brw)

### `▍` Resident

> A macOS gauge for the memory your local models live in.

Activity Monitor says memory is 83% full. That number is true and useless. Resident is a macOS menu bar gauge that measures the three things that actually decide whether local inference is fast — whether the weights are resident, how much the GPU is allowed to hold, and the memory-bandwidth decode ceiling per model — and tells you which one is currently binding, with live tok/s.

[![Repo](https://img.shields.io/badge/GitHub-resident-f5a623?style=flat-square&logo=github&labelColor=050604)](https://github.com/Don-Works/resident)

### `▍` Handler

> A macOS watchdog for the ceilings that panic your Mac.

When macOS exhausts a system-wide limit — most often the open-file table — `launchd` dies and the kernel panics with `initproc exited`, and your Mac reboots mid-work with no warning. Handler shows how close you actually are, names the process eating the headroom, tells you which files it is holding, fits a trend over time to turn growth into a deadline, and can opt in to auto-reclaim before the machine falls over.

[![Repo](https://img.shields.io/badge/GitHub-handler-f87171?style=flat-square&logo=github&labelColor=050604)](https://github.com/Don-Works/handler)

### `▍` Reminders MCP

> Apple Reminders, drivable by an agent.

Your Reminders lists as twelve MCP tools in one Swift binary — due dates, alarms, repeats, priorities and notes, read and written straight through EventKit. An agent works the same list you do, on the same Mac, with no sync service in between.

[![Repo](https://img.shields.io/badge/GitHub-reminders--mcp-7c5cff?style=flat-square&logo=github&labelColor=050604)](https://github.com/Don-Works/reminders-mcp)

### `▍` More on the way

> The rest of the bench.

We build a lot of tooling at Revitt to keep our own work running. As each piece proves itself, we open it up here.

[![GitHub](https://img.shields.io/badge/Don--Works-on%20GitHub-c6ff1a?style=flat-square&logo=github&labelColor=050604)](https://github.com/Don-Works)

---

## Why we do this

We look after people, and we build tools. That's the whole idea behind Revitt, and it's the whole idea behind Don Works.

- **We start with people.** Every tool here exists because it made someone's actual work easier — ours, a client's, or both.
- **We build things that work.** These aren't experiments we threw over the wall. They're the tools we run our own delivery on, every day.
- **We share so it gets better.** Good tools go stale when you keep them to yourself. Open them up and people find the bugs, the missing pieces, and the better ideas.

---

## Licence

Everything here is released under **AGPL-3.0**. In plain terms: you can use these tools, change them, and build on them however you like, for free. The one thing we ask is that if you improve them, you share those improvements back — even if you're running a changed version as a service.

If that doesn't fit how your business works, [talk to us at Revitt](https://revitt.co/?utm_source=github&utm_medium=referral&utm_campaign=don_works_open_source&utm_content=org_readme_commercial) about a **commercial licence** — that's one of the ways the open work and the paid work look after each other.

---

<div align="center">

**[donworks.co.uk](https://donworks.co.uk)** · **[github.com/Don-Works](https://github.com/Don-Works)** · **[revitt.co](https://revitt.co)**

`·· ·· ··` Made by Revitt — open for everyone `·· ·· ··`

</div>
