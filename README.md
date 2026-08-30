# Case Files

This repo tracks the daily security investigations I do in my homelab. Each day I pick one alert or finding, investigate it, and write up a case file covering the indicators, the steps I took, the evidence I found, and my conclusion. The point is to build a record I can go back to and learn from.

Every 30 days or so I'll write a longer post summarizing what the cases added up to.

Everything here comes from my own lab. Nothing is from an employer or any system I don't own.

## Case file format

Each case uses the same seven sections:

- **The question** - what I'm trying to figure out
- **Indicator / subject** - the alert, host, and time range I started from
- **What I did** - the pivots and tools, in the order I used them
- **What I found** - the reconstructed timeline and the evidence behind it
- **Verdict & confidence** - what happened and how sure I am
- **One thing I learned** - a field, a gap, or a pivot worth remembering
- **Tomorrow's first move** - where to pick up next

Some cases also include a detection rule written against the activity investigated.

The blank template is in `cases/TEMPLATE.md`.
