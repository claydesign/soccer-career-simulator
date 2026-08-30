# MyFootyLife v1.004

A mobile-first soccer career simulator.

## v1.004 changes
- Redesigned career start screen based on the approved MyFootyLife reference design.
- Overall increases through matches/training and through successful situations.
- European competitions are mutually exclusive per season: UCL, UEL, or UECL, never more than one.
- Season-end screen explicitly reports the team's league finishing position.
- Different clubs approach the player in each new transfer window/season.
- Starting wage is $10,000/week at age 16 and scales with overall + club tier.
- Contracted players keep their current wage until the contract expires.
- A multi-year contract gives a stay/current-club path while the contract is active.
- Other clubs may still make higher-wage approaches while the player is contracted.
- Situation events use a three-choice risk/reward structure:
  A = easy / high success / low reward
  B = medium / medium success / medium reward
  C = hard / lower success / high reward
- Success chances are fixed, visible numbers for each situation.
- Positive outcomes do not add fatigue.
- Relationship mechanics removed.
- Tracked attributes: team trust, coach trust, reputation, overall, appearances, goals, assists.
- Situation results can move those attributes up or down.
- LocalStorage saves the career in the browser.

## Files
- `index.html` — complete game
- `manifest.webmanifest` — install metadata
- `README.md` — version notes
