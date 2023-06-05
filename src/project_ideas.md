# Project Ideas

## parser in {{language}} 

The more the merrier. As noted [here](https://github.com/nvim-neorg/neorg/blob/main/ROADMAP.md#external-tooling), "many parsers can be created for it without forming annoying "'dialects'".

## Graph Visualization

→ something like the graph visualization feature of Obsidian

## Improve Internationalization (i18n)

Almost goes without saying in an open-source project, but it bears saying anyway.

## *TeX Support

[Orgmode can do this](https://orgmode.org/manual/Embedded-LaTeX.html), why can't we?

## Advanced date and time support

Likely best implemented as a core module?

## neorg-planager (my personal obsession at the moment)

A module for as-declaratively-as-possible creating Gantt timelines and schedules from roadmaps, projects, and tasks. Designed to take care of most of the "what" and "when" and "how" up front so as to reduce cognitive load. Ideally, this will take care of ensuring that day-to-day time usage aligns with long-term priorities. Generally in line with the GTD methodology, but tailored to my needs. Robustness to unforeseen circumstances and ability to track completion and view statistics (a bit [like Anki](https://docs.ankiweb.net/stats.html), perhaps) are essential.

One of the biggest features is the ability to use custom priority-respecting scheduling algorithms to go from roadmaps, Gantts, projects, etc. to fine-grained schedules, and also to have this accessible through my phone (for now via Telegram API, later via Signal API or even a custom App).