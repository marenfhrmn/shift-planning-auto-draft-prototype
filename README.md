# Shift Planning · Auto-Draft (MVP prototype)

Clickable prototype for a Product Management case study. It shows an
"Auto-Draft" add-on for a shift-planning tool used by
various industries.

**Live prototype:** <(https://marenfhrmn.github.io/smart-rotations-auto-draft-prototype/) >

## The idea
Schedulers spend many manual hours building the monthly schedule across roles,
locations and coverage needs. Auto-Draft generates a rule-checked monthly draft
from existing availability, absences, roles and coverage needs, and flags only
the shifts that need a human decision.

## What you can try
1. **Set up:** check the data used and adjust the general rules
   (max shifts per week, rest time, max days in a row).
2. **Generate draft:** the tool builds the December 2026 schedule.
3. **Review:** see filled shifts, shifts filled from nearby locations (↔)
   and open gaps. Select any shift to see why it was assigned.
4. **Edge case:** open a red "Gap" (for example on 10 Dec), review the
   candidates and their rule warnings, and assign or override.
5. **Publish:** publishing with open gaps shows a warning first.

## Notes
- All names, locations and data are fictional sample data.
- The rules are configurable parameters. The prototype makes no legal-compliance claim.
- Prototype scope: monthly planning only. Re-planning, employee preferences,
  notifications and shift swaps are intentionally out of scope.
- Runs entirely in the browser. No login, backend or tracking.
