# 7 Steps to Win: Manager Edition

A coaching tool for first line sales managers. Sellers learn the 7 Steps to Win; this helps managers coach them through it.

- **Coaching guides** for each step: the seller's job, the manager's job, the metric to watch, coaching questions, red flags, when to step in, and a "ready for the next step?" checklist.
- **Deal Doctor**: 18 common situations that stall deals (no meeting, wrong person, no urgency, gone dark, stalled, no budget, competition, price, procurement, and more). Each gives diagnostic questions, plays to try in order, a talk track, the manager's move, and when to walk away. Copy a coaching plan straight to a seller.
- **Funnel check**: enter weekly counts for the team or a seller to see which step's conversion is breaking.
- **Team Check**: add your sellers and rate each one Focus, Building, or Strong by step to pick coaching priorities and a team training topic.

## Running it

A single static file, `index.html`, with no build step. Open it in a browser or serve it with GitHub Pages.

Everything you enter (team names, funnel numbers, ratings, checklists) is saved in your own browser only. Nothing is sent anywhere.

## Editing content

All content lives in the `<script>` block of `index.html`:

- `STEPS` holds the seven step coaching guides
- `SC` holds the Deal Doctor scenarios
- `RATES` holds the funnel conversions and default targets
