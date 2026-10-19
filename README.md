# Nomad Notes

A travel planner built for long-term travel. Trips, flights, stays, transfers, budget, entry rules and stay limits in one page, with a clear split between what you have **paid**, what you have **committed** to, and what is only **estimated**.

**Live demo:** https://tayloramartin.github.io/nomad-notes/

The demo opens with an example itinerary (US, Iceland, Slovenia, Balkans, Serbia, Georgia). Everything in it is made up. Changes you make are saved only in your own browser.

![Budget tab](screenshots/budget.png)

## What it shows
- **Budget that tells the truth.** Remaining = budget − paid. Projected leftover also subtracts committed and estimated costs. Multi-currency, converted to USD, with the real amount charged locked in for paid items.
- **Transfers needed.** "Transfer $X to <account> before <date>", grouped into two-week windows.
- **Refund badges** on bookings: refundable until a date, partly refundable, non-refundable, or window closed.
- **Stay limits for any passport.** Days per entry, or days in any rolling window (for example 90 in 180).
- **Warnings** for nights with no place to stay and for free-cancellation deadlines.
- **Travel prep:** entry rules, health records, documents, rewards.
- **Two themes:** Midnight and Pastel.

## More screens
![A trip, with refund badges and a missing-night warning](screenshots/trip.png)
![Stay limits for different countries](screenshots/stay-limits.png)

## Notes
This repository contains the built demo only (`index.html`, one self-contained file). It needs an internet connection for fonts and React.
