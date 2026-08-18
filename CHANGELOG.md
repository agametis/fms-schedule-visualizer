# What's New

## Version 0.6.4 — 18 August 2026

**Entering times is now reliable.**

Previously, when a time field already contained values (for example `00:00:00`
taken over from a schedule), typing often did nothing — you had to select the
field content manually first before a new value was accepted.

This has been fixed:

- Clicking a time field (hours, minutes or seconds) immediately selects its
  content, so you can just type over it.
- Every keystroke is accepted, even when the field is already filled.
- The End Time field no longer loses focus while you are typing.

This applies to all time entries in the task editor — start and end times for
one-time, weekly and every-n-days schedules.

## Version 0.6.3 — Initial version

First documented release.
